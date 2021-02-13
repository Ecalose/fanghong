
使用教程：

1.上传插件整个文件夹到 /public 目录。得到：
/public/WxqqJump

2.修改 /public/index.php 文件。在第一行 <?php 下新增一行：
require_once('WxqqJump/WxqqJump.php');


当不再使用或者需要临时关闭跳转时，只需//注销该行代码即可。


