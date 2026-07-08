db & 安全音量大小

输入 处理 输出 模型

数字信号 midi 信号 模拟信号

混音 cubase

时序器

bus 舞台监听

打谱软件 guitar musescore

声学测量软件

## 大纲

**“物理声学基础 -> 硬件与信号流 -> 核心处理技术 -> 录音室混音实战 -> 现场扩音与系统调试 -> 前沿与进阶”**

### 第一阶段：声音、声学与数字音频基础

**目标：建立科学的听觉认知和物理概念，理解数字与模拟的区别。**

*   **1.1 物理声学基础**
    *   声波的物理特性（频率、振幅、波长、相位、声速）
    *   声音的传播原理（反射、吸收、折射、衍射）
    *   梳状滤波效应（Comb Filtering）与相位抵消
    *   驻波（Standing Waves）与房间共振模式（Room Modes）
*   **1.2 心理声学与听觉特性**
    *   等响度曲线（Fletcher-Munson Curves / 弗莱彻-芒森曲线）
    *   哈斯效应（Haas Effect）与优先效应
    *   听觉掩蔽效应（时域与频域）
    *   双耳声源定位（时间差 ITD 与强度差 ILD）
*   **1.3 电声学基础**
    *   分贝系统（dB SPL, dBu, dBV, dBFS 的定义与换算）
    *   阻抗（Impedance）匹配与桥接（高阻抗与低阻抗）
    *   平衡与非平衡信号传输原理（共模抑制比 CMRR）
*   **1.4 数字音频理论**
    *   模数/数模转换（ADC / DAC）
    *   采样率（Sample Rate）与奈奎斯特采样定理（Nyquist Theorem）
    *   位深度（Bit Depth）与动态范围（Dynamic Range）、量化噪声、抖动（Dither）
    *   系统延迟（Latency）与字时钟（Word Clock）

### 第二阶段：设备认知与信号流

**目标：掌握所有音频硬件的特性与操作，彻底搞懂“声音从哪来，经过哪，到哪去”。**

*   **2.1 麦克风技术**
    *   拾音原理分类（动圈、电容、铝带式）
    *   指向性（全指向、心形、超心形、8字形、枪式）
    *   麦克风参数解读（灵敏度、最大声压级、频率响应、底噪）
    *   近讲效应（Proximity Effect）与离轴染色（Off-axis Coloration）
*   **2.2 线缆、接口与周边设备**
    *   常见接口（XLR, TRS, TS, RCA, Speakon, BNC）
    *   DI盒（主动与被动DI的区别与应用场景）
    *   分线盒（Stagebox）与隔离变压器
*   **2.3 调音台架构（模拟与数字）**
    *   输入通道条（前置放大器 Mic Preamp, 幻象电源 48V, 极性反转 Phase/Polarity, Pad衰减）
    *   信号流节点（Insert插入点, Direct Out直接输出）
    *   母线系统（Aux Send 辅助发送前/后推子, Group/Subgroup 编组, Matrix 矩阵输出, LCR 主输出）
    *   控制组（VCA / DCA 编组的原理与应用）
    *   数字调音台特有功能（Layer层级, Routing跳线, Scene/Snapshot场景记忆, Offline Editor离线编辑）

### 第三阶段：核心信号处理技术

**目标：掌握塑造声音的三大核心工具：频域、动态与时空域处理。**

*   **3.1 增益架构（Gain Staging）**
    *   信噪比（S/N Ratio）与动态余量（Headroom）
    *   系统增益级的黄金法则与失真避免
*   **3.2 均衡处理（Equalization）**
    *   EQ种类（图示均衡 GEQ、参数均衡 PEQ、搁架式 Shelving、动态均衡 Dynamic EQ）
    *   高通/低通滤波器（HPF/LPF）及其斜率（Slope/Octave）
    *   频段划分与乐器基频/泛音列识别
    *   减法EQ（去频段）与加法EQ（染色）的哲学
*   **3.3 动态处理（Dynamics）**
    *   压缩器（Compressor）：四大参数（Threshold, Ratio, Attack, Release）、Knee（拐点）、Make-up Gain
    *   压缩器类型与染色（VCA, FET, 光学Opto, 电子管Vari-Mu）
    *   限制器（Limiter）与砖墙限制
    *   噪声门（Noise Gate）与扩展器（Expander）
    *   多频段压缩（Multiband Compression）
    *   侧链（Sidechain）技术与闪避（Ducking）
    *   De-esser（消除齿音）
*   **3.4 空间与时间效果（Time-Based Effects）**
    *   混响（Reverb）：参数解析（Pre-delay, Decay Time, Diffusion, Damping），种类（Hall, Room, Plate, Spring, Convolution/采样混响）
    *   延迟（Delay）：Slapback, Ping-Pong, 拍速计算（BPM to ms）
    *   调制类效果（Chorus, Flanger, Phaser）及其相位原理
*   **3.5 谐波与失真处理（Harmonics/Saturation）**
    *   磁带/电子管饱和（Saturation）
    *   激励器（Exciter）与失真（Distortion/Overdrive）

### 第四阶段：录音室混音实战（Studio Mixing）

**目标：能在DAW（数字音频工作站）中完成商业级音乐混音。**

*   **4.1 混音准备与工程管理**
    *   DAW基本操作与路由跳线（Pro Tools / Logic / Cubase等）
    *   轨道清理、色彩标记、编组与Session管理
*   **4.2 构建混音的三维空间**
    *   横向（声像 Panning 与立体声宽度 L/C/R 混音法）
    *   纵向（频段分布与频率掩蔽冲突解决）
    *   深度（音量大小、高频衰减、混响与延迟营造空间感）
*   **4.3 分轨混音技巧**
    *   鼓组（Drums）：底鼓与贝斯的频率咬合、军鼓的穿透力、Overhead的相位对齐、鼓组平行压缩（Parallel Compression/New York Compression）
    *   人声（Vocals）：音高修正（Auto-Tune/Melodyne）、多重压缩（Serial Compression）、空间润色
    *   吉他与键盘：频段避让与立体声扩展
*   **4.4 混音自动化（Automation）**
    *   音量推子骑行（Vocal Riding）
    *   声像与效果器参数动态变化
*   **4.5 混音母线（Mix Bus）与母带基础**
    *   Mix Bus 胶合压缩（Glue Compression）与总线EQ
    *   行业响度标准（LUFS, True Peak, RMS）
    *   导出格式与抖动处理
