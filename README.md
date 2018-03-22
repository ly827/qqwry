程序名称：IP解析程序
程序功能：基于QQ的二进制数据库QQWry.Dat
程序作者：strongc
使用方法：
 
请将文件 QQWry.Dat 置于当前目录中
或者可以用修改
define('__QQWRY__' , dirname(__FILE__).".\QQWry.Dat");
语句自定义QQWry.Dat路径
 
#实例+++++++++++++++++++++++++++++++
$ip="202.201.48.1";
$QQWry=new QQWry;
$ifErr=$QQWry->QQWry($ip);
echo "$QQWry->Country$QQWry->Local";
