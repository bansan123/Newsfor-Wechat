

Wechat - 小程序
------
> 后面会继续开发完善，并放出相关php接口代码 ～～
>
> 志同道合的朋友可以Fork，一起撸
>
> 官方文档: https://mp.weixin.qq.com/debug/wxadoc/dev/?t=1475052055457
>

目录结构
------
```shell
|--- api & WebService Api                 数据接口存放目录
|--- function & Custom Function Library   自定义函数库
|--- images & Img Resources               图片资源
|--- pages & View Dir                     Controller
|--- public & Public directory            公共目录
|--- template & Public View               通用模版
|--- uploads & Dowloads Files Dir         公共下载目录
|--- utils & Public Function              通用函数
```

模板目录
------
* 1、template [模块名称][页面名称]
* 2、template 目录以模块划分,模块内的页面放在 [模块名称][页面名称] 内
* 3、通用模版放在 [模块名称] 内
