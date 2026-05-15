<!-- Header -->
<div align="center">
## Abhishek Kedage

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f2e,100:0f4c75&height=200&section=header&text=Abhishek%20Kedage&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Controls%20%7C%20Electrified%20Powertrains%20%7C%20Mathematical%20Modelling&descAlignY=58&descColor=88c0d0" />
M.S. Automotive Engineering · Clemson University · GPA 4.0/4.0

Controls · Electrified Powertrains · Thermal Systems · Mathematical Modelling

</div>
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://linkedin.com/in/YOUR_LINKEDIN)
[![Email](https://img.shields.io/badge/Email-kedageabhishek%40outlook.com-grey?style=flat&logo=gmail)](mailto:kedageabhishek@outlook.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-abhishekkedage.github.io-0f4c75?style=flat)](https://YOUR_GITHUB_USERNAME.github.io)

---

## 👋 About Me
2 years industry (Earthsense Inc.) · 3.5 years Formula SAE Technical Lead · Research Assistant, Stellantis/DOE Battery Workforce Challenge

```yaml
name       : Abhishek Kedage
degree     : M.S. Automotive Engineering @ Clemson University (GPA: 4.0/4.0)
location   : Greenville, SC, USA
available  : Summer 2026 (June 1 start) through Fall 2026
seeking    : Internships — Powertrain Controls | BMS | Thermal Systems | Vehicle Dynamics
focus      : Electrified Powertrains · BMS Algorithms · Thermal Management · Model-Based Controls
```

Graduate researcher at **Clemson University (CU-ICAR)** with 2 years of industry experience at **Earthsense Inc.** and 3.5 years leading powertrain and thermal subsystems at **Formula SAE** (Team Octane Racing Electric — 2nd place nationally). I work at the intersection of battery state estimation, thermal controls, and vehicle dynamics — designing and validating systems from the governing equations up.

---

## 🔧 Technical Skills

<div align="center">

| Domain | Tools & Technologies |
|---|---|
| **Controls** | MPC · PID · Kalman Filter (EKF) · Fuzzy Logic · Stateflow · State-space modeling |
| **Simulation & Modelling** | MATLAB · Simulink · Simscape · Stateflow · Scilab · CarSim |
| **BMS Algorithms** | SOC estimation (EKF) · SOP estimation (Thevenin) · CC-CV charging control |
| **Thermal Systems** | Battery thermal management · Motor cooling · Heat exchanger design · CFD (ANSYS Fluent) |
| **CAD & CAE** | CATIA V5 · SolidWorks · Creo · Fusion 360 · Siemens NX · Ansys |
| **Programming** | MATLAB/Simulink (primary) · Python · C++ (Arduino) · Shell · YAML · Docker |
| **Methods** | HPPC testing · BSFC mapping · NTU method · Thermal resistance networks · Git |

</div>
Available for Summer 2026 internships (June 1) in the USA.

---

## 🚀 Featured Projects

### 🔄 [4WID-MPC Vehicle Stability Control](./4wid-mpc-stability-control)
> `MATLAB` `Simulink` `CarSim` `Fuzzy Logic` `MPC` `Stateflow`
### Projects

Hierarchical stability controller for a 4-wheel-independent-drive EV: Mamdani fuzzy upper layer generates corrective yaw moment; MPC lower layer allocates optimal wheel torques via a **custom Hildreth QP solver** (no Optimization Toolbox required). Validated in CarSim across three ISO maneuvers.

- 🏎️ Tight DLC (120 km/h): Peak yaw rate **144 → 47 deg/s** (67% reduction)
- 🧊 Low-μ DLC (μ=0.3): Yaw rate bounded to **±13 deg/s** vs 77 deg/s uncontrolled; sideslip near zero vs ~−140° spin-out
- 🌊 Sine-wave steer: **75% peak sideslip reduction**; lateral position drift halved
| | Project | Stack | Key Result |
|---|---|---|---|
| 🔄 | [4WID-MPC Vehicle Stability Control](./4wid-mpc-stability-control) | MATLAB · Simulink · CarSim · Fuzzy + MPC | Yaw rate 144 → 47 deg/s · 75% sideslip reduction |
| ⚡ | [Hybrid / EV / ICE Powertrain Simulation](./hybrid-ev-ice-powertrain-sim) | MATLAB · Simulink · Stateflow | 64 MPG HEV · 819-mile range |
| 🔋 | [BMS — SOC & SOP Estimation](./bms-soc-sop-estimation) | MATLAB · Simulink · EKF · Stateflow | 110 kWh pack · Stellantis/DOE |
| 🌡️ | [Motor Thermal Management](./formula-sae-motor-thermal-management) | CATIA V5 · ANSYS Fluent · Arduino | 40% pump energy reduction · 4.8 kW managed |
| 📡 | [Sensor Fusion & Adaptive Cruise Control](./adaptive-cruise-control-sensor-fusion) | Arduino C++ · Kalman Filter · PID | < 3 mm accuracy · 200 Hz loop |
| 🏎️ | [Formula SAE Accumulator Design](./formula-sae-accumulator-design) | CATIA · ANSYS · MATLAB · Simulink | 72V 6.2 kWh · 80 cells · 40g FEA validated |

---

### ⚡ [Hybrid, Electric & ICE Powertrain Simulation](./hybrid-ev-ice-powertrain-sim)
> `MATLAB` `Simulink` `Stateflow` `Energy Management`

Forward-facing vehicle simulation comparing ICE, BEV, and series–parallel HEV under real-world drive cycles. Rule-based Stateflow EMS with Economy and Sport modes controlling engine, motor, clutch, regen, and charging states.

- 🔥 ICE: **43 MPG** — BSFC-optimized 6-speed gear shift, 2.0L NA
- ⚡ BEV: **181-mile range** — 40.8 kWh, BorgWarner HVH250, PID thermal control
- 🏁 HEV: **64 MPG / 819-mile range** — 1.5L + HPEVS AC-23, 90 kW combined

---

### 🔋 [BMS Algorithms — SOC & SOP Estimation](./bms-soc-sop-estimation)
> `MATLAB` `Simulink` `Stateflow` `Kalman Filter` `Thevenin Model`

**U.S. DOE Battery Workforce Challenge (Stellantis)** — BMS algorithm development and thermal controls for a 110 kWh production vehicle battery pack.

- Extended Kalman Filter SOC estimation on Thevenin equivalent circuit with temperature-dependent parameters
- SOP estimation via voltage-constraint method using 2D R0(SOC, T) lookup tables
- Stateflow CC-CV charging controller with fault detection and safety interlocks
- Thermal design: **8.9 kW peak heat load** — coolant channel sizing and thermal control logic

---

### 🌡️ [Motor Thermal Management System](./formula-sae-motor-thermal-management)
> `CATIA V5` `ANSYS Fluent` `MATLAB` `Arduino C++`

**Formula SAE — Team Octane Racing Electric.** Liquid cooling system for a 32 kW racing motor triggering thermal shutdowns at 85°C. Thermal resistance network → CATIA jacket design → ANSYS CFD → Arduino PID controller.

- 🌡️ **4.8 kW** heat load managed; motor held below 80°C during endurance
- 📉 **40% pump energy reduction** via closed-loop PID speed control
- 🔬 CFD: **15 kPa** pressure drop, **6°C** coolant ΔT — validated before manufacturing
- 🏆 Car finished **2nd place nationally** at Formula Bharat (India)

---

### 🚗 [Sensor Fusion & Adaptive Cruise Control](./adaptive-cruise-control-sensor-fusion)
> `Arduino C++` `Kalman Filter` `PID` `Sensor Fusion`

Dual HC-SR04 sensor fusion with Kalman filtering, deployed on an RC vehicle with independent PID controllers for ACC (throttle) and lane keeping (steering) at ~200 Hz.

- 📏 **< 3 mm** distance accuracy · Fusion convergence: **600 ms → 250 ms**
- ✅ Track completion: **12.6 s**, all 5 checkpoints cleared

---

### 🏎️ [Formula SAE — Accumulator Design](./formula-sae-accumulator-design)
> `CATIA V5` `ANSYS` `MATLAB` `Simulink`

Ground-up design of a **72V, 6.2 kWh NMC racing battery pack** (Formula Bharat 2022): OpenLap energy simulation → cell selection → 20s4p architecture → segment design → Orion BMS 2 integration → Simulink models (cell, pack, CC-CV, heat dissipation).

- 80 cells across 5 segments, all validated to **40g longitudinal/lateral, 20g vertical** (FEA)

---

## 📊 GitHub Stats

<div align="center">

![Abhishek's GitHub Stats](https://github-readme-stats.vercel.app/api?username=abhishek-kedage&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=abhishek-kedage&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🎓 Currently Working On
### Skills

```
🏎️  Deep Orange 18    —  Powertrain sizing for high-speed autonomous vehicle (Clemson)
🛢️  DD13 Engine Dyno  —  Alternate fuel CI engine testing & data acquisition
Controls          MPC · PID · EKF · Fuzzy Logic · Stateflow · State-space
BMS               SOC/SOP estimation · CC-CV control · Thevenin model · HPPC testing
Thermal           Battery & motor thermal management · CFD (ANSYS Fluent) · Resistance networks
Simulation        MATLAB · Simulink · Simscape · CarSim · Scilab
CAD / CAE         CATIA V5 · SolidWorks · Creo · Ansys · Fusion 360
Programming       MATLAB (primary) · Python · C++ · Shell · Docker
```

---

## 🏢 Experience Highlights

**Earthsense Inc.** *(System Engineer, 2 years)* — EV and hybrid powertrain development for autonomous inspection robots. Extended runtime 3 hrs → 10 hrs via EV-to-hybrid architecture shift. Dockerized system integration with Python/Shell.

**Clemson University** *(Research Assistant — Battery Workforce Challenge, Stellantis/DOE)* — BMS algorithms (SOC/SOP) + thermal controls design for 110 kWh production battery pack.

**Team Octane Racing Electric** *(Technical Lead, 3.5 years, 40-member team)* — Powertrain and thermal subsystems across multiple Formula SAE vehicles. HPPC cell testing, Thevenin model parameter extraction, motor cooling, battery pack architecture.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f4c75,50:1a1f2e,100:0d1117&height=120&section=footer" />

*Available for Summer 2026 internships (June 1 start) — Powertrain Controls · BMS · Thermal Systems · Vehicle Dynamics — USA*

</div>
