# OnlyFansOne Website Codex Handoff Prompt

请根据当前源码继续维护一个 OnlyFansOne 静态网站。

## 目标

OnlyFansOne 是一个面向创作者、品牌和营销团队的社媒增长与内容曝光服务平台。网站文案以英文为主，同时支持切换中文展示。

## 技术要求

- 使用纯 HTML、CSS、JavaScript。
- 不需要后端。
- 保留前端演示流程，不接入真实付款或真实登录系统。
- 保留多页面路由体验：首页、关于我们、访客下单、会员服务、FAQ、联系、登录、注册、忘记密码、隐私政策、使用条款。
- 保留访客下单流程：平台选择、服务选择、目标数量、订单信息、完成状态。
- 保留响应式布局。

## 文案方向

- 默认英文展示，中文通过导航栏语言按钮切换。
- 避免使用“刷粉 / 刷赞 / 刷评论”等高风险表达。
- 使用更适合公开展示、广告审核、支付合规和用户信任的表达：
  - social growth
  - content visibility
  - audience growth
  - engagement support
  - campaign kickstart
  - cold start / early momentum

## 当前品牌

- Brand: OnlyFansOne
- SEO title: OnlyFansOne | Social Media Growth & Content Visibility Platform
- 中文 SEO title: OnlyFansOne | 社媒增长与内容曝光服务平台

## 文件说明

- `index.html`: 根目录单文件版本。
- `FanFlow-share.html`: 可分享的单文件版本，内容已同步为 OnlyFansOne。
- `fanflow-site/index.html`: 拆分版入口。
- `fanflow-site/styles.css`: 共享样式。
- `fanflow-site/app.js`: 双语文案、页面渲染和交互逻辑。
- 各路由目录中的 `index.html`: 多页面静态路由壳。

## 注意

OnlyFansOne 与 OnlyFans 名称高度相似，正式上线前建议确认商标、支付渠道和广告平台审核风险。如需降低风险，可考虑改名为 FansOne、SocialOne 或 FansBoostOne。
