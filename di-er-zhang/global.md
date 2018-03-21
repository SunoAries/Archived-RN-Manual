#### Global

定义标题大小、文本常规大小、按钮文本大小、列表文本大小、菜单文本大小、最小文本大小、设备尺寸......

#### Code Example

```
export const titleSize=36;

export const commonTextSize=26;

export const btnTextSize = 26;

export const listTextSize = 26;

export const menuTextSize = 30;

export const minTextSize = 24;

let Dimensions = require('Dimensions');

const {width, height} = Dimensions.get('window');

export function scale(pix) {
    return pix * (width / (DEVICE == 'PAD' ? 2048 : 750))
}
```

#### Use Example

```
import * as Global from '../../util/Global';

const styles = {
    ......
    title: {
        fontSize: Global.scale(Global.titleSize),
        color: '#333333',
        backgroundColor: '#f2f2f2'
    },
    footer: {
        marginTop: Global.scale(180)
    },

    ......
}
```



