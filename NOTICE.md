# 图标来源与权利说明

## 原始资源

| 来源 | 文件或系列 | 保存与处理 |
| --- | --- | --- |
| 用户提供的插画，经内置 image_gen 编辑 | Final-Clownfish-HD.png、Final-Clownfish-QX.png | 按用户确认的版本处理水印和透明背景；高清版保留 1254px 编辑结果，QX 版从该图缩小至 144px。原插画权利归相应权利人，本仓库不另行声明其许可。 |
| 内置 image_gen 图像生成工具 | Global-Skeuomorphic-HD.png、Global-Skeuomorphic-QX.png | 自定义拟物地球，真实透明背景；由生成原图分别缩小为 1024px 与 144px；提示词、原图校验值记录在 sources.json。 |
| [Koolson/Qure](https://github.com/Koolson/Qure) | Steam、国家/地区、常用服务、代理、直连、断开等 PNG | 固定来源提交 `b16b260625f873266f6a6a9b88710132774997b8`，目录 `IconSet/Color`，原样保存。 |
| [Anthropic 官网](https://www.anthropic.com/) | Anthropic.png | 公开 Apple Touch Icon，原样保存。 |
| [Anthropic 官方媒体包](https://anthropic.com/press-kit) / [Newsroom](https://www.anthropic.com/news) | Anthropic-Symbol-Slate.svg、Claude-Spark-Clay-Original.svg、Claude-Spark-Clay-Original.png | 官方媒体包中的 SVG、PNG 原文件，内容原样保存。 |
| Google 官方 gstatic.com | Google-G.png | 原始品牌 PNG，地址详见 sources.json。 |
| [Google Partner Marketing Hub](https://partnermarketinghub.withgoogle.com/brands/google/branding-guidelines/how-to-show-googles-brand/) | Google-G-Original.png | 官方公开下载的 GoogleG_FullColor_RGB.png，2820 × 2820，原始透明留白与文件内容保留。 |
| [TradingView 官网](https://www.tradingview.com/) | TradingView.png | 官网公开的 180 × 180 Apple Touch Icon，原样保存。 |
| [Battle.net 官方下载页](https://download.battle.net/en-us/desktop) | BattleNet.png | 官方页面声明的 196 × 196 PNG 站点图标，原样保存。 |
| [Binance 官方 iOS 应用](https://apps.apple.com/hk/app/id1436799971) | Binance-Rounded-HD.png 的原始图像 | Apple 图片 CDN 的 1024px PNG；应用发行方为 Binance Switzerland AG。 |
| [Microsoft Learn](https://learn.microsoft.com/en-us/entra/identity-platform/howto-add-branding-in-apps) | Microsoft-Symbol.svg | 官方下载的四彩标志 SVG，原样保存。 |
| [Speedtest by Ookla 官方 iOS 应用](https://apps.apple.com/us/app/speedtest-by-ookla/id300704847) | Speedtest-HD.png | Apple 图片 CDN 的 1024px PNG 原样保存；发行方为 Ookla。 |
| [Muse from Meta 官方 iOS 应用](https://apps.apple.com/us/app/muse-from-meta/id6760173601) | Muse-HD.png | Apple 图片 CDN 的官方 1024 × 1024 PNG 原样保存；发行方为 Meta Platforms, Inc.。 |
| [Meta 官方品牌资源](https://www.meta.com/brand/resources/meta/company-brand/) | Meta-Original.svg | 官方公司标志包中的正色 SVG，原样保存；归档文件路径和校验值记录在 sources.json。 |
| [Instagram 官方品牌资源](https://www.meta.com/brand/resources/instagram/instagram-brand/) | Instagram-Original.png | 官方 Gradient Glyph 透明 PNG，5000 × 5000，原样保存。 |
| [Muse 官网](https://muse.ai) | Muse-Transparent-Original.svg | 官网公开的蓝色渐变标志，原生透明背景；与原有白底 App Store 图标并列保留。 |

## 规格转换与自定义排版

| 文件或系列 | 处理 |
| --- | --- |
| Muse-QX.png | 从 Muse-HD.png 官方高清原图缩小至 144 × 144、8-bit RGBA、非交错 PNG；保留原图案、配色和背景。 |
| Meta-Symbol.svg、Meta-HD.png、Meta-QX.png | 从官方原件提取已有 Symbol 和所需定义；不修改图案与配色，仅置于透明正方形画布，分别导出 1024px 与 144px。 |
| Instagram-HD.png、Instagram-QX.png | 从官方 5000px 透明 PNG 分别缩小到 1024px 与 144px，增加透明留白；不放大小图、不重绘原图。 |
| Muse-Transparent-HD.png、Muse-Transparent-QX.png | 分别从官网 SVG 直接导出 1024px 与 144px，增加透明留白；原标志与渐变配色保持。 |
| Anthropic-QX.png、TradingView-QX.png、BattleNet-QX.png、Speedtest-QX.png | 对应原始品牌 PNG 缩小至 144 × 144、8-bit RGBA，重新编码并移除元数据。 |
| Google-G-HD.png、Google-G-QX.png | 沿用官方原图图案与配色，仅去掉多余透明留白，再独立导出 1024px 与 144px；未放大 96px 旧图，现有经典彩色 G 文件保留。 |
| Microsoft-HD.png、Microsoft-QX.png | 从原始官方 SVG 分别渲染 1024 × 1024 和 144 × 144；图案比例和配色保留，PNG 透明背景。 |
| Claude-Spark-Clay-HD.png、Claude-Spark-Clay-QX.png | 分别从官方 Claude Spark - Clay SVG 直接导出 2048px 与 144px；图形与配色保持原样，8-bit RGBA 透明 PNG；官方 SVG 和 937px PNG 原图单独保留。 |
| Anthropic-Tan.svg、Anthropic-Tan-HD.png、Anthropic-Tan-QX.png | 官方标志路径配 #D4A27F 暖棕圆角底，两套 PNG 分别从 SVG 渲染；暖棕底为自定义排版配色。 |
| Speedtest-Rounded-HD.png、Speedtest-Rounded-QX.png | 对官方原始 1024px App Store 图像添加透明圆角，弧度与币安版一致；图案保留，两套均由含原图的 SVG 独立渲染，原版 PNG 继续保留。 |
| Binance-Rounded-HD.png | 从原始 1024px App Store 资源为外部黑色背景添加透明圆角，未放大 QX 小图。 |
| Binance-Rounded-QX.png | 保留已发布的 144px 圆角版本。旧尖角文件已从当前版本移除，历史来源提交和 SHA-256 留在 sources.json。 |

## 权利与逐文件记录

| 项目 | 说明 |
| --- | --- |
| Qure 出处 | 上游 [README](https://github.com/Koolson/Qure/blob/b16b260625f873266f6a6a9b88710132774997b8/README.md) 要求转载注明出处，并用于非商业分享、学习交流。 |
| 品牌权利 | 图像和商标的权利归相应权利人，本仓库不重新声明这些资源的许可或品牌背书。 |
| 技术记录 | [sources.json](sources.json) 保存逐文件来源、转换说明、实际尺寸、大小及 SHA-256。 |
