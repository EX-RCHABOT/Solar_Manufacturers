

# Step 1 — Define Project consumption”

For **new-construction multifamily in California**, a very typical planning assumption is:

* **6–10 kWh/day per unit** (efficient new build, no electric heating)
* Peak demand per unit (non-HVAC): **1.5–2.5 kW**
* Diversity factor applies (not all units peak at once)

### Conservative but realistic baseline

Let’s model **8 kWh/day per unit**:

```
21 units × 8 kWh/day ≈ 168 kWh/day
```

This is a **very reasonable target** for:

* Evening load shifting
* Partial overnight backup
* Title 24 + resilience justification

---

# Step 2 — Decide what the battery is doing

There are three common interpretations of “21 units consumption”:

## Scenario A — Daily energy offset / load shifting

* Battery supplies ~1 full day of energy
* No guarantee of long-duration outage coverage

👉 **~170–200 kWh usable**

## Scenario B — Essential-load backup (4–6 hours)

* Battery covers evening peak or outage window
* HVAC usually excluded

👉 **200–300 kWh usable**

## Scenario C — Aggressive resilience / ITC-maximizing

* Battery supports:

  * Full evening + partial overnight
  * PV smoothing
  * Future EV / DR participation

👉 **300–500 kWh usable**

---

# Step 3 — Power rating matters as much as kWh

Battery sizing is **two-dimensional**:

| Parameter    | Typical Need |
| ------------ | ------------ |
| Energy (kWh) | 200–500      |
| Power (kW)   | 100–250      |

### Rule of thumb

* **1 kW per 3–5 units** for diversified residential load
* 21 units → **100–150 kW PCS** is a solid starting point

This avoids nuisance load shedding and keeps AHJs comfortable.

---

# Step 4 — What battery sizes actually make sense

## 🔹 Option 1 — 200 kWh Commercial Cabinet

* Covers ~1 day of modeled consumption
* Clean Title 24 + ITC story
* Minimal fire footprint

**Good for:** baseline compliance + modest resilience

---

## 🔹 Option 2 — 300–350 kWh Skid BESS (⭐ SWEET SPOT)

* Covers:

  * Full evening peak
  * Partial overnight
  * Some outage margin
* PCS: ~150 kW
* Very strong ITC justification

**Good for:**
✔ Multiple units consumption
✔ Fire-friendly
✔ Owner value
✔ ITC optimization

---

## 🔹 Option 3 — 500 kWh Skid BESS

* Covers:

  * Full evening + overnight
  * PV curtailment avoidance
  * Future EV / DR programs
* PCS: 200–250 kW

**Good for:** long-term asset strategy
⚠ Requires more siting discipline

---

# Step 5 — What this means for ITC capture

Using **rough-order installed costs** (varies by vendor):

| Size    | Approx. Installed Cost | 30% ITC     |
| ------- | ---------------------- | ----------- |
| 200 kWh | $180k–$240k            | $54k–$72k   |
| 300 kWh | $250k–$330k            | $75k–$99k   |
| 500 kWh | $400k–$550k            | $120k–$165k |

💡 **The jump from 200 → 300 kWh often pays for itself in tax value + operational flexibility.**

---

# Step 6 — Compatible battery form factor.

For this size range, **residential-class batteries are no longer ideal**.

### Recommended architecture

* **Single commercial cabinet or skid**
* Exterior pad or dedicated utility area
* One emergency stop
* One placard set
* One PCS

This is exactly the size range where AHJs usually say:

> “Yes — this is clearly a commercial energy system.”

---

# Step 7 — 

> **Design around a 300–350 kWh commercial skid-mounted BESS with ~150 kW PCS**, structured as a **standalone storage asset** for ITC purposes.

* Clean Title 24 compliance
* Strong ITC capture
* Fire-review-friendly layout
* Real resilience value
* Future expandability

