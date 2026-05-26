# Choose Your Own Contact (Microphone)
## 选择你的接触式（麦克风）：声音中的近距离接触 DIY 工作坊

---

## 中文版

### 一句话简介
从一片 piezo 开始，焊接、测试、封装，再用它录一段物体里的振动。

### 工作坊说明

我们平时听到的大多是空气里的振动。物体内部也会传递振动，但不一定能通过空气被听见。**接触式麦克风（Contact Microphone）** 是一种贴在物体表面、直接拾取固体振动的传感器。

工作坊提供材料、电路和三条制作路径。每个人先完成基础款，再根据时间和兴趣选择是否继续做 PiP 或 P48 版本。

最后用现场设备录音，并播放每个人选出的 60 秒素材。

### 我们会一起做什么

#### 1. 听：参考作品与制作案例（约 25 分钟）
开场会先看和听一组具体参考：
- [**Toshiya Tsunoda: Extract From Field Recording Archive**](https://erstwhilerecords.bandcamp.com/album/extract-from-field-recording-archive)：用小型麦克风和接触式麦克风记录港口、路面、绳索等物理振动
- [**Jacob Kirkegaard: AION**](https://www.moma.org/interactives/exhibitions/2013/soundings/artists/6/works/)：在切尔诺贝利禁区的废弃空间里记录房间共振
- [**Christina Kubisch: Electrical Walks**](https://electricalwalks.org/electrical-walks/)：用感应耳机把城市里的电磁场转成可听声音
- [**The Gladys Hydrophone**](https://www.instructables.com/The-Gladys-Hydrophone/)：基于 piezo 和缓冲电路的 DIY 水听器制作案例
- [**LOM: DIY contact microphones**](https://knowledge.lom.audio/research/contact_mics)：接触式麦克风和前级 / buffer 的技术笔记

听完这些，再做一个现场 A/B/C 演示：
- **A**：裸 piezo 直接接 iRig，你听到的是什么
- **B**：piezo + JFET buffer + PiP 供电进录音机，低频保留更多
- **C**：piezo + 平衡前级 + P48 进调音台，更适合较长线缆

这个演示只比较几个实际差异：低频、噪声、供电和线缆长度。

#### 2. 学：电路原理（约 20 分钟）
不需要电子工程背景。我们会用最直白的语言解释：
- piezo 是怎么"发电"的（压电效应）
- 为什么直接接设备会"丢低频"（高阻抗源 vs 低阻抗负载，形成高通滤波器）
- JFET buffer 怎么解决这个问题（阻抗变换）
- PiP（Plug-in Power）和 P48（幻象电源）是什么、各自适用什么场景
- 为什么 PiP 用一根线就能同时走信号和供电

#### 3. 做：三条路径任选（约 60 分钟）

**所有人先完成基础款**（20–30 分钟），保证每个人结束时都带走一只能工作的麦克风。然后根据时间和兴趣继续。

| 路径 | 接口 | 电路 | 适用场景 | 难度 |
|---|---|---|---|---|
| 🟢 基础款 | 3.5mm TRS | 裸 piezo | 手机 / iRig / 相机 | 焊 3 个点 |
| 🟡 PiP 款 | 3.5mm TRS | piezo + JFET buffer | iRig / Zoom 录音机 / 相机 | 焊 1 块小板 |
| 🔵 P48 款 | XLR | piezo + 平衡前级 | 调音台 / 专业便携录音机 | 焊 1 块小板 + XLR |

**外壳**：我们提供 3D 打印的统一外壳，预留扩展腔可以容纳进阶电路板。基础款做完外壳腔体是空的，进阶款把电路板塞进去再封。

**封装**：用 5 分钟快干环氧树脂直接灌进外壳里。3D 打印外壳本身就是模具，不脱模。这样工作坊结束就能拿走（虽然完全固化要回家放一晚）。

#### 4. 录：现场 + 外出录音（约 60 分钟）
我们提供三个录音任务，三选一：

- **A. 三种材质**：金属的、木质的、活的（身体 / 植物 / 水），各 20 秒
- **B. 一个空间的三个尺度**：墙、家具、小物件
- **C. 一个不可见的振动**：冰箱、水管、地板、窗户共振

不一定要按任务来，但任务可以在你不知道录什么的时候帮你起步。

录音设备：iRig + 手机、Zoom 录音机、调音台（看你做的是哪一款），都在现场。

#### 5. 分享：集体聆听会（约 30 分钟）
用监听音箱播放，每人 60 秒。听完之后简短地说一下你录的是什么、为什么选它。

### 你会带走什么
- 一只你自己做的接触式麦克风
- 一段现场录音
- 对固体振动、接触拾音和阻抗匹配的基本理解
- 一份基础电路知识，之后可以继续改电路或加效果

### 我们提供什么 / 你需要带什么

**我们提供**：piezo（20mm / 27mm / 35mm 三种）、JFET buffer 板、P48 平衡前级板、3.5mm TRS 与 XLR 接头、屏蔽线、3D 打印外壳、5min 环氧、焊台、iRig、Zoom 录音机、小调音台、监听耳机和音箱。

**你需要带**：你的手机或笔记本（用来听 / 存录音）。如果你有自己常用的录音机或便携设备，欢迎带来。

### 实务信息
- **时长**：约 4 小时
- **人数**：10–15 人
- **背景要求**：无。声音艺术 / 电子基础有帮助但不必要
- **安全提示**：焊台是热的；不要把 PiP 麦插到 P48 接口（会烧 JFET）；P48 设备要先接线再开电、先关电再拔线

---

## English Version

### One-line summary
Start with a piezo disc, solder it, test it, seal it, and use it to record vibration inside objects.

### Workshop Overview

Most of what we hear arrives as vibration in the air. Objects vibrate inside themselves too — most of the time, those vibrations don't make it through the air to our ears. A **contact microphone** is a sensor that sticks to a surface and picks up vibration directly through solids.

We provide the materials, circuits, and three build paths. Everyone starts with the basic version, then keeps going to PiP or P48 if time and interest allow.

At the end, we record on-site and play 60 seconds chosen by each participant.

### What We'll Do Together

#### 1. Listen: Reference works and build examples (~25 min)
We'll begin with a small set of concrete references:
- [**Toshiya Tsunoda: Extract From Field Recording Archive**](https://erstwhilerecords.bandcamp.com/album/extract-from-field-recording-archive): small microphones and contact microphones used to record physical vibrations in ports, pavement, ropes, and other surfaces
- [**Jacob Kirkegaard: AION**](https://www.moma.org/interactives/exhibitions/2013/soundings/artists/6/works/): room resonance recorded in abandoned spaces inside the Chernobyl exclusion zone
- [**Christina Kubisch: Electrical Walks**](https://electricalwalks.org/electrical-walks/): induction headphones used to make urban electromagnetic fields audible
- [**The Gladys Hydrophone**](https://www.instructables.com/The-Gladys-Hydrophone/): a DIY hydrophone build based on piezo elements and buffer circuits
- [**LOM: DIY contact microphones**](https://knowledge.lom.audio/research/contact_mics): technical notes on contact microphones and preamps / buffers

Then a live A/B/C demonstration:
- **A**: Bare piezo straight into iRig — what you actually hear
- **B**: piezo + JFET buffer + PiP into a recorder - keeps more low end
- **C**: piezo + balanced preamp + P48 into a mixer - better for longer cable runs

This demo keeps the comparison practical: low end, noise, power, and cable length.

#### 2. Learn: Circuit principles (~20 min)
No electronics background required. In plain language:
- How a piezo "generates" voltage (the piezoelectric effect)
- Why plugging it directly into a device drops the low end (high-impedance source meets low-impedance load → high-pass filter)
- How a JFET buffer fixes this (impedance conversion)
- What PiP (Plug-in Power) and P48 (phantom power) are, and when each applies
- Why PiP can carry signal and power on a single wire

#### 3. Build: Pick one of three paths (~60 min)

**Everyone completes the basic version first** (20–30 min) so no one leaves empty-handed. From there, you can keep going based on time and interest.

| Path | Connector | Circuit | Use cases | Difficulty |
|---|---|---|---|---|
| 🟢 Basic | 3.5mm TRS | Bare piezo | Phone / iRig / camera | 3 solder joints |
| 🟡 PiP | 3.5mm TRS | piezo + JFET buffer | iRig / Zoom recorders / cameras | 1 small board |
| 🔵 P48 | XLR | piezo + balanced preamp | Mixers / professional portable recorders | 1 small board + XLR |

**Enclosure**: We provide a unified 3D-printed shell with a chamber that fits the optional circuit boards. Basic builds leave the chamber empty; advanced builds drop the board in and seal.

**Potting**: 5-minute epoxy poured directly into the shell. The 3D-printed shell is the mold — no demolding. You can carry the mic out at the end of the workshop (full cure happens overnight at home).

#### 4. Record: On-site and short walks (~60 min)
Three optional recording prompts:

- **A. Three materials**: metal, wood, something alive (your body, a plant, water) — 20 seconds each
- **B. A space at three scales**: a wall, a piece of furniture, a small object
- **C. An invisible vibration**: fridge, water pipe, floor, window resonance

You don't have to follow the prompts, but they're there if you don't know where to start.

Equipment on-site: iRig + your phone, Zoom recorders, a small mixer — depending on which build you chose.

#### 5. Share: Collective listening session (~30 min)
Playback on monitor speakers, 60 seconds per person. Afterwards a short word from each: what you recorded, why you picked it.

### What You'll Take Home
- A contact microphone you made yourself
- One on-site recording
- A basic understanding of solid vibration, contact pickup, and impedance matching
- A working baseline of circuit knowledge for later modifications or effects

### What We Provide / What to Bring

**We provide**: piezo discs (20mm / 27mm / 35mm), JFET buffer boards, P48 balanced preamp boards, 3.5mm TRS and XLR connectors, shielded cable, 3D-printed enclosures, 5-minute epoxy, soldering stations, iRig, Zoom recorders, a small mixer, monitor headphones and speakers.

**You bring**: your phone or laptop for listening and storing recordings. If you have your own recorder or portable rig, bring it.

### Practical Info
- **Duration**: ~4 hours
- **Capacity**: 10–15 people
- **Prerequisites**: none. Background in sound art or electronics helps but is not required
- **Safety**: soldering irons are hot; never plug a PiP mic into a P48 input (it will fry the JFET); for P48 devices, connect cables before powering on, and power off before disconnecting

---

## 给我们自己（讲师）的注记 / Notes for Ourselves

### 工作坊前要准备的事
- [ ] 3D 打印 20 个外壳（含扩展腔）
- [ ] 预制 / 准备 20 块 JFET buffer 板（元件齐全）
- [ ] 准备 15 块 P48 板
- [ ] piezo 三种尺寸各采购 20 片
- [ ] 5min 环氧前一晚试一次，确认实际可操作时间
- [ ] 焊接元件清单按 15 人 ×1.3 倍冗余采购
- [ ] 准备 2–3 支讲师款成品麦做 A/B/C demo 和外出借用
- [ ] 准备一张 A4 cheat sheet：iRig + 手机设置 5 步、PiP 设备开启菜单位置、安全须知
- [ ] 建好录音上传共享文件夹（AirDrop + 微信群双备份）
- [ ] 监听音箱 + 房间提前测试（分享会用）

### 现场流程时间表
| 时间 | 内容 |
|---|---|
| 0:00–0:25 | 概念 + 参考作品 + A/B/C demo |
| 0:25–0:45 | 电路讲解 + 焊接示范 |
| 0:45–1:45 | 动手：基础款 → 进阶款 |
| 1:45–2:15 | 装外壳 + 灌环氧 |
| 2:15–3:15 | 借讲师麦外出录音（自己做的麦同时固化） |
| 3:15–3:45 | 听自己的麦，整理录音上传 |
| 3:45–4:15 | 集体聆听会 |

### 风险
1. 🔴 误插 P48 烧 PiP 麦 → 物理接口区分（PiP=3.5mm，P48=XLR），开场强调
2. 🔴 环氧没干就被带走 → 备 5 个讲师预制麦做替补，签收"回家放一晚"
3. 🟡 焊接慢手 → 至少 2 把焊台 + 1 个助手；提供"半成品板"
4. 🟡 录音上传失败 → AirDrop + 微信群 + 拷 SD 卡三层备份
