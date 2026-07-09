# 音频基础知识

音频基础 1节  课后作业：线材焊接，拓扑图绘制

- 声音、声学与数字音频基础
- 常见接口与音频线材
- 设备认知（麦克风，各种乐器，音响，功放）
- 乐器 & 音响设备连接，无线设备使用，系统拓扑，乐器效果器链

## 参考大纲

这是一份为您深度梳理的**「音频基础（第1节）」全景式教学大纲**。大纲严格按照您提供的核心模块展开，去除了冗长的解释，最大化地填充了音频工程领域的硬核基础知识点与专业术语，非常适合作为专业音响工程、录音艺术或现场扩声（Live Sound）课程的体系框架。

---

# 🎧 《音频与系统基础》第1节：全景大纲

## 一、 声音、声学与数字音频基础 (Acoustics & Digital Audio Basics)
### 1. 物理声学基础 (Physical Acoustics)
*   **声波三要素**：频率 (Frequency/音高)、振幅 (Amplitude/响度)：介绍分贝、波形 (Waveform/音色)
*   **物理特性**：波长 (Wavelength)、周期 (Period)、相位 (Phase) 与相位抵消
*   **传播特性**：声速 (Speed of Sound, 20℃时约 343 m/s)、平方反比定律 (Inverse Square Law)：距离声源每增加一倍，声音大小固定减少 6分贝
*   **环境声学现象**：反射 (Reflection)、吸收 (Absorption)、绕射/衍射 (Diffraction)、折射 (Refraction)
*   **室内声学基础**：混响 (Reverberation)、回声 (Echo)、驻波 (Standing Waves)、房间共振 (Room Modes)

### 2. 心理声学基础 (Psychoacoustics)
* **人耳听觉范围**：20Hz - 20kHz

  低中高音划分：
*   **等响度曲线**：Fletcher-Munson Curves（弗莱彻-芒森曲线）
*   **听觉效应**：哈斯效应 (Haas Effect / 优先效应)、掩蔽效应 (Masking Effect)、双耳定位 (Binaural Localization)

### 3. 数字音频基础 (Digital Audio)
*   **模数/数模转换**：ADC (Analog to Digital) 与 DAC (Digital to Analog)
*   **采样率 (Sample Rate)**：奈奎斯特定理 (Nyquist Theorem)、常见标准 (44.1k, 48k, 96k, 192k)
*   **位深度 (Bit Depth)**：动态范围 (Dynamic Range)、量化噪声与抖动 (Dither)、常见标准 (16-bit, 24-bit, 32-bit float)
*   **系统参数**：缓冲大小 (Buffer Size) 与 延迟 (Latency)
*   **音频文件格式**：无损 (WAV, AIFF, FLAC) 与 有损 (MP3, AAC)

---

## 二、 信号电平、常见接口与音频线材 (Signals, Interfaces & Cables)
### 1. 音频信号分类与电平 (Audio Signal Levels)
*   **麦克风电平 (Mic Level)**：毫伏级（最弱信号，需话放）
*   **乐器电平 (Instrument Level)**：高阻抗信号 (Hi-Z)
*   **线路电平 (Line Level)**：专业级 (+4 dBu) 与 消费级 (-10 dBV)
*   **扬声器电平 (Speaker Level)**：大电流/高电压（需功放驱动）

### 2. 传输原理：平衡与非平衡 (Transmission Principles)
*   **非平衡信号 (Unbalanced)**：单芯屏蔽 (Tip-Sleeve)，易受电磁干扰 (EMI/RFI)，适合短距离
*   **平衡信号 (Balanced)**：双芯屏蔽 (Tip-Ring-Sleeve / Hot-Cold-Ground)，共模抑制比 (CMRR) 消除底噪，适合长距离

### 3. 常见模拟接口与线材 (Analog Connectors)
*   **XLR (卡侬头)**：最常见的平衡接口（公头/母头定义，Pin 1地，Pin 2热，Pin 3冷）
*   **1/4" (6.35mm) 插头**：大三芯 TRS（平衡/立体声）与 大二芯 TS（非平衡/单声道/吉他线）
*   **1/8" (3.5mm) 插头**：常见消费级耳机/AUX接口（TRS/TRRS）
*   **RCA (莲花头)**：常见于DJ设备、家庭影院（非平衡）
*   **Speakon (NL2/NL4/NL8)**：专业无源音箱连接头（防呆、锁扣设计）

### 4. 常见数字与网络音频接口 (Digital & Network Protocols - 基础提及)
*   **传统数字接口**：MIDI (5-pin DIN), S/PDIF (同轴/光纤), AES/EBU, ADAT (光纤)
*   **网络数字协议 (AoIP)**：Dante, AVB, MADI, SoundGrid (系统拓扑扩展)

---

## 三、 核心音频设备认知 (Core Audio Equipment Recognition)
### 1. 拾音设备：麦克风 (Microphones)
*   **工作原理分类**：
    *   动圈麦克风 (Dynamic)：耐高声压级(SPL)，无需供电（如 Shure SM58/SM57）
    *   电容麦克风 (Condenser)：灵敏度高，频响宽，需 48V 幻象电源 (Phantom Power)
    *   铝带麦克风 (Ribbon)：脆弱，音色温暖复古
*   **指向性 (Polar Patterns)**：全指向 (Omnidirectional)、心形 (Cardioid)、超心形 (Supercardioid)、8字型 (Figure-8/Bidirectional)
*   **近讲效应 (Proximity Effect)**

