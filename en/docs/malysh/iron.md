# Iron

<div class="rom-hero">
    <h1 class="rom-hero-title">Transformers and Chokes</h1>
    <p class="rom-hero-subtitle">The Heart of Analog Path</p>
</div>

---

## Output Transformers (TVZ)

### Production: OSM-0.063 (Factory Made)

| Parameter | Value |
|-----------|-------|
| **Core** | ШL 20×25 (OSM-0.063) |
| **Steel Cross-Section** | 5.0 cm² (effective ~4.5 cm²) |
| **Primary Winding (I)** | 3600 turns (wire 0.18–0.2 mm) |
| **Secondary Winding (II)** | 118 turns (for 8 Ohm, wire 0.5 mm in 2 strands) |
| **Sectionalizing** | 3P + 2S (P-S-P-S-P) |
| **Raa (reflected)** | ~7.5 kOhm |
| **Low Frequency (fL)** | ~25 Hz (-1 dB) |
| **Production** | Factory winding, quality control |

---

## Power Transformer (TS)

### OSM-0.16 (Factory Made)

| Parameter | Value |
|-----------|-------|
| **Core** | ШL 32×40 (OSM-0.16) |
| **Rated Power** | 160 W (×2 margin from consumption) |
| **Anode Winding** | 2 × 260V (0.25A) — for "dual mono" |
| **Filament Winding 1** | 6.3V (4A) — output tubes + driver |
| **Bias Winding** | 50V (0.1A) — for fixed bias and curve tracer |
| **Service Winding** | 12V (1A) — for Arduino Nano, relay and motor |
| **Production** | Factory manufacturing |

---

## Filter Chokes

### OSM-0.036 (2 pcs)

| Parameter | Value |
|-----------|-------|
| **Core** | ШL 16×25 (OSM-0.036) |
| **Iron Cross-Section** | ~4.0 cm² |
| **Inductance (L)** | 5.0 — 8.0 H (under load) |
| **Max Current (Imax)** | 0.2 A (200 mA) — margin for G-807 |
| **Resistance (R)** | ~120–150 Ohm |
| **Wire (copper)** | 0.22 — 0.25 mm (PETV-2) |
| **Turns** | 3500 (to fill window) |
| **Non-magnetic Gap** | 0.1 mm (one layer of office paper) |
| **Production** | Factory manufacturing |

---

## Winding Data (For DIY)

### TVZ on OSM-0.063

```
Primary Winding:
  - Wire: PETV-2 0.18–0.2 mm
  - Turns: 3600
  - Sections: 3P+2S (P-S-P-S-P)
  - Resistance: ~150 Ohm

Secondary Winding:
  - Wire: PETV-2 0.5 mm (2 strands)
  - Turns: 118 (for 8 Ohm)
  - Sections: 2 parallel

Insulation:
  - Inter-section: Lacquer cloth 0.1 mm
  - Inter-winding: 3 layers paper
  - Impregnation: Paraffin + beeswax
```

### TS on OSM-0.16

```
Anode Winding:
  - Wire: PETV-2 0.25 mm
  - Turns: 2 × 1100 (260V)
  - Current: 0.25A

Filament Winding:
  - Wire: PETV-2 0.8 mm
  - Turns: 24 (6.3V)
  - Current: 4A

Bias Winding:
  - Wire: PETV-2 0.15 mm
  - Turns: 200 (50V)
  - Current: 0.1A

Service Winding:
  - Wire: PETV-2 0.4 mm
  - Turns: 48 (12V)
  - Current: 1A
```

### Choke on OSM-0.036

```
Winding:
  - Wire: PETV-2 0.22–0.25 mm
  - Turns: 3500
  - Gap: 0.1 mm (office paper)
  - Inductance: 5–8 H at 200 mA
```

---

## Materials

### Cores

| Type | Material | Permeability |
|------|----------|--------------|
| **OSM-0.036** | Steel E310 | μ ~ 2000 |
| **OSM-0.063** | Steel E310 | μ ~ 2000 |
| **OSM-0.16** | Steel E310 | μ ~ 2000 |

### Wires

- **PETV-2** — Polyetherimide enamel, heat class F (155°C)
- **Copper** — Oxygen-free, 99.99%

### Insulation

- **Lacquer cloth** — 0.1 mm, class F
- **Paper** — Capacitor grade, 0.02 mm
- **Impregnation** — Paraffin + beeswax (1:1)

---

## Measurements

### TVZ Frequency Response (OSM-0.063)

```
25 Hz  : -1 dB
100 Hz : 0 dB (reference)
1 kHz  : 0 dB
10 kHz : -0.5 dB
40 kHz : -1 dB
```

### Phase Response

```
20 Hz  : +5°
1 kHz  : 0°
20 kHz : -3°
```

---

## Kit Contents

<div class="rom-mission" style="margin-top: 1rem;">
    <p class="rom-mission-text">
        <strong>Factory components:</strong> transformers (TVZ OSM-0.063, TS OSM-0.16), chokes (OSM-0.036), enclosures, pre-assembled PCBs.
    </p>
    <p class="rom-mission-text" style="margin-top: 1rem;">
        For enthusiasts: we publish specifications for DIY transformer and choke fabrication at home.
    </p>
</div>

---

[← Back to Malysh](index.md)
