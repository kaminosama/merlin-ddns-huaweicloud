# merlin-ddns-huaweicloud

梅林固件自定义ddns脚本分享

添加华为云相关参数后贴进/jffs/scripts并赋予执行权限即可

参数说明：
hostname=""          # 域名
zone_id=""           # 域名所在区域id，可以从华为云控制台对应域名解析记录集列表页面的url中找到
record_id=""         # 记录集id，在记录集列表页面选择你要解析的记录点一下保存可以在浏览器控制台找到
endpoint=""          # 域名所在区域，可在API Explorer中随便一个调试中取得
huawei_domain=""     # 账户名，可在“我的凭据”页面找到
name=""              # iam账户名，可在“我的凭据”页面找到
password=""          # 你的iam账户密码，可在脑子里找到