### 2. 音源与乐器接口设备 (Instruments & DI)
* **DI盒 (Direct Injection Box)**：作用（高阻转低阻，非平衡转平衡），无源 (Passive) 与有源 (Active) 的选择

* 各类乐器输出特性（电吉他、电贝斯、键盘/合成器、原声乐器拾音器）

* 各种乐器的声音

* 各种效果器介绍

#### 乐器效果器链配置 (Instrument Effects Chain)

  常见于吉他和贝斯

  *   **串联模式 (Insert/In-Line)**：
      *   动态类 (Dynamics)：压缩 (Compressor)、降噪 (Noise Gate)、限幅 (Limiter)
      *   增益类 (Gain/Dirt)：过载 (Overdrive)、失真 (Distortion)、法兹 (Fuzz)
      *   频响类 (EQ/Filter)：哇音 (Wah)、图形/参数均衡器
      *   调制类 (Modulation)：合唱 (Chorus)、相位 (Phaser)、镶边 (Flanger)、颤音 (Tremolo)
  *   **并联模式 (Send/Return - 调音台常见或音箱效果环路)**：
      *   时间/空间类 (Time-based)：延迟 (Delay)、混响 (Reverb)
  *   **标准吉他踏板连接顺序拓扑** (Tuner -> Dynamics -> Dirt -> Modulation -> Time)

### 3. 控制中枢：调音台 (Mixing Consoles)
*   **架构认知**：模拟调音台 (Analog) vs. 数字调音台 (Digital)
*   **通道条 (Channel Strip) 基础**：Gain(增益/话放), HPF/LPF(高低通滤波), EQ(均衡), Aux/Send(辅助发送), Pan(声像), Fader(推子), Mute/Solo
*   **母线与路由 (Buses & Routing)**：Main Mix(主输出), Subgroups(编组), VCA/DCA, Matrix(矩阵)

### 4. 驱动与发声：功放与音响系统 (Amplifiers & Speakers)
*   **功放 (Power Amplifiers)**：阻抗匹配 (Impedance/Ohms)，功率余量 (Headroom)，持续功率(RMS) vs. 峰值功率(Peak)，阻尼系数
*   **扬声器 (Speakers)**：
    *   有源音箱 (Active) vs. 无源音箱 (Passive)
    *   频段划分：超低音 (Subwoofer)、低音 (Woofer)、中音 (Mid-range)、高音 (Tweeter)
    *   分频器 (Crossover)：主动分频与被动分频
*   **线阵列 与 点声源:**

---

## 四、 连接、无线电、系统拓扑与效果器链 (System Flow & Topology)
### 1. 信号流与增益架构 (Signal Flow & Gain Staging)
*   **标准信号流**：音源 (Source) -> 麦克风/DI -> 线缆 -> 话放 (Preamp) -> 调音台处理 -> 功放 (Amp) -> 扬声器 (Speaker) -> 人耳
*   **增益架构 (Gain Staging)**：信噪比 (SNR)、底噪 (Noise Floor)、削波失真 (Clipping) 的控制原则

### 2. 无线音频设备使用基础 (Wireless Systems)
*   **组成部分**：发射机 (Transmitter - 麦克风/腰包) + 接收机 (Receiver)
*   **频段选择**：VHF vs. UHF，2.4GHz 系统的优缺点
*   **系统稳定性**：频点规划 (Frequency Coordination) 避免互调失真 (IMD)、天线分配系统 (Antenna Distribution)、真分集 (True Diversity) 技术
*   **IEM (In-Ear Monitors)**：无线个人耳返系统的信号路由

### 3. 现场系统拓扑基础 (System Topology)
*   **主扩系统 (FOH - Front of House)**
*   **舞台返听系统 (Stage Monitoring)**：地台音箱 (Wedges) 与 耳返 (IEM)
*   **接口箱 (Stage Box) 与 信号分配 (Splitters)**

---

## 五、 课后作业 (Homework)

### 📝 作业 1：线材焊接实操 (Cable Soldering Practice)
*   **任务 A (平衡线)**：制作一条 3米 标准 XLR 公转母麦克风线。
    *   *考核点*：剥线长度控制、镀锡质量、Pin 1/2/3 防错焊、屏蔽网处理、焊点光泽饱满无虚焊。
*   **任务 B (非平衡线)**：制作一条 3米 1/4" TS 吉他乐器线。
    *   *考核点*：芯线与屏蔽网的隔离、线夹固定、防拉扯测试。

### 📝 作业 2：系统拓扑图绘制 (System Topology Drawing)
*   **任务描述**：假设你需要为一个小型现场乐队（编制：主唱x1、电吉他x1、木吉他x1、电贝斯x1、键盘x1）搭建系统。请使用绘图工具（或手绘）画出从**音源拾取**到**调音台**，再到**扩声/返听音箱**的完整系统连线拓扑图。
*   **考核点（图面必须包含）**：
    1.  正确的设备选用（主唱选什么麦？吉他/键盘是否需要DI盒？用什么线材连接？）
    2.  连线类型标注（用不同颜色或线条标明 XLR平衡线、TS非平衡线、Speakon喇叭线）。
    3.  调音台的信号分配（Main LR 接主扩功放/音箱，Aux 发送接舞台返听音箱）。
    4.  标注 48V 幻象电源的开启位置（如有需要）。
