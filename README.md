# bicycleSharingServer
JavaWEB后台

"划船不用桨"团队   wofi单车后台
# 已部署到阿里云服务器

[后台访问地址(有效期至2018/2)](http://59.110.238.9:8080/bicycleSharingServer_war/)

用户名密码:admin 高管验证:huija

[安卓端下载地址](http://59.110.229.53/download/wofi.apk)

想要附近有车,先安卓端注册,在网页端输入:

http://59.110.238.9:8080/bicycleSharingServer_war/api-borrow-borrowBicycle/车编号/手机号

重启下安卓端就会有当前行程了,还的话是还在当前位置.

如果无法访问页面,请邮件zhj3212j@outlook.com开启,有时服务器会异常关闭

# 关于后台未解决的问题

首页由于添加地图组件的原因,修改了框架css,现在主页的侧边栏无法收起(其他页正常),PC端无任何影响,手机端浏览会有出现侧边栏盖住主页内容的情况,并无大碍.
  
# 关于exe文件
是直接双击同步项目到github的小程序,中间要按几次回车.缺点:commit统一备注为"小改动",大的改动请自行敲命令行.

请原谅一个这么懒的人,懒得写readme,懒得去敲命令行.

# 初学者的建议
我的Test里面是ssm的demo,而且还用的是maven管理的,可以先去看下那个,顺路可以学下maven