# Малыш (小家伙)

<div class="rom-hero">
    <h1 class="rom-hero-title">Малыш</h1>
    <p class="rom-hero-subtitle">电子管推挽式 A/AB 类放大器，带固定偏置</p>
</div>

<div class="rom-mission">
    <p class="rom-mission-text">
        <strong>人民的电子管放大器。计划中的套件。</strong>
    </p>
    <p class="rom-mission-text" style="margin-top: 1rem;">
        Малыш 是面向所有人的项目。计划在研发完成和原型组装后以套件形式供应。
        电子管技术通过现代控制和分析系统重新诠释。
    </p>
</div>

---

## 1. 架构和概念

| 参数 | 值 |
|------|-----|
| **类型** | 电子管推挽式 A/AB 类放大器 |
| **平台** | 通用电子管壁挂式平台 (Tube-Agnostic Platform) |
| **主要特点** | 内置特性曲线仪 (Ia/Vg 计) 和数字"指挥" (Auto-Bias) |
| **控制** | Arduino Nano (C 脚本), USB/Ethernet 接口 |

---

## 2. 模块化结构 (3 块板)

### 板 #1: Front-End (信号)

| 参数 | 描述 |
|------|------|
| **尺寸** | 300 × 50 mm (2 层，底层接地平面) |
| **元件** | 2× 6N23P-EV (驱动/倒相)，ALPS 电位器 (电动) |
| **输入** | 前面板 RCA |
| **安装** | 三明治：灯座在走线侧，灯穿过机箱。元件在机箱地下室，信号走线在钢制机箱和电路板底层 Ground Plane 之间 |

### 板 #2: Tube Controller (大脑，可选)

| 参数 | 描述 |
|------|------|
| **尺寸** | 63.5 × 35.5 mm (预生产格式) |
| **芯片** | Arduino Nano (或 STM32) |
| **功能** | |
| — Auto-Bias | 保持静态电流 (45–60 mA)，精度 0.1 mA |
| — 特性曲线仪 | 更换灯时自动记录 Ia/Vg 曲线 |
| — 发射 | 测量灯剩余寿命 (Emission Health Check) |
| **连接** | USB (Arduino Nano) 或 Ethernet (量产) |

### 板 #3: PSU (电源)

| 功能 | 描述 |
|------|------|
| **整流器** | 独立整流器 ("双单声道") |
| **滤波器** | 驱动滤波器 |
| **偏置** | 负偏置电源 (-60V) |
| **逻辑** | 逻辑电源 (+5V) |

---

## 3. 硬件 (Atoms & Iron)

### 输出变压器 (TVZ)

| 版本 | 描述 |
|------|------|
| **量产** | OSM-0.16 钢帽 ("锅")，工厂制造 |

### 电源变压器

- **OSM-0.4** (工厂制造)

### 扼流圈

- **2× OSM-0.063** (顶板，带帽)

### 机箱

| 参数 | 描述 |
|------|------|
| **设计** | "Slim" (高度 45 mm)，可拆卸 |
| **材料** | 钢 2 mm |
| **结构** | Flat-pack (螺栓组装) |

---

## 4. 电子管通用性 (Tube Agnostic)

得益于控制器和机箱支持所有必要的灯座，允许你使用现有的输出电子管和灯座组装放大器：

| 电子管 | 特性 |
|--------|------|
| **G-807** | 魅力和力量 |
| **6P3S / EL34** | 经典 |
| **6P36S / 6P44S** | 低阻抗，低音控制 |
| **GU-50** | 坦克之声 |

---

## 5. 项目经济 (套件)

| 参数 | 值 |
|------|-----|
| **格式** | 套件 — 计划发布 |
| **组件** | 工厂 OSM 变压器、外壳、预焊接电路板、元件套件 |
| **套件成本** | ~52,000 卢布 |
| **零售价格** | 75,000 – 85,000 卢布 (完整配置带电动音量、Tube Controller 以太网和交钥匙组装) |
| **定位** | 面向所有人的人民电子管放大器 |

---

## 文档

- [🔊 放大器](amps.md) — 放大器规格
- [⚙️ 铁件](iron.md) — 变压器和绕制

---

<div class="rom-footer">
    <p class="rom-footer-tagline">Communicate. Command. Control.</p>
    <p><a href="https://intent-garden.org">🌿 Intent-Garden.Org</a></p>

    <div class="rom-lang-switcher" style="margin: 1.5rem 0;">
        <a href="/en/malysh/" class="rom-lang-btn">🇺🇸 EN</a>
        <a href="/ru/malysh/" class="rom-lang-btn">🇷🇺 RU</a>
        <a href="/zh/malysh/" class="rom-lang-btn">🇨🇳 ZH</a>
    </div>
</div>