---
# Next Steps:
1. **Lock assumptions** (kWh/unit, peak load)
2. Match **specific manufacturer SKUs** to 300–350 kWh
3. Generate a **one-line diagram**
4. Draft **proposal language** explaining the 21-unit logic
5. Flag **fire setback envelopes** for each size
6. Produce an **Option A (200 kWh)** vs **Option B (300 kWh ITC-optimized)** table

Perfect — let’s put this into a **clear, decision-grade side-by-side comparison** and link directly to **manufacturer resources** so your team (and the AHJ / owner) can verify everything themselves.

I’ll focus on **battery solutions that are realistically compatible with a multi-unit commercial PV + ESS project in LA**, and that align with what we discussed: **Title 24 compliance, fire approval, and optional whole-building backup**.

---

# Commercial ESS Comparison – PV + Multi-Unit Projects

## Quick Legend

* ✅ = Strong fit
* ⚠️ = Possible, but with caveats
* ❌ = Not recommended

---

## 1️⃣ Tesla Powerwall 3 (Residential-Class ESS)

| Category              | Details                                      |
| --------------------- | -------------------------------------------- |
| Manufacturer          | **Tesla**                                    |
| Product               | Powerwall 3                                  |
| Intended Market       | Residential / Light commercial               |
| Typical Capacity      | ~13.5 kWh per unit                           |
| Voltage               | 120/240V                                     |
| Installation          | Wall-mounted                                 |
| UL Listing            | UL 9540                                      |
| Fire Testing          | UL 9540A (cell/module level)                 |
| Expandability         | Limited (multiple units required)            |
| Best Use Case         | Title 24 minimum compliance                  |
| Whole-Building Backup | ❌                                            |
| AHJ Friendliness      | ⚠️ (depends heavily on layout & aggregation) |

### Pros

* Widely recognized
* Simple installation
* Integrated inverter
* Good for **code-minimum storage**

### Cons

* Residential architecture
* Aggregation causes fire/layout complexity
* Not ideal for centralized shutdown
* Limited commercial documentation depth

### Manufacturer Resources

