# w_2111
哈希值竞猜源码纯合约的返奖源码
<br/></br>
[下载地址](https://www.uuid2.com/2111.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>转账功能<p>
<p>#!/bin/bash
PATH=/bin:/sbin:/usr/bin:/usr/local/bin:/usr/sbin
step=5 #间隔的秒数，不能大于10
for (( i = 0; i < 60; i=(i+step) )); do
curl http://xxx/index/wpay/auto_transfer3
curl http://xxx/index/wpay/auto_transfer2
curl http://xxx/index/wpay/auto_transfer1
sleep $step
done
exit 0<p>
<p>监听收款
#!/bin/bash
PATH=/bin:/sbin:/usr/bin:/usr/local/bin:/usr/sbin
step=3 #间隔的秒数，不能大于10
for (( i = 0; i < 60; i=(i+step) )); do
curl http://xxx/index/wpay/index3
curl http://xxx/index/wpay/index2
curl http://xxx/index/wpay/index1
sleep $step
done
exit 0<p>
<p>xxx改成你的域名
玩法有
index3 单双<p>
<p>index2 尾数<p>
<p>index1 牛牛<p>
<p>返奖私钥和监听充值地址修改/application/index/controller/wxpay.php
返奖地址和私钥在25和26行配置
监听充值玩法地址在200行以后配置，具体在哪里你们自己找吧，都在wxpay.php这个文件<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202205/adf4e1e963.png" alt="哈希值竞猜源码纯合约的返奖源码">
