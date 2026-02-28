# Iron

<div class="rom-hero">
    <h1 class="rom-hero-title">Transformers and Chokes</h1>
    <p class="rom-hero-subtitle">The Heart of Analog Path</p>
</div>

---

## Output Transformers (TVZ)

### Production: OSM-0.16 (Factory Made)

| Parameter | Value |
|-----------|-------|
| **Base Core** | OSM-0.16 (cut tape core, type ШL 32×40) |
| **Steel Material** | Cold-rolled electrical steel (grade 3407 or 3408) |
| **Construction** | Custom design for Push-Pull, steel shield ("pot") |
| **Technology** | Sectionalized winding (3P + 2S), vacuum lacquer impregnation |
| **Frequency Range** | 15 Hz — 45,000 Hz (at -1 dB irregularity) |
| **Features** | Individual Ia/Vg passport for each transformer pair |
| **Production** | Factory winding, quality control |

---

## Power Transformer

### OSM-0.4 (Factory Made)

| Parameter | Value |
|-----------|-------|
| **Base Platform** | OSM-0.4 (Magnetic Core ШL 40×50) |
| **Rated Power** | 400 W (4x power margin) |
| **Construction Type** | Core type, individual magnetic shield |
| **Winding Configuration** | Dual Mono High-Voltage: 2 × 280-300V (Anode L/R) |
| **Filament** | 3 × 6.3V (Separate heater for driver and output tubes) |
| **Logic** | 1 × 12V (Controller and automation power) |
| **Features** | Vacuum lacquer impregnation, anti-vibration mounting |
| **Production** | Factory manufacturing |

---

## Filter Chokes

### OSM-0.063 (2 pcs)

| Parameter | Value |
|-----------|-------|
| **Type** | OSM-0.063 |
| **Inductance** | 5–10 H (depending on gap) |
| **Current** | Up to 200 mA |
| **Mounting** | On top panel, in caps |
| **Quantity** | 2 pcs (separate per channel) |

---

## Winding Data (For DIY)

### TVZ on OSM-0.16

```
Primary Winding:
  - Wire: PETV-2 0.25 mm
  - Turns: 5000
  - Sections: 3P+2S (alternating)
  - Resistance: ~180 Ohm

Secondary Winding:
  - Wire: PETV-2 0.8 mm
  - Turns: 120 (4 Ohm tap), 170 (8 Ohm tap)
  - Sections: 2 parallel

Insulation:
  - Inter-section: Lacquer cloth 0.1 mm
  - Inter-winding: 3 layers paper
  - Impregnation: Paraffin + beeswax
```

### Choke OSM-0.063

```
Winding:
  - Wire: PETV-2 0.35 mm
  - Turns: 2000
  - Gap: 0.1 mm (textolite)
  - Inductance: ~8 H at 100 mA
```

---

## Materials

### Cores

| Type | Material | Permeability |
|------|----------|--------------|
| **OSM** | Steel E310 | μ ~ 2000 |

### Wires

- **PETV-2** — Polyetherimide enamel, heat class F (155°C)
- **Copper** — Oxygen-free, 99.99%

### Insulation

- **Lacquer cloth** — 0.1 mm, class F
- **Paper** — Capacitor grade, 0.02 mm
- **Impregnation** — Paraffin + beeswax (1:1)

---

## Measurements

### TVZ Frequency Response

```
15 Hz  : -1 dB
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
        <strong>Factory components:</strong> OSM transformers, enclosures, pre-assembled PCBs.
    </p>
    <p class="rom-mission-text" style="margin-top: 1rem;">
        For enthusiasts: we publish specifications for DIY transformer 
        and enclosure fabrication at home.
    </p>
</div>

---

[← Back to Malysh](index.md)
