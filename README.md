# WKWebView OC版 一款IOS8以后的web加载神器
WKWebView 支持POST请求 加载本地页面 直接加载网页 JS交互 集成支付宝/微信URL支付功能  仿微信返回按钮
```
/**
 加载纯外部链接网页

 @param string URL地址
 */
- (void)loadWebURLSring:(NSString *)string;
/**
 加载本地网页
 
 @param string 本地HTML文件名
 */
- (void)loadWebHTMLSring:(NSString *)string;

/**
 加载外部链接POST请求(注意检查 XFWKJSPOST.html 文件是否存在 )
 
 @param string 需要POST的URL地址
 @param postData post请求块
 */
- (void)POSTWebURLSring:(NSString *)string postData:(NSString *)postData;
```


![Aaron Swartz](https://github.com/XFIOSXiaoFeng/WKWebView/blob/master/WKWebView/XFWkwebView/testimage.gif)
