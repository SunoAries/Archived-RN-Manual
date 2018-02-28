## Button {#Button}

Button is a pure[NativeBase](https://nativebase.io/)component.  
Buttons are the integral part of an application. They are used for various purposes like, submit or reset a form, navigate, performing interactive actions such as showing or hiding something in an app on click of the button, etc.



```
import React, { Component } from 'react';
import { Container, Header, Content, Button, Text } from 'native-base';
export default class ButtonExample extends Component {
  render() {
    return (
      <Container>
        <Header />
        <Content>
          // NativeBase default style
          <Button>
            <Text>Click Me! </Text>
          </Button>
        </Content>
      </Container>
    );
  }
}
```

![](/assets/import.png)

