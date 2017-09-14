虚拟机
172.16.99.195  22322 rdadmin/password01!
172.16.99.189  22322 rdadmin/kaixin.long   

ssh远程登陆
ssh name@remoteserver -p 2222
sudo scp -p 22322 rdadmin@172.16.99.189:/home/rdadmin/bin/repo .

Artifactory：
http://172.16.99.196:8081

\\172.16.100.15\常用软件
-------------------------------------------------------------------
RAP地址
http://172.17.193.108/workspace/myWorkspace.do?projectId=1#256
账号:hongwei
Email:wei.hong@phicomm.com
密码:ilCG74@$

-------------------------------------------------------------------
签名命令
java -jar signapk.jar platform.x509.pem platform.pk8 PhicommAfterSales.apk out.apk
-------------------------------------------------------------------
*#88#8  工厂模式
*#06#  imei meid号查询
-------------------------------------------------------------------
账户管理 测试服务器数据库地址
114.141.173.17 4000  账号：root feixun*123
电子保卡测试服务器地址 SalesData数据库里面的user_info
114.141.173.27 10012 账号：feixun   Fx@123456
---------------------------------------------------------------------
WIFI密码
phicomm_test1  密码：feixun*8469
---------------------------------------------------------------------
log打印
$ adb shell ps | grep phicare
u0_a108   20364 380   945540 87392 SyS_epoll_ 00000000 S com.phicomm.phicare
$ adb logcat | grep 20364
08-22 18:26:44.112  2521  4597 I ActivityManager: Start proc 20364:com.phicomm.phicare/u0a108 for activity com.phicomm.phicare/.ui.me.SplashActivity
---------------------------------------------------------------------
MeLauncher apk获取路径：\\172.16.100.15\Mobile_RD\ver_release\android\MeLauncher\Release
-------------------------------------------------------------------
apk安装过程分析
http://blog.csdn.net/mnorst/article/details/38727799

classloader分析
----------------------------------------------------------------
import static dagger.internal.Preconditions.checkNotNull;

----------------------------------------------------------------------------
git clone -b master-no-emc gerrit:viroyal-elec/c1330
C1330的代码拉取方式
-----------------------------------------------------------------------------
利用干货集中营数据，gank   http://gank.io/api
UI
侧边栏
上下滑动收缩
下拉刷新，上拉加载

框架
dagger
mvp + retrofit

XLog 看看

分享
自定义注解

切换主题背景


-----------------------------------------------------------------------------


http://blog.csdn.net/android_hl/article/details/70455018

https://ws1.sinaimg.cn/large/610dc034ly1fiz4ar9pq8j20u010xtbk.jpg
