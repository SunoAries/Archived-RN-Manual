#### AppUtils

主要包含获取图片地址、资源链接、转换大小、版本检测等功能。例如funtion  getImageUrl 、function getResUrl、function transSize、function versionCheck.

#### Code example 

```
export function getImageUrl(name) {
    if (name) {
        return baseUrl + "download/userResource/img.do?fileName=" + name;
    } else {
        return "";
    }
}

```



