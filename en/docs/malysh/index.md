# Malysh (The Kid)

<div class="rom-hero">
    <h1 class="rom-hero-title">Malysh</h1>
    <p class="rom-hero-subtitle">Tube Push-Pull Class A/AB Amplifier with Fixed Bias</p>
</div>

<div class="rom-mission">
    <p class="rom-mission-text">
        <strong>Sovereign Audio Platform. Planned as a KIT.</strong>
    </p>
    <p class="rom-mission-text" style="margin-top: 1rem;">
        Malysh is a project for EVERYONE. Planned for release as a kit after R&D completion and prototype assembly. 
        Tube technology reimagined through modern control and analysis systems.
    </p>
</div>

---

## 1. Architecture and Concept

| Parameter | Value |
|-----------|-------|
| **Type** | Tube Push-Pull Class A/AB Amplifier |
| **Platform** | Universal Tube Wall-Stand (Tube-Agnostic Platform) |
| **Key Feature** | Built-in Curve Tracer (Ia/Vg Meter) and Digital "Conductor" (Auto-Bias) |
| **Control** | Arduino Nano (C script), USB/Ethernet interface |

---

## 2. Modular Structure (3 Boards)

### Board #1: Front-End (Signal)

| Parameter | Description |
|-----------|-------------|
| **Size** | 300 × 50 mm (2-layer, Ground Plane on bottom) |
| **Components** | 2× 6N23P-EV (driver/phase inverter), ALPS potentiometer (motorized) |
| **Inputs** | RCA on front panel |
| **Mounting** | Sandwich: Tube sockets on trace side, tubes pass through chassis. Components in chassis basement, signal traces between steel chassis and Ground Plane on board's bottom side |

### Board #2: Tube Controller (Brain, Optional)

| Parameter | Description |
|-----------|-------------|
| **Size** | 63.5 × 35.5 mm (pre-production format) |
| **Chip** | Arduino Nano (or STM32) |
| **Features** | |
| — Auto-Bias | Hold idle current (45–60 mA) with 0.1 mA precision |
| — Curve Tracer | Automatic Ia/Vg curves when swapping tubes |
| — Emission | Residual tube life measurement (Emission Health Check) |
| **Connection** | USB (Arduino Nano) or Ethernet (production) |

### Board #3: PSU (Power Supply)

| Function | Description |
|----------|-------------|
| **Rectifiers** | Separate rectifiers ("dual mono") |
| **Filters** | Driver filters |
| **Bias** | Negative bias supply (-60V) |
| **Logic** | Logic power (+5V) |

---

## 3. Hardware (Atoms & Iron)

### Output Transformers (TVZ)

| Version | Description |
|---------|-------------|
| **Production** | OSM-0.063 in steel caps ("pots"), factory made |

### Power Transformer

- **OSM-0.16** (factory made)

### Chokes

- **2× OSM-0.036** (on top panel in caps)

### Enclosure (Heavy Metal)

With this set of iron and the steel chassis concept, Malysh emerges as a true Heavy Metal. Despite its name, this apparatus will weigh like a proper kettlebell.

**Detailed weight breakdown by "atoms":**

| Component | Weight |
|-----------|--------|
| **1. Transformer Group** | |
| Power Transformer OSM-0.16 (ШL 32×40) | ~3.2 kg |
| Output Transformers (2 pcs. PL 16×36) | ~3.6 kg (1.8 kg each) |
| Chokes (2 pcs. OSM-0.036) | ~1.6 kg (0.8 kg each) |
| **Total for copper and iron** | **~8.4 kg** |
| | |
| **2. Enclosure and Shielding** | |
| Chassis (430×300×45 mm, steel 2 mm) | ~2.8 kg |
| Caps ("Pots", 5 pcs) | ~1.5 kg |
| Bottom cover and fasteners | ~0.8 kg |
| **Total for metal** | **~5.1 kg** |
| | |
| **3. Components and Tubes** | |
| Capacitors (2000 µF cans) | ~0.6 kg |
| Tubes (4×G-807 + 2×6N23P) | ~0.5 kg |
| PCBs (3 pcs), heatsinks, ALPS, wires | ~0.4 kg |
| **Total for "misc"** | **~1.5 kg** |

**✅ Total estimated weight of Malysh (The Kid) amplifier:**

<div class="rom-mission" style="margin-top: 1rem;">
    <p class="rom-mission-text">
        <strong>~15.0 kg (± 1 kg)</strong>
    </p>
</div>

**Benefits of this weight:**

| Aspect | Benefit |
|--------|---------|
| **For Sound** | Large mass and steel chassis perfectly dampen tube microphonics and transformer vibrations |
| **For Image** | When a KIT buyer lifts a 15 kg box, they understand they bought a "thing", not an empty tin can |
| **For Logistics** | 15 kg still passes standard CDEK/Post tariffs without special equipment |

This is real "cast iron" sound!

---

## 4. Tube Agnostic

Thanks to the controller and chassis supporting all necessary sockets, you can build an amplifier using your existing output tubes and sockets:

| Tube | Characteristic |
|------|----------------|
| **G-807** | Charisma and power |
| **6P3S / EL34** | Classic |
| **6P36S / 6P44S** | Low impedance, bass control |
| **GU-50** | Tank sound |

---

## 5. Project Economics (KIT)

| Parameter | Value |
|-----------|-------|
| **Format** | KIT — planned for release |
| **Components** | Factory transformers (TVZ OSM-0.063, TS OSM-0.16), chokes (OSM-0.036), enclosures, pre-assembled PCBs, component sets |
| **Kit Cost** | ~52,000 RUB |
| **Retail Price** | 75,000 – 85,000 RUB (full config with motorized volume, Tube Controller with Ethernet and turnkey assembly) |
| **Positioning** | Sovereign Audio Platform. Taming the power of G-807, GU-50. For Sound Gardeners. |

---

## Documentation

- [🔊 Amplifiers](amps.md) — amplifier specifications
- [⚙️ Iron](iron.md) — transformers and winding

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
