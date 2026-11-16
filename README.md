# 塔塔 AI 用户端 1.1.1

本版基于1.1.0，改为暖米色、陶土橙、居中问候与输入卡片的Claude启动页风格。
启动页与首页使用Claude官网Logo，塔塔品牌名称保留。Logo随应用本地打包，不依赖运行时联网加载。

Logo来源：https://claude.com/static/product-overview/claude-logo-lockup.svg
参考页面：https://claude.com/product/overview

Windows x64便携版：artifacts/TataAI-Client-1.1.1-win-x64.exe
旧版源码和EXE保留，SHA256核验一致；本版继续沿用原本地账号数据，不建议新旧版同时运行。

交互逻辑沿用1.1.0，仅调整界面布局、配色、品牌图形、展示文字与窗口底色。
验证：浏览器模拟回归（.ui-test/verify-claude-client.cjs）、1040px与680px截图检查、打包文件一致性检查。
没有使用真实账号激活/充值，没有修改线上配置；未签名。