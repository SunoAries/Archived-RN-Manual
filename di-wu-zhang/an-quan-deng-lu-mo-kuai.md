#### 登录模块

该模块主要实现用户的注册，登录。包含用户的密码校验、密码失效等功能。

#### Code Example

```
function router() {
    return (
        <Router onExitApp={() => onExitApp()}>
            <Scene key="root" hideNavBar={true}>
                {Platform.OS === 'ios' ? null : <Scene key="splash" component={Splash} initial/>}
                <Scene key="login" component={Login} type={ActionConst.REPLACE}/>
                 .......
                 </Scene>
        </Router>
    )
}

```

#### 



