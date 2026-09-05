# Awesome GPT-6 Astra

[English](README.en.md) · 中文默认

精选、可署名、可点回原帖的 GPT-6 Astra 案例馆。这是编辑过的导览，不是全集，也不是 OpenAI 官方仓库。

GPT-6 Astra 于 2026-09-03 发布，9 月 4–5 日向 Plus / Pro / 企业用户铺开。X 上这两天真正炸开的不是跑分，而是人把电脑交给模型之后做出来的东西。

**先看这 5 条：** Anshu 45 分钟游戏 · Tom Krcha 代码火车 · Peter Gostev 梵高小镇 · Pietro 3D iPod · 歸藏甜甜圈

## Contents

- [Featured 16](#featured-16)
- [分类目录](#分类目录)
- [可复用套路](#可复用套路)
- [已知局限](#已知局限)
- [投稿与许可](#投稿与许可)

## Featured 16

### 01. Anshu — 45 分钟 one-shot 3D 游戏

- **作者：** Anshu（[@anshuc](https://x.com/anshuc)）
- **原帖：** https://x.com/anshuc/status/2096008083826725132
- **日期：** 2026-09-04
- **工具：** Codex · Blender MCP · 图像生成对标
- **试玩：** 仅视频；作者答应后续会放

约 45 分钟做出可玩 3D 原型。方法不是空口喊「做个好看的游戏」，而是先用图像模型出概念图，再让 Astra 截游戏画面对标，直到接近概念图并锁 60fps。资产由模型自建。

**为何收录：** 上线首日传播最广的方法帖。**边界：** 作者自述配额消耗很低；玩法仍在做。

### 02. Tom Krcha — 运行时生成的活火车

- **作者：** Tom Krcha（[@tomkrcha](https://x.com/tomkrcha)）
- **原帖：** https://x.com/tomkrcha/status/2096082580554777041
- **日期：** 2026-09-05
- **工具：** TypeScript · Three.js
- **试玩：** 仅视频

两列火车没有 `.glb` / `.obj`，全部由几何函数在运行时生成。轮子运动、爆炸拆解、重组动画都是代码驱动。同作者还有房子照片 → 完整 Blender 场景，以及蒸汽火车草图 → 3295 个可编辑物体。

**为何收录：** 这是 3D engineering，不是点鼠标建模。**边界：** 拓扑未必适合直接生产。

### 03. Peter Gostev — 梵高小镇与 Gogh Strike

- **作者：** Peter Gostev（[@petergostev](https://x.com/petergostev)）
- **原帖：** [小镇](https://x.com/petergostev/status/2095776685807346105) · [FPS](https://x.com/petergostev/status/2096013280519016608)
- **日期：** 2026-09-04 / 2026-09-05
- **工具：** Three.js · Blender · Sites
- **试玩：** https://van-goghs-town.surge.sh/ · https://gogh-strike.surge.sh/

先把《星夜》《卧室》《夜间咖啡馆》等 6 幅梵高画合成可漫游的 Three.js 小镇；接着用 Ultra 跑约 6 小时，把同一套美术做成后印象派 5v5 射击。

**为何收录：** 少有可直接打开玩的创意案例。**边界：** 作者自托 demo，未做多人联机验收。

### 04. Pietro Schirano — 15 分钟 3D iPod

- **作者：** Pietro Schirano（[@skirano](https://x.com/skirano)）
- **原帖：** https://x.com/skirano/status/2095648379455861054
- **日期：** 2026-09-04
- **工具：** Codex · Blender · Mac App
- **试玩：** 仅视频

一句话：用 Blender 做 3D iPod，用原版 iPod 交互浏览 Codex threads。约 15 分钟。同作者还做了单图生成 3D 动画、视频转可交互代码、地图钉重建街区、Ableton MCP 从零做一轨。

**为何收录：** 官方博客署名作者之一，覆盖面最完整。**边界：** 部分时长为作者自述。

### 05. Matthew Berman — Fall Guys 到 5 天 SimCity

- **作者：** Matthew Berman（[@MatthewBerman](https://x.com/MatthewBerman)）
- **原帖：** https://x.com/MatthewBerman/status/2095595892464333065
- **日期：** 2026-09-03
- **工具：** `/goal` · browser control · Sites
- **试玩：** https://signals.forwardfuture.com/astra-review/

早期体验最完整的长线程之一：两条 prompt 的 Fall Guys、3D biome、liminal horror、京都步行导览，以及 `/goal` 跑了 5 天还没做完的 SimCity。

**为何收录：** 同时展示「能玩」和「能跑多日」。**边界：** SimCity 在发布演示时尚未完成。

### 06. 歸藏 — 10 分钟 Blender 甜甜圈

- **作者：** 歸藏（[@op7418](https://x.com/op7418)）
- **原帖：** https://x.com/op7418/status/2096065904828416286
- **日期：** 2026-09-05
- **工具：** Codex · Blender MCP · bpy
- **试玩：** 仅视频

新手课通常 1–2 小时的精细甜甜圈，约 10 分钟出工程文件，还能继续加糖霜和运镜。作者对比：同类视频模型一次几十块，这里交出的是可改的工程文件。

**为何收录：** 中文圈最实在的成本账。**边界：** 成本为作者估算。

### 07. Yunfan Ye — 房源图变 3D 房子

- **作者：** Yunfan Ye（[@realYunfanYe](https://x.com/realYunfanYe)）
- **原帖：** https://x.com/realYunfanYe/status/2095612137582526615
- **日期：** 2026-09-03
- **工具：** 3D reconstruction
- **试玩：** 仅视频

用 Zillow 房源图片生成 3D 房屋和宣传视频。

**为何收录：** 把真实世界照片推进可浏览空间。**边界：** 作者自认细节有误，也会幻觉出原房没有的部位。

### 08. Federico Viticci — Notes 里一笔一笔画自像

- **作者：** Federico Viticci（[@viticci](https://x.com/viticci)）
- **原帖：** https://x.com/viticci/status/2096025249582039180
- **日期：** 2026-09-04
- **工具：** Computer Use · Apple Notes · Mac
- **试玩：** 仅视频

给 Astra 一张自己的肖像照，它打开 Apple Notes，用鼠标一笔一笔勾出轮廓、五官和头发。

**为何收录：** 不是生成一张图，是在真实系统里动手。**边界：** 笔触草图，不是写实肖像。

### 09. Clad3815 — 只看屏幕通关《宝可梦火红》

- **作者：** Clad3815（[@Clad3815](https://x.com/Clad3815)）
- **原帖：** https://x.com/Clad3815/status/2095596013168050551
- **日期：** 2026-09-03
- **工具：** Computer Use · 截图循环

纯截图、不读内存、不给攻略。Astra 18 小时 12 分打完；GPT-5.6 Sol 用 96 小时 35 分；GPT-5.5 跑 218 小时未完成。

**为何收录：** Computer Use + 长程目标最硬的对照之一。**边界：** 时长为作者测试结果。

### 10. Derya Unutmaz — 11 分钟巴赫钢琴

- **作者：** Derya Unutmaz（[@DeryaTR_](https://x.com/DeryaTR_)）
- **原帖：** https://x.com/DeryaTR_/status/2096090915790069857
- **日期：** 2026-09-05
- **试玩：** https://brandenburg-piano.vercel.app/

做一架可弹虚拟钢琴，并把巴赫《勃兰登堡协奏曲》全部 6 首做进去，约 11 分钟。同作者还复刻了 40 年前的 Sinclair ZX Spectrum 48K。

**为何收录：** 少见的「做完就能用」音乐工具。**边界：** 网页钢琴，不是录音室质量。

### 11. Jay Chooi — 机械臂 40% → 95%

- **作者：** Jay Chooi（[@chooi_jeq](https://x.com/chooi_jeq)）
- **原帖：** https://x.com/chooi_jeq/status/2096064315115839904
- **日期：** 2026-09-05

真实机械臂抓取：Fable 5.1 约 40%，Astra 约 95%；输出 token 少 6.2 倍，成本低 2.3 倍，速度快 2.7 倍。

**为何收录：** 少数带硬指标的案例。**边界：** 作者单次对照，不是第三方基准。

### 12. Greg Isenberg — 9 条能上班的 Agent prompt

- **作者：** Greg Isenberg（[@gregisenberg](https://x.com/gregisenberg)）
- **原帖：** https://x.com/gregisenberg/status/2095854071580156338
- **日期：** 2026-09-04

账单谈判、把中介服务拆成软件、盯二手市场捡漏、一人公司看板、夜间真机 QA、竞品卧底。

**为何收录：** 比「做个小游戏」更接近普通人明天能试的用法。**边界：** 这是提示词清单，不是全部实跑报告。

### 13. paulwei — 语音打《杀戮尖塔 2》

- **作者：** paulwei（[@coolish](https://x.com/coolish)）
- **原帖：** https://x.com/coolish/status/2096195104809873710
- **日期：** 2026-09-05
- **工具：** Computer Use · 语音

没写复杂 prompt，语音让 Astra 打开游戏。模型自己去设置里学键位，打了 48 层，精英和 Boss 接近零伤。

**为何收录：** 今天中文圈最有温度的一条。**边界：** 单局体验。

### 14. AiBattle — Godot 索尼克，Max vs Medium

- **作者：** AiBattle（[@AiBattle_](https://x.com/AiBattle_)）
- **原帖：** https://x.com/AiBattle_/status/2095994051354919049
- **日期：** 2026-09-04

同一提示词：Max 53 分钟、吃 4% 周配额；Medium 25 分钟、吃 1%。Max 更完整，Medium 已经能通关。

**为何收录：** 最清楚的「推理强度 vs 成本」对照。**边界：** 配额百分比是作者订阅档自述。

### 15. OpenAI — KiCad PCB 与房子进 UE5

- **作者：** OpenAI（[@OpenAI](https://x.com/OpenAI)）
- **原链：** https://openai.com/index/gpt-6-astra/
- **日期：** 2026-09-03
- **工具：** KiCad · Blender · Unreal Engine 5

官方演示里，Astra 用 KiCad 把电路原理图做成可生产 PCB；另一条是 Blender 建房再导入 UE5，客户可以走进去看。

**为何收录：** 官方自己选的专业软件示范。**边界：** 官方演示环境。

### 16. SKEL — 早餐时给布加迪发了两封邮件

- **作者：** SKEL（[@skel](https://x.com/skel)）
- **原帖：** https://x.com/skel/status/2096113092736540685
- **日期：** 2026-09-05
- **工具：** Astra · GPT Image · 已连接的 Gmail

早餐时用图像模型画布加迪 Mistral，后台已连 Gmail 的 Astra 主动给布加迪发了两封邮件。作者紧急断开授权。

**为何收录：** Computer Use 到这个能力后，权限就是真的权限。**边界：** 作者自述事件；本仓库未看到邮件原文。

## 分类目录

精选已计入各类。下面是目录补充，连精选一共约 32 条。

### 游戏与可玩原型

- 三岁小孩动力沙 / 卡车 / 恐龙 — [@imoutoftokensFR](https://x.com/imoutoftokensFR/status/2096202083561054342)
- Astral War 浏览器射击 — [@RealFedeURU](https://x.com/RealFedeURU/status/2096202133532008758)
- Three.js MMORPG 区域 — [@oceanbennett](https://x.com/oceanbennett/status/2096049972437209510)
- Fernando Galaxy 原生 iOS — [@RayFernando1337](https://x.com/RayFernando1337/status/2096150987031633961)
- 宝可梦风 3D / 涩谷 / 东京塔 — [@masahirochaen](https://x.com/masahirochaen/status/2096196861287878877)
- 可玩射击 + 赛车 — [@k2sbhai](https://x.com/k2sbhai/status/2096182794737402183)

### 3D 世界与建模

- 楔圆形办公室 — [@higgsfield_ai](https://x.com/higgsfield_ai/status/2095630197257367857)
- 一条 prompt 用基本体拼出整车 — [@Stefan_3D_AI](https://x.com/Stefan_3D_AI/status/2096185294165103049)
- Cinema 4D 也能建模 — [@mojon1](https://x.com/mojon1/status/2096189580752081024)
- 澳洲宿舍照片还原 — [@rionaifantasy](https://x.com/rionaifantasy/status/2096163579925770671)
- 零 Blender 经验做美式厨房 — [@berryxia](https://x.com/berryxia/status/2096158415894835518)
- GTA6 画风新加坡街道 — [@birdabo](https://x.com/birdabo/status/2096156461365960837)
- 火车草图 → 3295 部件 — [@tomkrcha](https://x.com/tomkrcha/status/2095756085890310311)

### Computer Use / 工程

- Paint 里画你 — [@The_Alex](https://x.com/The_Alex/status/2095962639386239400)
- 55 段素材自动剪辑 — [@0xTykoo](https://x.com/0xTykoo/status/2096183262255386833)
- 无人机飞控 PCB — [@GoGoFly23](https://x.com/GoGoFly23/status/2096145124950708512)
- UI 生成质量 — [@MSchwaibold](https://x.com/MSchwaibold/status/2096059496812716307)
- iOS 参考做安卓 — [@jonaswrks](https://x.com/jonaswrks/status/2096201967982829707)

### 科学 / 音乐 / Prompt

- ZX Spectrum 48K 复刻 — [@DeryaTR_](https://x.com/DeryaTR_/status/2096062355692048605)
- 个人风格 MIDI — [@super_bonochin](https://x.com/super_bonochin/status/2096183825433084181)
- 第一性原理盘问代码库 — [@georgepickett](https://x.com/georgepickett/status/2095979879137460640)

## 可复用套路

1. **先出图，再对标。** Anshu、歸藏、berryxia 都是 image gen 概念图 → Blender / Three.js 截图迭代。
2. **接 MCP，不要只聊天。** Blender MCP、Ableton MCP、电脑操控比把代码拷出来强一个数量级。
3. **Medium 往往够用。** 索尼克对照说明 Max 更精，Medium 已能出可玩版本。
4. **用 ChatGPT Sites 直接托管。** 梵高小镇、Gogh Strike、巴赫钢琴都是 prompt 到可分享链接。
5. **给它目标，不要逐步喂。** `/goal` 适合多日任务。
6. **权限最小化。** 能发邮件之后，默认连 Gmail 并不聪明。

## 已知局限

- Plus 配额很紧，一个稍复杂的 3D 任务就能打满 5 小时额度。
- 不是每条 one-shot 都能上线。车模、房源 3D、PCB 布线仍会出现工程级错误。
- 有人觉得 Fable 5.1 在纯视觉 / HTML 审美上仍更强。
- 高级网络安全能力对普通用户是关掉的。
- 本清单是导览，不保证你用同一提示词能复现同等效果。

## 投稿与许可

- 本仓库摘要文字：[CC0 1.0](LICENSE)
- 原作品版权仍归作者，详见 [NOTICE.md](NOTICE.md)
- 新案例请读 [CONTRIBUTING.md](CONTRIBUTING.md)
- 收录不等于背书可复现
- Not affiliated with OpenAI
