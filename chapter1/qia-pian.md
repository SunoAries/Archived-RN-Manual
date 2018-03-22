## 按钮


#### 基础使用示例

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

#### 按键配置

| Property | Default | Option | Description |
| :--- | :---: | :---: | :--- |
| style |  |  | 定义按钮样式 |
| active |  | boolean | 描述按钮状态 |
| transparent | true | boolean | 渲染按钮子元素 |
| bordered |  |  |应用边框 |
| rounded |  |  | 渲染按钮，带有微微隆起的边缘 |
| block |  |  | 块级按钮 |
| full |  |  | 全宽按钮 |
| disabled |  |  | 禁用按钮的点击选项 |
| small |  |  | 对于小尺寸的按钮  |
| large |  |  | 对于大尺寸的按钮 |
| iconRight |  |  |图标的右填充 |
| iconLeft |  |  | 左填充图标 |
| light |  |  | 为您的组件添加浅白色背景色 |
| primary |  |  | 为您的组件添加蓝色背景色 |
| success |  |  | 为您的组件添加绿色背景色 |
| info |  |  | 为您的组件添加淡蓝色背景色 |
| warning |  |  | 为您的组件添加一个黄色的警告背景色 |
| danger |  |  | 为您的组件添加红色背景色 |
| dark |  |  |为您的组件添加黑色背景色 |

#### View

![](/assets/import.png)

