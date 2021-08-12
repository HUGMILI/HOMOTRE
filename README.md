## 系统简介

1. 同态加密匿名投票demo系统，模拟投票、计票、公示三方分立。

2. 投票采用公钥加密，公示方拥有私钥。

3. 投票方将加密后票送到计票方，计票方利用同态特性进行计算，得到汇总的结果；公示方拿到该结果后解密之，即得总票数。

4. 公示方不知道单独每张票的情况，从而实现了匿名；计票方计算过程解不出投票记录，于是可以防止从中作假。

## 在线体验

演示地址：http://106.12.187.249:8080

## 演示图

<table>
    <tr>
        <td><img src="https://taiji-vote.oss-cn-beijing.aliyuncs.com/1.png?versionId=CAEQEBiBgMDHv76ivRciIGZlNjAyZmIwODE3NzQzNTVhMzgxZjIxZGU0ZjkzZjMw"/></td>
        <td><img src="https://taiji-vote.oss-cn-beijing.aliyuncs.com/2.PNG?versionId=CAEQEBiBgICGmL2ivRciIGFkYmFhMjJkZDNkZDRiZTU5MWM2MjkxZTJkNWIwYTk1"/></td>
    </tr>
    <tr>
        <td><img src="https://taiji-vote.oss-cn-beijing.aliyuncs.com/3.PNG?versionId=CAEQEBiBgIC797yivRciIGE0ZGQzNzg1N2E4NjQ2ZWQ5YjQxYTVmMzFkNTliMTJj"/></td>
        <td><img src="https://taiji-vote.oss-cn-beijing.aliyuncs.com/4.PNG?versionId=CAEQEBiBgMDY0ryivRciIDU5ZDU4ZDU4ZWRlZDRlYWJhODY0MzU4MTdhMGI3N2Ix"/></td>
    </tr>
</table>

## 注意

1. DEMO使用的应用框架和同态加密算法均来自网络，保留了原文的版权声明，不能直接商业使用，请注意！
2. 项目源代码中删除了数据库连接信息和数据库建表语句，仅提供源代码供大家参考。
