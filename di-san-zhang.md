#react-native-router-flux
*   在一个中心区域定义可切换 scene 模块
*   在使用过程中，跟 react-native 提供的 navigator 的区别是你不需要有 navigator 对象
*   你可以在任意地方使用简单的语法去控制 scene 的切换，如：Actions.login({username, password}) or Actions.profile({profile}) or 甚至Actions.profile(123)
*   所有的参数将被注入到 this.props 中给 Scene 组件使用。



定义你所有的路由在一个React组件里

```
    const App = () => (
      <Router>
        <Stack key="root">
          <Scene key="login" component={Login} title="Login"/>
          <Scene key="register" component={Register} title="Register"/>
          <Scene key="home" component={Home}/>
        </Stack>
      </Router>
    );
```
用一个简单的API调用从一个页面导航到另一个页面
```
    
    // 导航到最上层路由 'home'
    Actions.home(PARAMS)
    
    // 后退 (比如退出当前导航栈)
    Actions.pop()
    
    // 刷新当前页面，并注入特定参数
    Actions.refresh({param1: 'hello', param2: 'world'})
```
