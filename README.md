# Unlimited-2FA Authenticator  
一个小巧方便的2FA身份验证器  
_此软件适用于支持Python的PC端，而不是移动端_  
---
这个软件本来是自用的，后来才上传到Github上  

此软件同市面上的所有的2FA身份验证软件一样，可以使用捕捉二维码（由于是PC端软件，所以是捕捉屏幕上的二维码来扫描）或手动输入账号以及验证码来绑定  
---
目前已经测试过使用此软件可以用于验证Github  
---
软件的使用  
---
第一步：  
打开软件后，软件会提示你选择一个储存地点，请选择一个安全的位置存放密钥（由于作者不会加密算法，所以密钥和账户是直接以文本的形式保存在2FA_data.json文件里的，以后我可能会加上加密处理），如果软件发现文件消失了，就会在同一个地方再生成一个存储文件，如果需要更改存储位置，请重新安装本软件  
  
第二步：  
你下载了这个软件，就代表你要验证一个软件，对吧？在选择完存储位置后，你就可以开始验证软件了。你有两种方案来验证，第一种是扫描屏幕上的二维码绑定，第二种是输入账号以及验证码来绑定。请你放心，本软件不需要联网（在第一次捕捉二维码绑定时需要联网分析二维码，这是不可避免的），也不会上传你的任何数据。如果你还是不放心，那你可以使用“手动添加”功能来绑定  

首先，我们先来使用“屏幕扫码”功能来绑定验证，点击“屏幕扫码”后，在键盘上按下“F9”按键，即可自动绑定（请确保二维码的窗口可以直接在屏幕上看到）。  

如果你发现捕捉二维码功能无法正常使用或你不放心使用，那么你可以使用“手动添加”功能。点击“手动添加”按钮后，会弹出一个“输入账号名称”窗口（窗口有时会被挡住，需要找一下），输入账号名称后，会弹出“输入2FA密钥”窗口，此时需要输入你需要验证的软件给你的6位数纯数字，即可完成绑定  
