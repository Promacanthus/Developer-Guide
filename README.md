# JetBrains 开源证书支持

Golang-Guide 项目一直以来都是在 JetBrains 公司旗下的 GoLand 集成开发环境中进行开发，基于 free JetBrains Open Source license(s) 正版免费授权，在此表达我的谢意。

![images](data:image/jpeg;base64,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)
