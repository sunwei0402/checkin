# Checkin

GitHub Actions 实现 [GLaDOS][reg] 自动签到

([GLaDOS][reg]注册可用邀请码: `M8543-E4N37-Z0JZY-BHTS0`, 双方都有奖励天数)

## 使用说明

1. Fork 这个仓库

1. 登录 [GLaDOS][glados] 获取 Cookie

1. 添加 Cookie 到 Secret `GLADOS`

1. 启用 Actions, 每天北京时间 00:10 自动签到

1. 如需推送通知, 可用 [PushPlus][pushplus], 添加 Token 到 Secret `NOTIFY`

[glados]: https://github.com/glados-network/GLaDOS
[pushplus]: https://www.pushplus.plus/
[reg]:https://glados.space/landing/M8543-E4N37-Z0JZY-BHTS0