* Product page:
  👉 [https://www.tesla.com/powerwall](https://www.tesla.com/powerwall)
* Specifications & manuals:
  👉 [https://www.tesla.com/support/energy/powerwall/installer-resources](https://www.tesla.com/support/energy/powerwall/installer-resources)

---

## 2️⃣ BYD Battery-Box Commercial (Cabinetized ESS)

| Category              | Details                        |
| --------------------- | ------------------------------ |
| Manufacturer          | **BYD**                        |
| Product               | Battery-Box Commercial         |
| Intended Market       | Commercial / Industrial        |
| Typical Capacity      | ~50–500+ kWh                   |
| Voltage               | 208V / 480V (with PCS)         |
| Installation          | Indoor or outdoor cabinet      |
| UL Listing            | UL 9540                        |
| Fire Testing          | UL 9540A                       |
| Expandability         | Modular                        |
| Best Use Case         | Essential loads / common areas |
| Whole-Building Backup | ⚠️ (load-shed dependent)       |
| AHJ Friendliness      | ✅                              |

### Pros

* Purpose-built for C&I
* Modular cabinet design
* Strong fire documentation
* Cleaner shutdown strategy

### Cons

* Requires external PCS/inverter
* Slightly longer procurement lead time

### Manufacturer Resources

* Commercial ESS overview:
  👉 [https://www.byd.com/us/energy-storage](https://www.byd.com/us/energy-storage)
* Battery-Box documentation:
  👉 [https://www.bydbatterybox.com/](https://www.bydbatterybox.com/)

---

## 3️⃣ LG Energy Solution – Commercial ESS

| Category              | Details                               |
| --------------------- | ------------------------------------- |
| Manufacturer          | **LG Energy Solution**                |
| Product               | Commercial ESS (rack/cabinet systems) |
| Intended Market       | Commercial / Utility                  |
| Typical Capacity      | ~100–600+ kWh                         |
| Voltage               | 208V / 480V                           |
| Installation          | Indoor / Outdoor                      |
| UL Listing            | UL 9540                               |
| Fire Testing          | UL 9540A                              |
| Expandability         | High                                  |
| Best Use Case         | Essential or partial building backup  |
| Whole-Building Backup | ⚠️                                    |
| AHJ Friendliness      | ✅                                     |

### Pros

* Strong brand trust
* Robust safety documentation
* Flexible configurations
* Widely accepted by utilities & AHJs

### Cons

* Requires careful integrator coordination
* Typically higher cost than residential ESS

### Manufacturer Resources

* Commercial ESS page:
  👉 [https://www.lgensol.com/ess](https://www.lgensol.com/ess)
* Technical documentation:
  👉 [https://www.lgensol.com/ess/download](https://www.lgensol.com/ess/download)

---

## 4️⃣ Schneider Electric – Commercial BESS + PCS

| Category              | Details                            |
| --------------------- | ---------------------------------- |
| Manufacturer          | **Schneider Electric**             |
| Product               | EcoStruxure / BESS Solutions       |
| Intended Market       | Commercial / Industrial            |
| Typical Capacity      | ~100 kWh to multi-MWh              |
| Voltage               | 208V / 480V                        |
| Installation          | Cabinetized / Skid                 |
| UL Listing            | UL 9540                            |
| Fire Testing          | UL 9540A                           |
| Expandability         | Excellent                          |
| Best Use Case         | Essential or whole-building backup |
| Whole-Building Backup | ✅                                  |
| AHJ Friendliness      | ✅                                  |

### Pros

* Integrated electrical + controls ecosystem
* Excellent documentation
* Strong fire/utility coordination
* Future-proof controls

### Cons

* Higher engineering involvement
* Premium pricing

### Manufacturer Resources

* Commercial storage overview:
  👉 [https://www.se.com/us/en/work/solutions/for-business/energy-storage/](https://www.se.com/us/en/work/solutions/for-business/energy-storage/)
* EcoStruxure ESS:
  👉 [https://www.se.com/us/en/product-range/62025-ecostruxure-energy-storage/](https://www.se.com/us/en/product-range/62025-ecostruxure-energy-storage/)

---

## 5️⃣ Fluence – Modular / Skid-Mounted BESS

| Category              | Details                                 |
| --------------------- | --------------------------------------- |
| Manufacturer          | **Fluence**                             |
| Product               | Modular / Gridstack-derived C&I systems |
| Intended Market       | Commercial / Utility                    |
| Typical Capacity      | 250 kWh → multi-MWh                     |
| Voltage               | Medium / Low voltage options            |
| Installation          | Skid or container                       |
| UL Listing            | UL 9540                                 |
| Fire Testing          | UL 9540A                                |
| Expandability         | Excellent                               |
| Best Use Case         | Whole-building backup                   |
| Whole-Building Backup | ✅                                       |
| AHJ Friendliness      | ✅ (with proper siting)                  |

### Pros

* Utility-grade safety design
* Excellent fire documentation
* Clear emergency shutdown
* Designed for AHJ scrutiny

### Cons

* Space requirements
* Longer permitting timeline
* Overkill for T24-only needs

### Manufacturer Resources

* Commercial & grid ESS:
  👉 [https://fluenceenergy.com/solutions/](https://fluenceenergy.com/solutions/)
* Safety & compliance info:
  👉 [https://fluenceenergy.com/safety/](https://fluenceenergy.com/safety/)

---

# Summary Recommendation Matrix

| Goal                   | Best Fit                   |
| ---------------------- | -------------------------- |
| Title 24 only          | Tesla Powerwall 3 ⚠️       |
| Essential loads backup | BYD / LG / Schneider ✅     |
| Whole-building backup  | Schneider / Fluence ✅      |
| Simplest fire approval | Cabinetized commercial ESS |
| Long-term scalability  | Skid-mounted BESS          |

---

## My Professional Take (Straight Talk)

* **Powerwall 3** is acceptable for **minimum compliance**, but not ideal as a central solution.
* **Commercial cabinetized systems** (BYD, LG, Schneider) are the **sweet spot** for most multi-unit projects.
* **Fluence-class systems** are best when resilience and future grid participation matter.

---


