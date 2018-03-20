#### AppUtil

主要包含获取图片地址、获取资源链接、大小转换、版本检测。如function getImageUrl 、function getResUrl、transSize、versionCheck



#### Code Example

```
const baseUrl = 'http://172.16.11.21:6131/mmp-web/';

export function getImageUrl(name) {
    if (name) {
        return baseUrl + "download/userResource/img.do?fileName=" + name;
    } else {
        return "";
    }
}
```





