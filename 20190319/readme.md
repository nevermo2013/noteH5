# html标签补充
## 表单标签
> 关于表单标签的补充内容,包括单选/多选等

+ 单选
+ 多选
+ 文件
+ 多行文本
+ get/post提交方式

## iframe
> iframe画中画,用于实现在当前页面包含其他页面

+ frameborder
+ scrolling


## sublime安装插件
+ 安装 package control  
+ ctrl+~ 粘贴一下代码 回车

```
import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp  = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try           manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)

```

+ ctrl + shift + p

+ 等待  输入  markdown  ==> 搜索相关插件

+ markdown本地预览工具 http://markdownpad.com/