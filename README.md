# Electric Go-Kart Build Guide

*Compiled for Hunter — Summer 2026 Project*
*Budget: $1,500-2,000*

---

## Overview

**Goals:** Go, brake, steer well, with differential, headlights, suspension, windscreen, decent speed

**Target Specs:**
- Top speed: 30-45 mph (adjustable via controller)
- Range: 15-25 miles depending on battery choice
- Weight capacity: ~250-300 lbs driver + kart
- Charging: 4-6 hours on standard outlet

---

## Bill of Materials

### 1. FRAME/CHASSIS — $200-400

**Option A: Buy a used gas kart frame (RECOMMENDED)**
- Craigslist/Facebook Marketplace: $100-200
- Already has steering, axle mounts, seat mounts
- Just need to remove gas engine, adapt for electric

**Option B: DIY Steel Tube Frame**
- 1" x 0.095" wall mild steel tubing: ~$100
- Bender rental or buy: $50-100
- Welding (if you don't have a welder): borrow/rent
- Plans available free online (search "go kart frame plans PDF")

**Option C: Frame Kit**
- Azusa Engineering frame kit: ~$300-400
- BMI Karts frame kit: ~$250-350

**Recommendation:** Find a used racing kart or off-road buggy frame. They're overbuilt for gas engines and perfect for electric conversion.

---

### 2. MOTOR — $150-350

**Best Value Options:**

| Motor | Power | Voltage | Price | Notes |
|-------|-------|---------|-------|-------|
| MY1020 BLDC | 1000-3000W | 48-72V | $65-120 | Most popular DIY choice |
| QS 138 (70H) | 3000W cont. | 48-72V | $250-300 | Higher quality, more torque |
| Kunray 72V | 3000-5000W | 72V | $200-250 | Good mid-range option |

**Recommendation:** Start with a **48V 2000-3000W MY1020 brushless DC motor** (~$80-100 on AliExpress/Amazon). Plenty of power for a go-kart, reliable, tons of documentation online.

If you want more speed/torque, the **QS138 70H mid-drive** (~$300) is the enthusiast favorite.

---

### 3. MOTOR CONTROLLER — $80-200

The controller must match your motor (voltage, wattage, brushless vs brushed).

**Options:**

| Controller | Amps | Voltage | Price | Notes |
|------------|------|---------|-------|-------|
| Generic 48V BLDC | 45-60A | 48V | $50-80 | Works with MY1020 |
| Sabvoton 72100 | 100A | 48-72V | $150-180 | Programmable, regen braking |
| Kelly KLS7230S | 100A | 24-72V | $180-220 | Quality brand, programmable |
| Votol EM-150 | 150A | 48-96V | $200-250 | Excellent, common in DIY EV |

**Recommendation:** **Kelly or Votol controller** — programmable, supports regen braking, adjustable top speed. Worth the extra $50-100 for safety and tunability.

---

### 4. BATTERIES — $400-800

**This is where you decide speed vs. budget.**

**Chemistry Options:**
- **LiFePO4 (LFP):** Safest, longest life (2000+ cycles), heavier, ~$400-600
- **Li-ion (NMC/18650):** Lighter, more energy dense, 500-1000 cycles, ~$300-500
- **Lead Acid:** Cheapest upfront (~$150), heavy, short life, NOT recommended

**Recommended Configurations:**

| Config | Voltage | Capacity | Weight | Range | Price | Speed |
|--------|---------|----------|--------|-------|-------|-------|
| 48V 20Ah LiFePO4 | 48V | 960Wh | ~15 lbs | 15-20 mi | $350-450 | 25-30 mph |
| 60V 20Ah LiFePO4 | 60V | 1200Wh | ~18 lbs | 18-25 mi | $450-550 | 30-35 mph |
| 72V 20Ah LiFePO4 | 72V | 1440Wh | ~22 lbs | 20-30 mi | $550-700 | 35-45 mph |
| 48V 20Ah Li-ion | 48V | 960Wh | ~10 lbs | 15-20 mi | $250-350 | 25-30 mph |

**Where to Buy:**
- Unit Pack Power (AliExpress/Amazon) — good budget LiFePO4
- EM3ev — quality ebike batteries, work great for karts
- DIY: Buy cells + spot welder + BMS (advanced, saves ~30%)

**Recommendation:** **48V or 60V 20Ah LiFePO4** — safest, good balance of range/speed/cost. Get one with built-in BMS (battery management system).

---

### 5. THROTTLE — $15-40

**Options:**
- **Foot pedal throttle (hall effect):** $25-40 — feels like a real car
- **Twist throttle:** $10-20 — motorcycle style
- **Thumb throttle:** $10-15

**Recommendation:** **Foot pedal throttle** — more intuitive, keeps hands free for steering. Search "electric go kart foot throttle hall effect."

---

### 6. BRAKES — $80-150

**Disc brakes are essential at these speeds.**

**Rear Axle Brake Setup:**
- Hydraulic disc brake caliper: $30-50
- Brake rotor (mount to axle or wheel hub): $20-30
- Master cylinder (foot operated): $25-40
- Brake lines + fluid: $15-20

**Front Brakes (optional but recommended):**
- Add hydraulic disc to front wheels: +$60-100

**Recommendation:** At minimum, **hydraulic disc brake on rear axle**. For better stopping, add front discs. Go-kart racing suppliers (BMI Karts, Comet Kart Sales) have complete kits.

---

### 7. STEERING — $60-120

If using a kart frame, steering is included. For DIY:

- Steering wheel: $20-30
- Steering shaft + column: $25-40
- Tie rods + ends: $20-30
- Spindles (if not on frame): $40-60

**Recommendation:** Buy a used kart with steering intact. Modifying steering geometry is tricky and safety-critical.

---

### 8. REAR AXLE + DIFFERENTIAL — $100-250

**Options:**

| Type | Pros | Cons | Price |
|------|------|------|-------|
| **Live axle (solid)** | Simple, cheap, strong | Both wheels same speed (tire scrub in turns) | $50-80 |
| **Live axle + spool** | Slightly better | Still locks both wheels | $70-100 |
| **Differential axle** | Proper cornering, less tire wear | More complex, heavier | $150-250 |

**Recommendation for "steer well":** Get a **go-kart differential axle assembly** (~$150-200). Search "go kart rear end differential" on Amazon or BMI Karts. 

For budget builds, a live axle works—racing karts use them—but you'll feel it in tight turns.

---

### 9. WHEELS + TIRES — $80-160

**Typical go-kart sizes:** 
- Front: 10x4.50-5 or 11x6.0-5
- Rear: 11x7.10-5 or similar

**Options:**
- Go-kart racing wheels + slicks: $150-200/set (overkill)
- Off-road/dune buggy wheels: $80-120/set
- ATV wheels (if larger build): $100-150/set

**Recommendation:** Search "go kart wheels and tires" — you can get a full set (4 wheels + tires + bearings) for **$80-120**.

---

### 10. SUSPENSION — $100-250

**Most karts have NO suspension** (solid frame). For comfort:

**Options:**

| Type | Price | Notes |
|------|-------|-------|
| Padded seat | $30-50 | Simplest "suspension" |
| Rear shock (single) | $40-80 | ATV/motorcycle shock, mount to frame |
| Front A-arms + shocks | $100-150 | More complex, requires frame design |
| Full coilover setup | $200-400 | For serious off-road use |

**Recommendation:** For a summer project, go with a **padded racing seat** + **single rear shock mounted to a swing arm**. Full suspension is possible but adds complexity.

---

### 11. ELECTRICAL ACCESSORIES — $50-100

| Item | Price |
|------|-------|
| Kill switch / key switch | $10-15 |
| Main contactor (for safety) | $20-30 |
| Fuse holder + fuse (match battery amps) | $10-15 |
| 12V DC-DC converter (for lights) | $15-25 |
| Headlights (LED) | $15-30 |
| Wiring, connectors, terminals | $20-30 |

**Don't skip the contactor** — it's a safety relay that cuts power. Essential.

---

### 12. WINDSCREEN — $30-60

- Lexan/polycarbonate sheet, bend with heat gun: $20-30
- Pre-made go-kart/UTV windscreen: $40-60

---

### 13. CHARGER — $50-100

Must match your battery voltage/chemistry.

- 48V LiFePO4 charger (5A): $40-60
- 60V LiFePO4 charger (5A): $50-70
- 72V LiFePO4 charger (5A): $60-80

**Get at least 5A** for reasonable charge times. 10A charges faster but costs more.

---

## Budget Summary

### Budget Build (~$1,200-1,400)
| Component | Price |
|-----------|-------|
| Used kart frame | $150 |
| MY1020 3000W motor | $100 |
| Generic 48V controller | $70 |
| 48V 20Ah LiFePO4 battery | $400 |
| Foot throttle | $30 |
| Hydraulic disc brake | $80 |
| Live axle (no diff) | $60 |
| Wheels + tires | $100 |
| Seat | $40 |
| Electrical (switches, wiring) | $50 |
| Headlights | $25 |
| Charger | $50 |
| Windscreen | $30 |
| **TOTAL** | **~$1,185** |

### Mid-Range Build (~$1,600-1,800)
| Component | Price |
|-----------|-------|
| Used kart frame | $150 |
| QS138 3000W motor | $280 |
| Kelly/Votol controller | $180 |
| 60V 20Ah LiFePO4 battery | $500 |
| Foot throttle | $35 |
| Front + rear disc brakes | $140 |
| Differential axle | $180 |
| Wheels + tires | $100 |
| Seat + rear shock | $80 |
| Electrical (switches, contactor) | $70 |
| LED headlights | $30 |
| Charger | $60 |
| Windscreen | $40 |
| **TOTAL** | **~$1,845** |

### Performance Build (~$2,000-2,400)
| Component | Price |
|-----------|-------|
| Quality frame or custom build | $300 |
| QS138 90H 4000W motor | $350 |
| Sabvoton/Kelly programmable controller | $220 |
| 72V 25Ah LiFePO4 battery | $700 |
| Everything else upgraded | $500 |
| **TOTAL** | **~$2,070+** |

---

## Build Sequence

### Phase 1: Frame & Drivetrain (Week 1-2)
1. Acquire frame (or build)
2. Mount motor to frame with adapter plate
3. Install rear axle/differential
4. Connect motor to axle (chain/belt + sprockets)
5. Test spin motor (temporarily wire battery + controller)

### Phase 2: Steering & Brakes (Week 2-3)
1. Install/verify steering geometry
2. Mount brake caliper to axle/hub
3. Install master cylinder, run brake lines
4. Mount wheels, check alignment

### Phase 3: Electrical (Week 3-4)
1. Mount battery securely (low, centered)
2. Wire: Battery → Fuse → Contactor → Controller → Motor
3. Install throttle, wire to controller
4. Install kill switch in easy reach
5. Test drive slowly in safe area!

### Phase 4: Finishing (Week 4-5)
1. Install DC-DC converter for 12V accessories
2. Wire headlights
3. Mount windscreen
4. Add seat, any suspension
5. Safety check everything, tune controller

---

## Where to Buy

### Frames & Parts
- **Craigslist/FB Marketplace** — used karts, best deals
- **BMI Karts** (bmikarts.com) — huge selection
- **Comet Kart Sales** (cometkartsales.com)
- **Northern Tool** — axles, wheels, hardware

### Motors & Controllers
- **AliExpress** — MY1020, QS motors, controllers (allow 2-4 weeks shipping)
- **Amazon** — faster shipping, slight markup
- **QS Motor direct** (qsmotor.com)
- **Kelly Controller** (kellycontroller.com)

### Batteries
- **AliExpress** — Unit Pack Power, other brands
- **Amazon** — faster but check reviews carefully
- **EM3ev** (em3ev.com) — quality ebike batteries
- **DIY** — 18650batterystore.com + spot welder

### Electrical
- **Amazon** — contactors, switches, connectors
- **ElectricalScooterParts.com** — throttles, wiring
- **Local auto parts store** — brake parts, wiring

---

## Safety Notes

⚠️ **MUST HAVES:**
- Kill switch within arm's reach
- Fuse rated for your battery (e.g., 60A for 48V 3000W)
- Contactor (power relay) between battery and controller
- Properly secured battery (can't shift in crash)
- Full coverage on electrical connections (no exposed terminals)
- Brake test before every ride

⚠️ **NICE TO HAVE:**
- Roll bar (especially at higher speeds)
- Seat belt or harness
- Helmet (always!)
- Fire extinguisher nearby when charging

---

## Performance Tuning

Most programmable controllers let you adjust:
- **Max speed** — limit for learning/safety
- **Acceleration curve** — gentle or aggressive
- **Regen braking strength** — charges battery when braking
- **Current limit** — protects motor/battery

Start conservative, increase as you get comfortable!

---

## Resources

- **Endless Sphere Forums** (endless-sphere.com) — huge EV DIY community
- **YouTube: "DIY electric go kart"** — tons of build videos
- **r/ebikes** and **r/ElectricVehicles** — Reddit communities
- **OpenPPG** — electric paramotor community (similar motors/batteries)

---

*Good luck with the build! This is gonna be fun. 🏎️⚡*

*— Ren*
