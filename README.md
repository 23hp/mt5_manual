# MT5 傻瓜式信号订阅说明书

### 如何订阅信号
信号是MT5帮助你躺赚的的一个功能， 可以直接在你的帐户里自动跟随专业操盘手，拷贝交易操作。

#### 前置条件：
- 专属交易账号一个，里面不能有单子，跟单专用，切勿自行下单。
- windows电脑一台，需要安装[MT5](https://download.mql5.com/cdn/web/international.capital.markets/mt5/icmarkets5setup.exe)和[chrome浏览器](https://www.google.cn/intl/zh-CN/chrome/)

![软件](/image/software.png)
- 至少$45等值RMB，用于订阅信号和购买服务器进行挂机交易

软件可以直接点击链接下载安装，缺少电脑请看文末。不满足以上条件可能无法操作成功。

### 操作详解
如何开通这个功能呢？首先，我们要申请一个MT交易者论坛账号，充钱买下信号，然后找到一台服务器，登录你的交易账号，配置并且使用这个信号。

1. 在Windows电脑上打开MT5，登录好你的交易账号。

2. 注册[MT交易者论坛](https://www.mql5.com/zh/auth_register)账号

假如你是第一次操作，你需要在下方链接注册一个账号，用于购买信号。

https://www.mql5.com/zh/auth_register

3. 往账号中充值

登录后，在页面右上角`菜单`中找到`存款到账户`，点击去充值，支持银联visa支付宝。
信号$30/月，用户挂机的VPS约$15/月，按需充值。

![软件](/image/deposit.png)

4. 购买信号

本操作需要在[chrome浏览器](https://www.google.cn/intl/zh-CN/chrome/)中进行，并且确保这台电脑安装了[MT5](https://download.mql5.com/cdn/web/international.capital.markets/mt5/icmarkets5setup.exe)，不然会失败。

以我崇拜的一名擅长黄金澳纽的交易员为例，
- 点开他发布的[信号](https://www.mql5.com/zh/signals/676830)
- 点击页面上`复制为30 USD`绿色按钮进行购买，在弹出的对话框中点击`启动MetaTrader 5 并在平台中订阅`按钮，在新弹出的对话框点打开

![软件](/image/subscibe.png)
- MT5就会弹出对话框，要求你注册，点击`如果您有账户，请登录`，把第2步申请的账号输入进去，点击`确定`，MT5底下就会弹出这个信号的付款页。
![登录](/image/signin.png)

- 因为我们刚刚充值过了，所以选择`MQL5`。

![支付](/image/pay.png)
- 等待付款成功，信号配置的对话框会弹出来。

5. 配置信号

按图示配置信号，配置完成后点击确定。

![配置](/image/config.png)


现在你的账号已经能够自动跟随操盘手的操作了。

面板中参数的解释请参考：[如何订阅信号](https://www.metatrader5.com/zh/terminal/help/signals/signal_subscriber)

例如：发现每次跟单的手数太小，可以在MT5顶部菜单栏选择`工具`->`设定`->找到`信号`面板，修改`使用不超过__%入金`的大小。 

软件需要一直保持开启，否则会因为关机导致自动跟单停止。要保持账号自动交易，我们就需要一台机器长期开着，运行这个软件，我们需要购买一台服务器（VPS）。

6. 挂机跟单

好在MT官方想得周到，为我们提供了挂机的服务。点击软件下方的VPS面板，购买MT提供的服务器进行挂机，选择适合你的付款方式支付。

![VPS](/image/vps.png)

选择全部迁移

![设置](/image/vps_setting.png)

7. 成功

当你的账号下出现如下两行，说明你已经完成所有操作步骤，可以关机了。

![成功](/image/done.png)

### F&Q 常见问题
#### 如何调整跟单大小？
增加或者减少你的本金，新增的跟单会根据你的本金大小重新调整。你也可以修改信号设置的`使用不超过__%入金`来有限地调整使用本金的相对大小。当你的本金没有信号仓多时，你跟单的仓重是不会超过信号仓的。具体的跟单原理请阅读：[如何订阅信号](https://www.metatrader5.com/zh/terminal/help/signals/signal_subscriber)
#### 为什么不跟单不生效/出错/自动平仓？
在工具->设定中打开信号设置，再重复步骤5和6即可。另外，确保你没有在这个仓自己下单，减少每次出金占总资金的比例，因为这些操作会导致本金减少，导致仓位比例高于信号仓而被动平仓。
#### 跟单效果不错，我如何续费？
在MT5软件底下的VPS面板，选择你要续费的方案和支付方式付款即可。

### 相关链接

- [信号是如何运作的](https://www.mql5.com/zh/articles/618)
- [如何订阅信号](https://www.metatrader5.com/zh/terminal/help/signals/signal_subscriber)
- [利润计算器](https://www.forextimechina.com.cn/zh/trading-tools/trading-calculator/profit-calculator)

