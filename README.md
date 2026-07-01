# 喵 (Mao) · 发布通道

[![downloads](https://img.shields.io/github/downloads/solaswing/avatar-releases/total?color=F2814A&label=%E4%B8%8B%E8%BD%BD%E6%80%BB%E6%95%B0)](https://github.com/solaswing/avatar-releases/releases/latest)
[![latest](https://img.shields.io/github/v/release/solaswing/avatar-releases?color=6FE0A8&label=%E6%9C%80%E6%96%B0%E7%89%88)](https://github.com/solaswing/avatar-releases/releases/latest)

> **跟社交软件反着来的桌面数字人。**
> 别的软件把你拉进别人的生活、榨你的注意力;喵住在你桌面上 —— 既是会干活的**同事**,也是懂你的**伴侣**。简单的活一句话就办,专业的活也能上手,而且越用越懂你。**默认全在本地。**

一只浮在 macOS 桌面上的 Live2D 伙伴 —— 有脸、会陪你、记得住你,还能连上你的 App 和网页帮你干活。

本仓库是「喵」的**公开发布通道**,只托管两样东西:**安装包**([Releases](https://github.com/solaswing/avatar-releases/releases/latest))+ **更新清单**([`latest.json`](latest.json),App 内「检查更新」比对用)。源码仓库私有,不在此处。

🌐 **想先看看?** 落地页带一只会 idle 动的实时 Live2D 演示 → **<https://solaswing.github.io/avatar-releases/>**

---

## ⬇️ 下载 · 安装

1. 去 [**Releases**](https://github.com/solaswing/avatar-releases/releases/latest) 下最新的 `Mao-x.y.z.dmg`。
2. 打开 DMG,把里面的 App 拖进「**应用程序**」。
3. 从启动台 / 应用程序双击打开。

> ✅ 已 **Developer ID 签名 + Apple 公证**,干净 Mac 双击即用,**不会有 Gatekeeper「无法打开」警告**,也不用右键「打开」那套。

**要求:** macOS 14 (Sonoma) 或更新 · **Apple Silicon**(M1 及以后)。Intel Mac 也能装,但只能走云聊天,本地私密那套用不了。

---

## 🎭 一个伙伴,三种形态

同一个喵,按你此刻在干嘛变身 —— 标题栏一点就切,占多占少你说了算。

| | 形态 | 说明 |
|---|---|---|
| 🧍 | **悬浮数字人** | 半透明浮在桌面角落,会跟着你的光标看、有话冒个泡 —— 一个待在那儿陪你、不挡事的伙伴。 |
| 💊 | **灵动岛** | 不想被看见就收进刘海,变一颗小药丸;鼠标一悬展开成播放器,封面 · 歌词 · 进度都在。 |
| 🪟 | **窗口模式** | 要正经聊、要干活,收进一个能缩放的窗口 —— 人物 + 聊天面板并排,长对话打字都顺手。 |

---

## 🧰 它能干啥

**🪄 简单的活 · 说一声就办**
查文件 · 播每日热点 · 定闹钟提醒 · 开 App / 放歌 / 看番 / 查天气 / 取验证码 · 截图取字(OCR)+ 扫码 + 框箭头标注 + 钉桌面 · 拖压缩包解开 / 拖文件压成 zip(都先问一句再动手)。

**🔧 专业的活 · 也能上手**
联网搜资料、读网页整理要点 · 描述一句直接生成图 · 起草 / 润色 / 改写 · 拖个 Excel/CSV 进来直接问数据(用 pandas 算,大表也精确)。

**💛 还是个会陪你的伴侣**
语音或打字聊天,**本地模型离线也能聊**,还能看屏幕回答你 · 记得你是谁(住哪儿、口味、在忙啥 —— 长期记忆在本地,越用越顺,随时能删)· 换脸换性子(自带 Mao,也能自定义多个角色,各有说话风格和音色)。

---

## 🔒 越能干,越该本地、私密

它看得到你屏幕、记得住你的事 —— 所以信任是地基:

- **数据在你机器上** —— 聊天和长期记忆默认留在本机,不上传、不拿去训练。
- **离线也行** —— 挑个本地中文模型,不联网也能聊,敏感的事根本不用过云端。
- **记忆看得见、随时删** —— 每条记忆都摆出来给你看,不想要的一键删。

---

## 🤝 说点老实话

免得你期望错位,喵擅长什么、不擅长什么,直说:

- **「操作软件」是开个大概,不是精确遥控。** 开 App、放歌、看番没问题;但要它在复杂界面里一帧帧丝滑点准每个按钮,做不到。专业的活它走的是**工具**(联网搜、生图、写作、pandas 算表格),靠实力办事,不是替你盲点界面。
- **学习是渐进的。** 越用越懂你,但不是第一天就全明白 —— 给它点时间。
- **看不到的当下事实,它不编。** 没真去查的比分/天气/屏幕内容,它会说「这个我没拿到」,而不是顺嘴编一个。

---

## 🔄 检查更新

App 内「检查更新」会读本仓库的 [`latest.json`](latest.json) 比对构建号,有新版就气泡提示 + 给下载链接(**不自动下载、不自动装** —— 下不下你说了算)。每版具体改了啥,见 [Releases](https://github.com/solaswing/avatar-releases/releases)。

---

## 📄 授权与致谢

- 应用许可 **AGPL-3.0**(闭源 / 商业授权另议)。
- 内置 Live2D 官方示例模型 **Mao**,遵循 [Live2D Cubism FMLA](https://www.live2d.com/eula/live2d-free-material-license-agreement_en.html)(需署名)。
- 系统 Now Playing 读取用到了 [BoringNotch](https://github.com/TheBoredTeam/boring.notch) 的 MediaRemoteAdapter(BSD-3-Clause)。

---

<sub>作者 周晓林 · 商务 / 授权咨询 <397659470@qq.com></sub>
