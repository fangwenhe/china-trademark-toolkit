# 发布与冷启动操作单（LAUNCH CHECKLIST · 中文，给自己看）

> 目标：把 `china-trademark-toolkit` 仓库发布后，尽快被 Google / Bing / AI 搜索收录，并完成第一次主动分发，跑通"建仓 → 收录 → 分发 → 询盘"闭环。每开一个新仓库都照这个清单走一遍。

## 一、建账号与仓库（约 30 分钟）
1. [ ] 注册 GitHub 账号，建议新建一个 **Organization（组织）**，名字用品牌英文（如 `huaqing-ip`），头像/简介写清 "CNIPA-recorded China trademark agency"。
2. [ ] New repository，名称带关键词：`china-trademark-toolkit`；**Public**；勾选 Add README（用本文件覆盖）。
3. [ ] 上传全部文件夹：`guides/ datasets/ templates/ tools/ LICENSE CODE_OF_CONDUCT.md README.md`。
4. [ ] 仓库 **About（齿轮设置）**：Description 直接用 README 首句含关键词；Website 填你的落地页；**Topics 打满 20 个**（清单见 README 末尾）。
5. [ ] 把仓库 **Pin（置顶）** 到组织主页；组织 Profile README 写一句话介绍并链接到本仓库。
6. [x] 占位符已替换：机构名 Huaqing Innovation (Huaqing IP)、邮箱 hello@huaqingip.com、过渡官网与预约走 GitHub Pages（https://fangwenhe.github.io）；待注册 huaqingip.com 后在 Pages 绑定自定义域名并把链接平滑切换。

## 二、开启 GitHub Pages（做承接/演示站）
1. [ ] Settings → Pages → Source 选 `main` 分支 /(root) 保存。
2. [ ] 得到 `https://组织名.github.io/china-trademark-toolkit/`，把 `tools/trademark-risk-self-check.html` 作为可在线打开的 demo 链接放进 README（"▶️ Live self-check"）。
3. [ ] （可选但推荐）绑定自有域名并开 Enforce HTTPS，品牌资产沉淀在自己手里。

## 三、主动提交收录（关键，能把收录从 3-4 周压到 24-72 小时）
1. [ ] **Google Search Console**：添加资源（先用 github.io 这个 Pages 站验证，HTML meta 标签方式最省事）→ 提交 sitemap/网址 → 对仓库主页、Pages 站、三篇 guide 分别"请求编入索引"。
2. [ ] **Bing Webmaster Tools**：同样添加并提交 URL（DuckDuckGo、Yahoo 共用 Bing 索引，一次覆盖三家）。
3. [ ] 在 Pages 站放一个简单 `sitemap.xml`（静态列出主要页面）。
4. [ ] 一周后回 Search Console 看"网页索引"和查询词，确认 `china trademark / register trademark in china / first-to-file` 有没有曝光。

## 四、第一次主动分发（冷启动流量主要靠这步，不是靠等 Google）
按目标客户出现的地方发，**每个平台措辞改成该平台口吻，不要群发同一段**：
1. [ ] **Reddit**：r/ChinaBusiness、r/Entrepreneur、r/FulfillmentByAmazon、r/EtsySellers、r/legaladvice（注意先看版规，以"我整理了一份免费中国商标避坑资料"的分享姿态，不硬广，转化链接放个人主页）。
2. [ ] **Hacker News**：有了几个 star 后发 Show HN，标题如 `Show HN: An open toolkit for registering and protecting trademarks in China`，挑美东工作日上午发。
3. [ ] **LinkedIn**：发一篇英文短帖（first-to-file 抢注真实教训 + 免费 toolkit 链接），并私信你的目标海外 IP 律师/事务所。
4. [ ] **dev.to / Medium**：把 Guide 01 改写成一篇文章，文末链回仓库（高权重反链，利于 SEO）。
5. [ ] **投目录**：Awesome Self-Hosted/相关 awesome-list、OpenAlternative、Product Hunt（有可运行 demo 后再上）。
6. [ ] 给海外律师的开发信里直接附本仓库链接——**开源资料本身就是最强的专业背书和破冰物**。

## 五、转化埋点（别只要 star，要线索）
1. [ ] README、每篇 guide 底部、self-check 结果页都放同一个转化入口（落地页/邮箱/预约）。
2. [ ] 落地页区分两类：直客（retail 报价）与海外律师（foreign-associate 批发 rate schedule）。
3. [ ] 用一个邮箱/表单收集询盘，并标注来源（哪个仓库/哪篇 guide）。

## 六、每周复盘（GitHub 自带数据，不用装东西）
1. [ ] 仓库 → Insights → **Traffic**：看近 14 天 Views/Uniques、**Referring sites（Google、Reddit、HN 各带多少）**、Popular content。
2. [ ] 看 Star 增长与 Issues（有人提 issue 就是强需求信号，认真回）。
3. [ ] 哪篇 guide/哪个词带来流量，就围绕它再补内容，形成长尾。

## 七、复制到下一个中国服务（验证闭环跑通后再批量）
同一套骨架改主题即可：`china-company-registration-toolkit`、`china-copyright-registration-toolkit`、`china-icp-filing-toolkit`、`tmall-global-entry-toolkit`……每个都走第一到第六步，并在组织 Profile 与 Pages 总站互相内链，把权重和线索收口到一处。

> 预期节奏（管理预期）：0-2 周主要靠站内搜索+这次主动分发起量；1-3 月 Google/Bing 长尾稳定带量、AI 搜索开始引用；3-6 月多仓库内链+SEO 复利。先把这一个做出真实 Traffic 数据，再批量复制。
