# Project Archaeopteryx: Bill of Materials (BOM)

Total system cost: **454.49 CHF** across 31 line items.

| Subsystem | Component | Qty | Unit (CHF) | Total (CHF) | Operational Purpose |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Flight Controller** | CoreWing F405 WING V2 | 1 | 50.61 | 50.61 | STM32F405 central processor, PDB, sensor fusion |
| **Navigation** | Beitian BN-880 GPS + Compass | 1 | 21.99 | 21.99 | L1 GNSS receiver and QMC5883L magnetic heading |
| **Ground Proximity** | Benewake TF-Luna LiDAR | 1 | 17.09 | 17.09 | AGL distance ranging for flare and terrain follow |
| **Airspeed Sensor** | Px4 Differential Pitot (MS4525DO) | 1 | 20.79 | 27.79 | Dynamic pressure sensing to compute $v_{\text{IAS}}$ |
| **Telemetry Link** | 3DR Radio Telemetry (433MHz 500mW) | 1 | 39.19 | 39.19 | Bidirectional long-range MAVLink ground telemetry |
| **RC Receiver** | HappyModel 2.4G ELRS EP1 TCXO Dual | 1 | 12.56 | 12.56 | Low-latency CRSF command uplink |
| **RC Transmitter** | RadioMaster Pocket Hall (ELRS M2LBT) | 1 | 63.19 | 63.19 | Handheld ground station controller |
| **Radio Power** | LiitoKala 35E 18650 Batteries (2 pcs) | 1 | 15.06 | 15.06 | Power cell for RadioMaster Pocket |
| **Motors** | 2212 1250KV Brushless Motor | 2 | 10.56 | 21.12 | Twin tractor propulsion configuration |
| **ESCs** | Hobbywing Skywalker V2 30A | 2 | 15.49 | 30.98 | Motor commutation and power delivery |
| **Propellers** | Gemfan Carbon Fiber Nylon | 3 | 3.12 | 9.36 | High-rigidity cruise propellers |
| **Flight Battery** | HRB 3300mAh LiPo (4S 60C) | 1 | 28.19 | 28.19 | High-discharge primary flight energy storage |
| **Battery Charger**| PD60 LiPo Charger | 1 | 17.17 | 17.17 | Field and bench DC battery charger |
| **Actuators** | MG90S All-Metal Gear 9g Servos | 1 | 8.53 | 8.53 | Control surface deflection (Ailerons, Elev, Rud) |
| **Airframe Spar** | Carbon Fiber Tube (8x6x500mm) | 2 | 5.03 | 10.06 | Main structural bending and torsion resistance |
| **Control Horns** | Nylon Control Yoke & Clevis (10 sets)| 1 | 1.99 | 1.99 | Surface-to-linkage mechanical connection |
| **Pushrods** | Z-type Steel Wire (200mm x 1.2mm) | 1 | 2.79 | 2.79 | Push/pull force transmission |
| **Linkage Stops** | Linkage Stopper / Servo Connectors | 1 | 3.01 | 3.01 | Mechanical zero-slop pushrod adjusters |
| **Hinges** | White Nylon Pinned Hinges (20 pcs) | 1 | 2.32 | 2.32 | Low-friction control surface pivots |
| **Hardware** | M3 x L5 x OD4 Brass Inserts (50pcs) | 1 | 2.69 | 2.69 | Heat-set structural chassis fastening |
| **Fasteners** | ISO 7380 M3 Button Head Screws | 1 | 8.31 | 8.31 | Mechanical assembly screws |
| **Wiring (Power)** | 14 AWG Silicone Cable (2m R / 2m B) | 2 | 2.95 | 5.90 | Low-resistance high-current ESC/battery leads |
| **Wiring (Signal)**| 24 AWG 2-pin Silicone Cable (5m) | 1 | 1.19 | 1.19 | Serial, I2C, and servo extensions |
| **Connectors** | XT60H Male/Female Connectors (5pcs)| 1 | 2.36 | 2.36 | Main power disconnect plugs |
| **Motor Plugs** | 3.5mm Banana Bullet Connectors (5 pr)| 2 | 1.92 | 3.80 | Quick-disconnect phase leads for motors |
| **Audio Alert** | 5V Active Piezo Buzzer (10pcs) | 1 | 1.58 | 1.58 | Arming tones and low-voltage fail-safe beacon |
| **Dampening** | Black M3 Rubber Vibration Dampers | 1 | 1.51 | 1.51 | IMU mechanical isolation mount |
| **Adhesives/Tape**| 3M 4229P VHB Tape + 502 CA Glue | 2 | -- | 7.96 | Structural bonding and component mounting |
| **Fastening** | Hook & Loop Battery Straps (5pcs) | 1 | 5.31 | 5.31 | Pack retention inside fuselage |
| **Bench Tools** | NC-559 Flux, Screwdrivers, Shrink | 3 | -- | 10.27 | Electronics assembly and insulation |
| **Data Logging** | 64GB SanDisk Ultra MicroSD | 1 | 0.00 | 0.00 | Onboard high-rate flight dynamics logging |
| **TOTAL** | | | | **454.49** | |
