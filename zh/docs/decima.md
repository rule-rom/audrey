# 电子管 Decima

<div class="rom-hero">
    <h1 class="rom-hero-title">电子管 Decima</h1>
    <p class="rom-hero-subtitle">射击游戏自动瞄准的模拟神经形态核心</p>
</div>

<div class="rom-mission">
    <p class="rom-mission-text">
        <strong>16 管实验项目。</strong>
    </p>
    <p class="rom-mission-text" style="margin-top: 1rem;">
        将电子管技术与神经形态原理相结合，用于
        实时硬件决策。模拟温暖和确定性响应，专为射击游戏设计。
    </p>
</div>

---

## 概念

电子管 Decima 是一个**游戏协处理器**，利用
真空管的模拟特性进行启发式决策。

### 为什么在游戏中使用电子管？

| 数字 | 模拟 |
|------|------|
| 离散计算 | 连续物理 |
| 确定性算法 | 模拟启发式 |
| 微秒延迟 | 即时响应 |
| 冷静计算 | 温暖不可预测性 |

---

## 架构

### 核心：16 管

```
┌─────────────────────────────────────────────────────┐
│              电子管 Decima (16 管)                   │
├─────────────────────────────────────────────────────┤
│  ┌─────┐  ┌─────┐  ┌─────┐  ┌─────┐                │
│  │ L1  │  │ L2  │  │ L3  │  │ L4  │  → 视觉        │
│  └─────┘  └─────┘  └─────┘  └─────┘    通道        │
│  ┌─────┐  ┌─────┐  ┌─────┐  ┌─────┐                │
│  │ L5  │  │ L6  │  │ L7  │  │ L8  │  → 瞄准        │
│  └─────┘  └─────┘  └─────┘  └─────┘    电机        │
│  ┌─────┐  ┌─────┐  ┌─────┐  ┌─────┐                │
│  │ L9  │  │ L10 │  │ L11 │  │ L12 │  → 战术        │
│  └─────┘  └─────┘  └─────┘  └─────┘    决策        │
│  ┌─────┐  ┌─────┐  ┌─────┐  ┌─────┐                │
│  │ L13 │  │ L14 │  │ L15 │  │ L16 │  → 输出        │
│  └─────┘  └─────┘  └─────┘  └─────┘    触发器      │
└─────────────────────────────────────────────────────┘
```

### 功能块

| 块 | 电子管 | 用途 |
|----|--------|------|
| **视觉通道** | L1–L4 | 视频处理，目标检测 |
| **瞄准电机** | L5–L8 | 模拟瞄准跟踪目标 |
| **战术** | L9–L12 | 决策 (攻击/掩护) |
| **输出** | L13–L16 | 触发器：开火、移动、躲避 |

---

## 工作原理

### 神经形态类比

```
突触 (生物) → 电子管级 (模拟)
神经元 (生物) → 求和栅格 (模拟)
动作电位 → 阳极脉冲
```

### 信号处理

1. **输入**: 采集视频信号 (HDMI/USB)
2. **模拟处理**: 电子管放大"有趣"区域
3. **阈值触发**: 超阈值 — 触发器触发
4. **输出**: USB/HID → 游戏 (开火、移动)

---

## 技术规格

| 参数 | 值 |
|------|-----|
| **电子管** | 16 件 (6Н23П-ЕВ) |
| **电源** | +300V (阳极)，6.3V (灯丝)，-60V (偏置) |
| **输入** | HDMI (视频)，USB (配置) |
| **输出** | USB HID (键盘/鼠标)，GPIO (触发器) |
| **延迟** | < 1 ms (模拟路径) |
| **功耗** | ~150 W |

---

## 工作模式

### 🎯 自动瞄准

按对比度物体进行模拟瞄准跟踪。

```
视频 → 对比度 → 放大器 → 瞄准偏转
```

### 🔥 自动开火

目标进入扇区时阈值触发。

```
扇区 → 比较器 (电子管) → 触发器 → 开火
```

### 🧠 战术

模拟逻辑上的简单启发式：

- **掩护**: 低血量时 — 撤退
- **攻击**: 有优势时 — 前进
- **巡逻**: 随机游走 (电子管噪声)

---

## 项目状态

<div class="rom-mission" style="margin-top: 1rem;">
    <p class="rom-mission-text">
        <strong>🔜 开发中 — 敬请关注</strong>
    </p>
    <p class="rom-mission-text" style="margin-top: 1rem;">
        项目处于概念和早期实验阶段。
        首批原型预计 2026 年推出。
    </p>
</div>

---

## 与 Decima8 的连接

电子管 Decima 使用根 Decima8 的原则：

- **PHASE_READ/WRITE**: 模拟状态同步
- **确定性**: 可预测的实时响应
- **神经形态**: 神经连接的硬件仿真

---

## 联系

<div class="rom-contact" style="margin-top: 2rem;">
    <h3 class="rom-contact-title">参与开发</h3>
    <div class="rom-contact-grid">
        <div class="rom-contact-item">
            <span class="rom-contact-icon">✉️</span>
            <a href="mailto:audrey@rulerom.com">audrey@rulerom.com</a>
        </div>
    </div>
</div>

---

<div class="rom-footer">
    <p class="rom-footer-tagline">Communicate. Command. Control.</p>
    <p><a href="https://intent-garden.org">🌿 Intent-Garden.Org</a></p>

    <div class="rom-lang-switcher" style="margin: 1.5rem 0;">
        <a href="/en/decima/" class="rom-lang-btn">🇺🇸 EN</a>
        <a href="/ru/decima/" class="rom-lang-btn">🇷🇺 RU</a>
        <a href="/zh/decima/" class="rom-lang-btn">🇨🇳 ZH</a>
    </div>
</div>
