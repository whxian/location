# location
### js获取页面URL地址，判断URL是否包含具体值

window.location.pathname　//设置或获取对象指定的文件名或路径

window.location.href　//设置或获取整个 URL 为字符串

window.location.origin // 获取当前页面的域名

window.location.port　//设置或获取与 URL 关联的端口号码

window.location.protocol　//设置或获取 URL 的协议部分

window.location.hash　//设置或获取 href 属性中在井号“#”后面的分段

window.location.host　//设置或获取 location 或 URL 的 hostname 和 port 号码

window.location.hostname　//设置或获取 location 或 URL 的 hostname 和 port 号码

window.location.search　//设置或获取 href 属性中跟在问号后面的部分

window.location　//属性 描述 hash 设置或获取 href 属性中在井号“#”后面的分段javascript判断字符串中是否包含某字符串




indexOf函数方法示例用法： 

例如：
```var url = window.location.href;
if(url.indexOf("link") >= 0 ) { //判断url地址中是否包含link字符串
  alert("包含link字符");
}```
