## Button {#Button}

Button is a pure[NativeBase](https://nativebase.io/)component.  
Buttons are the integral part of an application. They are used for various purposes like, submit or reset a form, navigate, performing interactive actions such as showing or hiding something in an app on click of the button, etc.

#### Contents

1. Button Theme

2. Transparent Button

3. Outline Button

4. Rounded Button

5. Block Buttton

6. Full Button

7. Icon Button

8. Button Size

9. Disabled  Button

#### Basic Exapmlpe

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

#### Configuration

| Property | Default | Option | Description |
| :--- | :---: | :---: | :--- |
| style |  |  | Defines button style |
| active |  | boolean | Boolean value to describe state  of Button |
| transparent | true | boolean | Renders child element of button |
| bordered |  |  | Applies outlinne button style |
| rounded |  |  | Renders button with slightlyroun  shaped edges |
| block |  |  | Block level button |
| full |  |  | Full width button |
| disabled |  |  | Disables click option for button |
| small |  |  | For small size button  |
| large |  |  | For large size button |
| iconRight |  |  | Right Padding for the icon |
| iconLeft |  |  | Left Padding for the icon |
| light |  |  | Add a light white background color to your component |
| primary |  |  | Add a blue background color to your component |
| success |  |  | Add a green background color to your component |
| info |  |  | Add a light blue background color to your component |
| warning |  |  | Add a yellow warning background color to your component |
| danger |  |  | Add a red background color to your component |
| dark |  |  | Add a black background color to your component |

#### View

![](/assets/import.png)

\#asdf

