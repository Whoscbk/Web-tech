# Web-tech
HTML+CSS+Javascript  

### HTML BASIC
1. ctrl + ? **注释**  
2. **元素** : element  
    element = (begin tag) + (end tag) + 元素内容 + 元素属性（局部属性/全局属性）  
空元素：没有end tag  
3. &lt;html lang="en"&gt;  
    根元素    
    lang属性： language,全局属性  
4. head 头文件  
    meta 元数据--附加信息  
5. 文本元素  
    **h1~h6**: 标题  
    **p**: paragraph  
    *lorem* 乱数假文  
    **span**: 无语义 仅用于设置样式  
    **pre**: 预格式化文本元素  
        i.e.取消空白折叠  
6. HTML entity:  
    &lt; - <  
    &gt; - >  
    &copy;  
    &amp;  
7. a元素  
    href: 跳转地址； 跳转某个锚点； 功能链接(执行javascript:/mailto:发送邮件/拨号tel:)  
    id: 全局属性，表示元素在文档中的唯一编号(用于锚链接)  
    target: 表示跳转窗口位置  
        _self: 在当前页面窗口中打开  
        _blank： 在新窗口中打开  
8. 路径的写法  
    绝对路径: schema://host:port/path  
        schema: http,https,file  
        host: 域名/IP地址  
        port: http(默认 80)，https(默认 443)  
    相对路径：./ 表示当前资源所在目录 | ../ 返回上一级目录  
9. 图片元素  
    img (空元素)：src,alt  
    src: source  
    alt: 当图片失效时替代的文本  
    usemap  
10. map 元素  
    area  
11. figure 元素：用于把图片、图片标题、描述包裹起来  
    子元素： figcaption -- 标题  
12. 多媒体元素  
        video src  
            controls 控制视频控件的显示  
            autoplay 自动播放  
            muted 静音播放  
            loop 循环播放  

        audio src  
            同上  
