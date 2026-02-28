# Tube Decima

<div class="rom-hero">
    <h1 class="rom-hero-title">Tube Decima</h1>
    <p class="rom-hero-subtitle">Analog Neuromorphic Core for Auto-Aim in Shooters</p>
</div>

<div class="rom-mission">
    <p class="rom-mission-text">
        <strong>Experimental project on 16 tubes.</strong>
    </p>
    <p class="rom-mission-text" style="margin-top: 1rem;">
        Combining tube technology with neuromorphic principles for 
        hardware decision-making in real-time. Analog warmth 
        and deterministic response for shooters.
    </p>
</div>

---

## Concept

Tube Decima is a **hardware co-processor** for games that uses 
the analog nature of vacuum tubes for heuristic decision-making.

### Why Tubes in Gaming?

| Digital | Analog |
|---------|--------|
| Discrete computation | Continuous physics |
| Deterministic algorithms | Analog heuristics |
| Microsecond latencies | Instant response |
| Cold calculation | Warm unpredictability |

---

## Architecture

### Core: 16 Tubes

```
┌─────────────────────────────────────────────────────┐
│              Tube Decima (16 tubes)                 │
├─────────────────────────────────────────────────────┤
│  ┌─────┐  ┌─────┐  ┌─────┐  ┌─────┐                │
│  │ L1  │  │ L2  │  │ L3  │  │ L4  │  → Vision      │
│  └─────┘  └─────┘  └─────┘  └─────┘    channel     │
│  ┌─────┐  ┌─────┐  ┌─────┐  ┌─────┐                │
│  │ L5  │  │ L6  │  │ L7  │  │ L8  │  → Aim         │
│  └─────┘  └─────┘  └─────┘  └─────┘    motor       │
│  ┌─────┐  ┌─────┐  ┌─────┐  ┌─────┐                │
│  │ L9  │  │ L10 │  │ L11 │  │ L12 │  → Tactics     │
│  └─────┘  └─────┘  └─────┘  └─────┘    decisions   │
│  ┌─────┐  ┌─────┐  ┌─────┐  ┌─────┐                │
│  │ L13 │  │ L14 │  │ L15 │  │ L16 │  → Output      │
│  └─────┘  └─────┘  └─────┘  └─────┘    triggers    │
└─────────────────────────────────────────────────────┘
```

### Functional Blocks

| Block | Tubes | Purpose |
|-------|-------|---------|
| **Vision Channel** | L1–L4 | Video processing, target detection |
| **Aim Motor** | L5–L8 | Analog aim tracking to target |
| **Tactics** | L9–L12 | Decision making (attack/cover) |
| **Output** | L13–L16 | Triggers: fire, move, dodge |

---

## Operating Principles

### Neuromorphic Analogy

```
Synapse (biology) → Tube stage (analog)
Neuron (biology) → Summing grid (analog)
Action potential → Anode pulse
```

### Signal Processing

1. **Input**: Video signal from capture (HDMI/USB)
2. **Analog Processing**: Tubes amplify "interesting" areas
3. **Threshold Trigger**: On exceed — trigger fires
4. **Output**: USB/HID → game (fire, move)

---

## Technical Specifications

| Parameter | Value |
|-----------|-------|
| **Tubes** | 16 pcs (6N23P-EV) |
| **Power** | +300V (anode), 6.3V (heater), -60V (bias) |
| **Input** | HDMI (video), USB (configuration) |
| **Output** | USB HID (keyboard/mouse), GPIO (triggers) |
| **Latency** | < 1 ms (analog path) |
| **Consumption** | ~150 W |

---

## Operating Modes

### 🎯 Auto-Aim

Analog aim tracking by contrast objects.

```
Video → Contrast → Amplifier → Aim deflection
```

### 🔥 Auto-Fire

Threshold trigger when target enters sector.

```
Sector → Comparator (tube) → Trigger → Fire
```

### 🧠 Tactics

Simple heuristics on analog logic:

- **Cover**: On low HP — retreat
- **Attack**: On advantage — advance
- **Patrol**: Random walk (tube noise)

---

## Project Status

<div class="rom-mission" style="margin-top: 1rem;">
    <p class="rom-mission-text">
        <strong>🔜 In Development — Stay Tuned</strong>
    </p>
    <p class="rom-mission-text" style="margin-top: 1rem;">
        Project is at concept and early experimentation stage. 
        First prototypes expected in 2026.
    </p>
</div>

---

## Connection to Decima8

Tube Decima uses principles from root Decima8:

- **PHASE_READ/WRITE**: Analog state synchronization
- **Determinism**: Predictable real-time response
- **Neuromorphic**: Hardware emulation of neural connections

---

## Contact

<div class="rom-contact" style="margin-top: 2rem;">
    <h3 class="rom-contact-title">Participate in Development</h3>
    <div class="rom-contact-grid">
        <div class="rom-contact-item">
            <span class="rom-contact-icon">✉️</span>
            <a href="mailto:decima@rulerom.com">decima@rulerom.com</a>
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
