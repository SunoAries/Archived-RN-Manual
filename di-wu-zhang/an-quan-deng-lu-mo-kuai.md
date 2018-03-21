#### 登录模块

该模块主要实现用户的注册，登录。包含用户的密码校验、密码失效等功能。

#### Code Example

```
//定义登录路由

class App extends React.Component {
    render() {
        return <Provider store={configureStore(initState)}>
            {router()}
        </Provider>
    }
}

function router() {
    return (
        <Router onExitApp={() => onExitApp()}>
            <Scene key="root" hideNavBar={true}>
                {Platform.OS === 'ios' ? null : <Scene key="splash" component={Splash} initial/>}
                <Scene key="login" component={Login} type={ActionConst.REPLACE}/>
                //路由登录模块 
                 .......
                 </Scene>
        </Router>
    )
}

export default App;


//登录组件

class Login extends Component {
    constructor(props) {
        super(props);
    }
    
     render() {
     ......
     <Container style={styles.bottom}>
            <Image style={styles.bottomBack} source={DEVICE == 'PAD' ? require('../../resources/img/login.jpg') : require('../../resources/img/login.jpg')}>
                <Input value={userName} style={styles.input} placeholder="请输入用户名"
                    icon='person'
                    onChange={(value) => {
                        handleInputChange('userName', value);
                    }} />
                <Input value={pwd} style={styles.input} placeholder="请输入密码"
                    icon='lock' showPwd secureTextEntry
                    onChange={(value) => {
                        handleInputChange('pwd', value);
                    }} />
                <CheckBox style={styles.check} text="记住用户名" textColor='#ffffff' onCheckChange={(check) => {
                    handleInputChange('remember', check);
                }} check={remember}></CheckBox>
                <Container style={styles.loginBtn}>
                    <Button onPress={() => {
                        loginStart(userName, pwd, remember)
                    }} disabled={!(userName.trim().length > 0 && pwd.trim().length > 0)} buttonText="登录" info
                        full style={Object.assign({}, styles.loginBtn, !(userName.trim().length > 0 && pwd.trim().length > 0) ? {} : { backgroundColor: '#039ae3' })}>
                        <Text>登录</Text>
                    </Button>
                </Container>
            </Image>
    </Container>
     
     ......
     
     }
}
```

#### 



