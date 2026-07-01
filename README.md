# 喵 · 桌面伙伴(Desktop Avatar · macOS)

[![downloads](https://img.shields.io/github/downloads/solaswing/avatar-releases/total?color=F2814A&label=%E4%B8%8B%E8%BD%BD%E6%80%BB%E6%95%B0)](https://github.com/solaswing/avatar-releases/releases/latest)
[![latest](https://img.shields.io/github/v/release/solaswing/avatar-releases?color=6FE0A8&label=%E6%9C%80%E6%96%B0%E7%89%88)](https://github.com/solaswing/avatar-releases/releases/latest)
![platform](https://img.shields.io/badge/platform-macOS%2014%2B%20·%20Apple%20Silicon-black?logo=apple)
![license](https://img.shields.io/badge/license-AGPL--3.0-blue)

> **社交软件把你接给别人,越刷越空;喵把世界接给你,越用越强。**

一只浮在 macOS 桌面上的 Live2D 伙伴 —— 有脸、会陪你、记得住你,还能连上你的 App 和网页帮你干活。没有 feed、没有关注、没有算法,只属于你一个人,默认全在本地。

本仓库是「喵」的**公开发布通道**,只托管两样东西:**安装包**([Releases](https://github.com/solaswing/avatar-releases/releases/latest))+ **更新清单**([`latest.json`](latest.json),App 内「检查更新」比对用)。源码仓库私有,不在此处。

🌐 **想先看看?** 落地页带一只会 idle 动的实时 Live2D 演示 → **<https://solaswing.github.io/avatar-releases/>**

---

## ⬇️ 下载 · 安装

1. 去 [**Releases**](https://github.com/solaswing/avatar-releases/releases/latest) 下最新的 `Miao-x.y.z.dmg`。
2. 打开 DMG,把里面的 App 拖进「**应用程序**」。
3. 从启动台 / 应用程序双击打开。第一次会有「**认识喵**」引导,配好聊天模型(「大脑」)就能用,其余以后在设置里慢慢解锁。

> ✅ 已 **Developer ID 签名 + Apple 公证**,干净 Mac 双击即用,**不会有 Gatekeeper「无法打开」警告**,也不用右键「打开」那套。

**要求:** macOS 14 (Sonoma) 或更新 · **Apple Silicon**(M1 及以后)。Intel Mac 也能装,但只能走云聊天,本地私密那套用不了。

---

## 它是什么(以及不是什么)

不是社交 App,不是 AI 女友,也不是冷冰冰的效率工具。喵是第一个把这四样,装进同一个、**只属于你**的桌面伙伴:

- **有人格 · 会陪你** —— 有张脸、记得你,不是用完即走的冷工具
- **连得上你的一切 · 能搭把手** —— 看得懂屏幕、读得了网页、接得上你的工具(MCP)
- **越用越懂你 · 越用越能干** —— 记住你的习惯、能装新工具,慢慢长成你的样子
- **只属于你 · 本地私密** —— 默认不上传、可离线、每一步你点头

> 自己干不了的重活(写代码、跑复杂自动化),喵不硬扛 —— 转交给 **Codex / Claude / Hermes** 这些更专业的"手",自己负责听懂你、盯着结果、留下来陪你。**它们是召之即来的手;喵是一直在的那张脸。**

> **操作能连多少步,主要看你配多强的"大脑"**:配强模型,常见操作(开 App、搜歌放歌、搜番点开、填表单)能稳稳连着跑、还**越用越熟**(每次成功攒一条操作配方);本地小模型短一些。真正复杂、通用操作够不着的,两条路:**委派专业 agent**(Codex / Claude / Hermes),或**给它定制专门工具 / MCP**(把复杂流程固化成一个工具,一句话调用)。

---

## ✨ 它能干啥

**这是数字人本体:**

| | |
|---|---|
| 🪟 **悬浮陪伴** | 透明窗口浮在桌面任意位置,角色轮廓内不穿透、外部空白处鼠标穿透;记住上次位置,登录自动启动 |
| 💬 **语音 / 文字对话** | 左键单击出气泡输入框;按住右 `⌥` 即说即转文字(push-to-talk);长回复可滚动 |
| 🧠 **多模型大脑** | 本地 MLX 离线模型 + 云端模型(ofox / Gemini / 任意 OpenAI 兼容自定义 API),按角色绑定 |
| 🎭 **多角色多人格** | 数据驱动的角色库,可增 / 删 / 改;每个角色绑定形象 + 默认音色 + 性格 |
| 🏝️ **灵动岛模式** | 收进 MacBook notch 旁的迷你 pill,hover 展开成音乐播放器(封面 / 歌词 / 进度) |
| 🗂️ **记得住** | 长期事实自动记录 + 可手动删;短期会话留在内存,退出即忘;不污染工具调用 |
| 📣 **主动搭话** | 每日热点日报 / 提醒 / 下雨叮嘱会主动开口,但播报排队、不打断你正在说的话 |

**它能替你干的活(说一句 / 拖一下就办):**

| | |
|---|---|
| 📸 **截图取字** | 快捷键框选或截整个窗口 → 复制 / 存桌面 / OCR 读出文字 / 识别二维码 / 标注(画框·箭头·涂鸦)/ 钉在桌面 |
| 🗜️ **压缩 / 解压** | 拖压缩包给它解开、拖文件夹给它压成 zip —— 都先问一句再动手 |
| 📊 **分析表格** | 拖个 Excel / CSV 进来直接问数据,用 pandas 真算(不是肉眼估),还能出图,多大的表都行 |
| 🎵 **听歌 / 管歌** | 放歌 / 暂停 / 切歌;QQ音乐大脑:搜歌·每日推荐·电台·听歌报告·口味解读·榜单;岛上实时显示当前播放(封面 / 歌词 / 进度,QQ音乐 / 网易云 / Apple Music 都读得到) |
| 👀 **读屏 / 操作软件** | 本地视觉模型读懂屏幕(榜单 / 列表 / 界面);还能在任意软件里点按钮、往搜索框打字、看结果(computer use) |
| 🔍 **查 · 搜 · 读** | 找文件(Spotlight)、联网搜资料、读网页正文全文、读你此刻选中的那段字(翻译 / 搜 / 解释) |
| 🌤️ **生活助手** | 查天气(精确定位)、取验证码(邮箱)、查日程 / 加提醒 / 加备忘、发邮件 |
| 🎨 **创作** | 生成图片(可接着"换成二次元风格"连续改)、写作润色改写、做 PPT / 文档 |
| 🖥️ **系统小事** | 打开 / 关 App、开网页、调音量、锁屏、弹通知、读写剪贴板、跑 Shortcuts 快捷指令、装 / 卸软件(Homebrew,先问再装) |
| 🤝 **超纲委派** | 干不了的活统一 `delegate` 交给后台同事(Hermes / Claude / Codex),按任务挑可用的、先问你 |

---

## 🎮 交互入口

| 操作 | 效果 |
|---|---|
| **左键单击** 数字人 | 弹出对话气泡 + 输入框 |
| **右键** 数字人 | 上下文菜单(设置 / 隐藏 / 切角色 / 模式切换 / 重置位置 / 重新引导) |
| **拖文件** 到数字人或灵动岛 | 询问你想对文件做什么(发邮件 / 翻译 / 整理 / 压缩,拖压缩包则问要不要解压…) |
| **按住右 `⌥`** | push-to-talk 语音输入,松开转文字 |
| **`⌃⌥S`** 截图 | 框选(按空格切整窗口)→ 一排动作:复制 / 保存 / OCR / 扫码 / 标注 / 钉桌面 |

输入框支持标准编辑快捷键:`⌘C` / `⌘V` / `⌘X` / `⌘A` / `⌘Z` / `⇧⌘Z`。退出:菜单栏 →「退出喵」(`⌘Q`)。

---

## ⚙️ 配置(可选,想更强再看)

密钥与个人数据**都只在你本机**(用户目录 `~/.config/desktop-avatar/`,`0700/0600` 权限),不上传:

- **换 / 加聊天模型**:设置 → API 管理 →「＋ 添加 API」填 Base URL(`https://host/v1`)+ key,即接任意 OpenAI 兼容后端(OpenRouter / DeepSeek / 硅基流动 / 本地 vLLM…),零门槛;本地模型放进对应文件夹自动读取。
- **配委派同事**:Claude 填 `setup-token` 长串、Codex 终端 `codex login`、Hermes 本机服务在跑即可(详见手册 §6.5)。
- **语音 / 邮件 / 音乐 key** 等都在设置各页里填。

> 全部路径、每页设置、每个工具的用法,见 **[📖 完整使用手册 · MANUAL.md](MANUAL.md)**。

---

## 🔄 检查更新

App 内「检查更新」会读本仓库的 [`latest.json`](latest.json) 比对构建号,有新版就气泡提示 + 给下载链接(**不自动下载、不自动装** —— 下不下你说了算)。每版具体改了啥,见 [Releases](https://github.com/solaswing/avatar-releases/releases)。

---

## 📦 授权 · 第三方

**本项目代码**采用 **AGPL-3.0**:欢迎自由使用、学习、修改;但**任何分发的衍生版本、以及以网络服务形式提供的部署,都必须同样以 AGPL-3.0 开源**。想在**闭源 / 商业**产品里集成、或不接受 AGPL 义务的,请单独联系作者获取**商业授权**。

第三方组件各自遵循其许可:

- **Live2D「Mao」示例模型 + Cubism SDK**:归 **Live2D Inc.** 版权所有,内嵌部分受 **Live2D Free Material License Agreement (FMLA)** 约束(需署名、营收 <1000 万日元、不得做「导入任意模型」的 Expandable Application)。**这部分不因本项目的 AGPL 而改变**。
- **BoringNotch**(媒体遥控适配):**BSD 3-Clause**。

> © 2026 周晓林 · AGPL-3.0。「喵 / Miao」名称为本项目普通法商标(™)。(「Mao」是内置那张 Live2D 脸的名字,归 Live2D Inc.,与产品名无关。)
> 商业 / 闭源授权咨询:📮 <397659470@qq.com>,或 GitHub [@solaswing](https://github.com/solaswing)。
