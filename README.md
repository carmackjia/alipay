node.js 实现支付宝 api
包括 `担保交易收款`，`即时到帐收款`，`双功能收款`，`网银支付`，`即时到账批量退款`，`支付宝确认发货`等

用法
```bash
npm install alipay
cd test
node app

请注意，这里要视环境而定，在Mad上，我的操作方法是直接到~目录下， npm install alipay_git_path 的

2.cd test
3.npm install 
4.node app
# http://localhost:3000
```

代码说明：
```
alipay_config.js # 设置参数
app.js 中 require('./alipay_config').alipay.route(app) # 设置了支付宝通知路由
alipaydemo.js    # 使用事件处理交易状态等

依赖：
```
