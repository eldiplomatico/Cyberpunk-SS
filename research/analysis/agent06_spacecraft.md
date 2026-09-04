# AGENT 06 -- SPACECRAFT MISSION DATABASE: ASTEROIDS, COMETS, AND NEOs

## Research Methodology
Research conducted via web searches of NASA, ESA, JAXA, CNSA official sources, peer-reviewed literature (Nature, IOPscience, arXiv), eoPortal, Gunter's Space Page, and NASA Technical Reports Server. Minimum 12 searches conducted across all major missions.

---

## 1. MISSION INVENTORY TABLE

| # | Mission | Agency | Launch | Target(s) | Type | Mass (launch/dry) kg | Status | Deflection Capability |
|---|---------|--------|--------|-----------|------|----------------------|--------|-----------------------|
| 1 | DART | NASA/APL | 2021-11-24 | Dimorphos (moon of Didymos) | Kinetic Impactor | 610/~550 | Completed (impact 2022-09-26) | YES -- DEMONSTRATED |
| 2 | OSIRIS-REx | NASA | 2016-09-08 | 101955 Bennu | Sample Return | 2,110/880 | Completed (sample returned 2023-09-24) | No (science mission) |
| 3 | OSIRIS-APEX | NASA | (extended mission) | 99942 Apophis | Flyby/Orbital Study | ~880 (dry, post-sample) | Active -- en route to Apophis (arrival 2029) | No |
| 4 | Lucy | NASA | 2021-10-16 | Jupiter Trojan asteroids (multiple) | Flyby Survey | 1,550/821 | Active | No |
| 5 | Psyche | NASA | 2023-10-13 | 16 Psyche | Orbiter | 2,747/1,648 | Active -- en route (arrival 2029) | No |
| 6 | Hayabusa | JAXA | 2003-05-09 | 25143 Itokawa | Sample Return | 510/380 | Completed (2010) | No |
| 7 | Hayabusa2 | JAXA | 2014-12-03 | 162173 Ryugu | Sample Return + SCI impactor | 600/490 | Completed (sample returned 2020-12-06) | Partial (SCI impactor test) |
| 8 | Rosetta/Philae | ESA | 2004-03-02 | 67P/Churyumov-Gerasimenko | Orbiter + Lander | 2,900/~1,230 | Completed (2016) | No |
| 9 | Deep Impact/EPOXI | NASA | 2005-01-12 | 9P/Tempel 1, 103P/Hartley 2 | Flyby + Impactor | 973/~601 (bus) | Completed (2013 -- lost contact) | Partial (impactor demonstrated) |
| 10 | Stardust/NExT | NASA | 1999-02-07 | 81P/Wild 2, 5535 Annefrank, 9P/Tempel 1 | Sample Return + Flyby | 385/254 | Completed (2011) | No |
| 11 | Hera | ESA | 2024-10-07 | Didymos/Dimorphos | Post-Impact Survey | 1,128/~780 | Active -- en route (arrival late 2026) | No (assessment only) |
| 12 | NEOWISE | NASA | 2009-12-14 | NEO Survey (IR telescope) | Survey/Detection | 661/~550 | Completed (decommissioned 2024) | No (survey only) |
| 13 | NEO Surveyor | NASA | Planned 2027-2028 | NEO Survey (IR telescope) | Survey/Detection | ~1,300 | In Development | No (survey only) |
| 14 | NEA Scout | NASA | 2022-11-16 | 2020 GE (NEA) | Solar Sail Flyby | ~14 (CubeSat) | Failed (lost contact) | No |
| 15 | Tianwen-2 | CNSA | 2025-05-28 | 469219 Kamo'oalewa, 311P/PanSTARRS | Sample Return + Comet Flyby | ~2,100/~1,000 | Active -- arrived at Kamo'oalewa | No |
| 16 | Comet Interceptor | ESA/JAXA | Planned ~2029 | Long-period or interstellar comet (TBD) | Multi-spacecraft flyby | ~1,000 (total, 3 spacecraft) | In Development | No |
| 17 | NEAR Shoemaker | NASA | 1996-02-17 | 433 Eros | Orbiter (landed) | 805/487 | Completed (2001) | No |
| 18 | Dawn | NASA | 2007-09-27 | 4 Vesta, 1 Ceres | Orbiter | 1,218/747 | Completed (2018) | No |
| 19 | Don Quijote (cancelled) | ESA | Cancelled | NEA (TBD) | Kinetic Impactor + Orbiter | ~400 (impactor) | Cancelled | YES (planned) |
| 20 | AIDA (original concept) | ESA/NASA | Evolved into DART+Hera | Didymos/Dimorphos | Kinetic Impact + Assessment | N/A (concept) | Superseded | YES (planned) |

---

## 2. DETAILED MISSION PROFILES

### 2.1 DART (Double Asteroid Redirection Test) -- NASA/Johns Hopkins APL

**Mission Objective (Stated):** First-ever planetary defense technology demonstration using kinetic impactor technique to change an asteroid's motion in space.

**Spacecraft Name:** DART

**Agency:** NASA (managed by Johns Hopkins Applied Physics Laboratory)

**Launch Date:** November 24, 2021, on SpaceX Falcon 9

**Target Object:** Dimorphos (moon of 65803 Didymos)
- Target Discovery Date: Didymos discovered 1996; Dimorphos discovered 2003
- Dimorphos diameter: ~151 m
- Dimorphos estimated mass: ~4.3 x 10^9 kg (assuming density ~2,400 kg/m^3)

**Spacecraft Mass:**
- Launch mass: ~610 kg (1,345 lb)
- Impact mass: ~580 kg (1,280 lb) -- after fuel consumption
- Dry mass: ~500 kg

**Propulsion System:**
- Primary: NEXT-C solar electric ion propulsion (technology demonstration) -- derived from Dawn mission; xenon ion thruster
- Secondary: Hydrazine monopropellant thrusters for attitude control and maneuvering
- Fuel: ~50 kg hydrazine, ~60 kg xenon

**Delta-V Capability:** The NEXT-C ion engine provided low continuous thrust; hydrazine thrusters for terminal targeting maneuvers

**Guidance and Navigation:**
- SMART Nav (Small-body Maneuvering Autonomous Real Time Navigation) -- autonomous onboard navigation for terminal approach
- Ground-based optical navigation during cruise

**Payload and Instrumentation:**
- DRACO (Didymos Reconnaissance and Asteroid Camera for Optical Navigation) -- single high-resolution imager derived from New Horizons LORRI camera
- LICIACube -- Italian Space Agency (ASI) 6U CubeSat deployed before impact for flyby imaging

**Communications:** X-band, RLSA (Radial Line Slot Array) antenna -- flat, high-gain antenna (technology demonstration)

**Encounter Velocity:** 6.1 km/s (approximately 6.14 km/s measured)

**Planned vs. Actual Trajectory:** Impact was precisely on target; SMART Nav guided spacecraft autonomously in final 4 hours; impacted within meters of Dimorphos center

**DEFLECTION DATA (ACTUAL MEASURED):**
- Orbital period change: -33 +/- 1 minutes (from 11 hours 55 minutes to 11 hours 23 minutes)
- Velocity change to Dimorphos: -2.70 +/- 0.10 mm/s (along-track)
- Momentum transfer enhancement factor (beta): 3.61 +/- 0.25 (assuming equal densities of 2,400 kg/m^3 for Didymos and Dimorphos)
- Beta range: 2.2 to 4.9 depending on assumed Dimorphos bulk density (1,500--3,300 kg/m^3)
- This means ejecta contributed 2-4x MORE momentum than the spacecraft itself

**Kinetic Impact Capability:** YES -- DEMONSTRATED
- Kinetic energy at impact: ~11 GJ (0.5 x 580 kg x (6,140 m/s)^2)
- Momentum delivered by spacecraft alone: 580 kg x 6,140 m/s = ~3.56 x 10^6 kg*m/s
- Effective momentum (with beta=3.61): ~1.29 x 10^7 kg*m/s
- Ejecta mass: Estimated tens of thousands of kg of material ejected

**Nuclear Capability:** No

**Mission Cost:** ~$325 million (excluding LICIACube)

**Mission Status:** Completed

**Mission Anomalies:** None significant. Beta factor being substantially above 1.0 was a positive surprise, indicating ejecta enhancement was far more effective than worst-case models predicted.

---

### 2.2 OSIRIS-REx (Origins, Spectral Interpretation, Resource Identification, Security -- Regolith Explorer) -- NASA

**Mission Objective (Stated):** Collect and return a sample from near-Earth asteroid Bennu; map the asteroid and study the Yarkovsky effect for planetary defense knowledge

**Spacecraft Name:** OSIRIS-REx

**Agency:** NASA / University of Arizona / Lockheed Martin / GSFC

**Launch Date:** September 8, 2016, on Atlas V 411

**Target Object:** 101955 Bennu
- Target Discovery Date: September 11, 1999
- Bennu diameter: ~500 m
- Bennu estimated mass: ~7.3 x 10^10 kg
- Bennu is classified as a Potentially Hazardous Asteroid (PHA)

**Spacecraft Mass:**
- Launch mass: 2,110 kg
- Dry mass: 880 kg
- Propellant mass: ~1,230 kg

**Propulsion System:**
- Derived from Mars Reconnaissance Orbiter / MAVEN heritage
- Main engines, trajectory correction thrusters, attitude control thrusters, low-thrust reaction engine assemblies
- Hydrazine monopropellant and nitrogen tetroxide/hydrazine bipropellant

**Payload and Instrumentation:**
- OCAMS (OSIRIS-REx Camera Suite -- PolyCam, MapCam, SamCam)
- OLA (OSIRIS-REx Laser Altimeter) -- provided by CSA
- OVIRS (Visible and Infrared Spectrometer)
- OTES (Thermal Emission Spectrometer)
- REXIS (Regolith X-Ray Imaging Spectrometer)
- TAGSAM (Touch-And-Go Sample Acquisition Mechanism) -- sample collection device

**Encounter Velocity:** Rendezvous mission (not flyby); very low relative velocity at orbit insertion (~0.2 m/s during touch-and-go)

**Ability to Change Target Velocity:** No meaningful capability
- The spacecraft could theoretically fire thrusters while near/on the asteroid, but the momentum transfer would be negligible against Bennu's mass
- TAGSAM contact was ~6 seconds; thruster firing during backaway demonstrated surface material mobilization but no measurable orbit change

**Documented Deflection Capability:** None. Purely scientific mission. However, the detailed mapping of Bennu's orbit and the Yarkovsky effect directly contributes to deflection planning knowledge.

**Nuclear Capability:** No
**Kinetic Impact Capability:** No (designed for gentle sample collection, not impact)

**Mission Cost:** ~$1.16 billion (including launch vehicle)

**Mission Status:** Primary mission completed (sample returned September 24, 2023). Extended as OSIRIS-APEX.

---

### 2.3 OSIRIS-APEX (OSIRIS-APophis EXplorer) -- NASA

**Mission Objective (Stated):** Study near-Earth asteroid 99942 Apophis following its close Earth approach in April 2029; characterize surface changes caused by tidal forces during the close approach

**Target Object:** 99942 Apophis
- Discovery Date: June 19, 2004
- Apophis diameter: ~370 m
- Apophis mass: ~6.1 x 10^10 kg
- Formerly classified as PHA with significant Earth impact probability (now ruled out for 2029 and 2036)

**Spacecraft Mass:** ~880 kg dry (same spacecraft as OSIRIS-REx, but without sample return capsule and with depleted fuel)

**Propulsion:** Same as OSIRIS-REx heritage system but with limited remaining propellant

**Key Activities at Apophis:**
- Arrive shortly after Apophis's close Earth flyby (within ~0.1 AU of Earth, April 13, 2029)
- 18 months of proximity operations
- STIR (Spacecraft Thruster Investigation of Regolith) maneuver: use thrusters to excavate surface material
- Map surface with remaining OCAMS, OTES, OVIRS instruments

**Deflection Capability:** No. Cannot meaningfully alter Apophis's orbit. The spacecraft mass is negligible relative to Apophis's mass.

**Mission Status:** Active -- en route. Earth gravity assist in 2025; arrival at Apophis mid-2029.

---

### 2.4 Lucy -- NASA/SWRI

**Mission Objective (Stated):** First mission to explore Jupiter's Trojan asteroids; investigate the diversity of primitive bodies that hold clues to the early solar system

**Spacecraft Name:** Lucy

**Agency:** NASA / Southwest Research Institute (PI)

**Launch Date:** October 16, 2021, on Atlas V 401

**Target Objects:** 
- Main belt: 52246 Donaldjohanson (flyby April 2025)
- L4 Trojans: 3548 Eurybates + satellite Queta, 15094 Polymele + satellite Shaul, 11351 Leucus, 21900 Orus
- L5 Trojans: 617 Patroclus/Menoetius (binary)

**Spacecraft Mass:**
- Launch mass: 1,550 kg
- Dry mass: 821 kg
- Propellant: ~729 kg hydrazine and NTO

**Propulsion System:**
- Dual-mode propulsion: hydrazine monopropellant + hydrazine/nitrogen tetroxide bipropellant
- Aerojet Rocketdyne thrusters

**Delta-V Capability:** Substantial for trajectory correction maneuvers, but mission is designed as flyby -- not orbital insertion

**Payload and Instrumentation:**
- L'LORRI (Long Range Reconnaissance Imager) -- derived from New Horizons
- L'Ralph (multispectral visible and IR mapping spectrometer)
- L'TES (Thermal Emission Spectrometer)
- Terminal Tracking Camera system

**Encounter Velocity:** High flyby speeds (varying by target, typically several km/s relative velocity)

**Deflection Capability:** No. Flyby mission only. No contact with targets. Trojan asteroids are in Jupiter's orbit, not near-Earth.

**Nuclear Capability:** No
**Kinetic Impact Capability:** No (not designed for impact; targets are too distant and massive)

**Mission Cost:** ~$981 million

**Mission Status:** Active. Successfully flew by Donaldjohanson (April 2025) -- discovered it was a contact binary.

**Anomaly:** One of two solar arrays did not fully latch after deployment. NASA eventually resolved this to acceptable operational status.

---

### 2.5 Psyche -- NASA/ASU

**Mission Objective (Stated):** Explore the origin of planetary cores by orbiting and studying metallic asteroid 16 Psyche

**Spacecraft Name:** Psyche

**Agency:** NASA / Arizona State University (PI) / JPL

**Launch Date:** October 13, 2023, on SpaceX Falcon Heavy

**Target Object:** 16 Psyche
- Discovery Date: March 17, 1852
- Psyche dimensions: ~280 x 232 x 164 km (highly irregular)
- Psyche mass: ~2.41 x 10^19 kg
- Main belt asteroid (not NEO)

**Spacecraft Mass:**
- Launch mass: 2,747 kg (including DSOC tech demo)
- Dry mass: 1,648 kg
- Xenon propellant: 1,085 kg

**Propulsion System:**
- Solar Electric Propulsion (SEP)
- Four SPT-140 Hall-effect thrusters
- Maximum thrust: ~240 millinewtons per thruster
- Xenon ion propulsion

**Delta-V Capability:** Very high cumulative delta-V due to continuous low-thrust operation over years. The large xenon load (~1,085 kg) provides substantial total impulse.

**Payload and Instrumentation:**
- Multispectral Imager
- Gamma-Ray and Neutron Spectrometer
- Magnetometer
- X-band radio (gravity science)
- DSOC (Deep Space Optical Communications) -- technology demonstration

**Deflection Capability:** No. Target is a main-belt asteroid far too massive (~2.4 x 10^19 kg) for any conceivable deflection. Mission is purely scientific.

**Nuclear Capability:** No
**Kinetic Impact Capability:** No

**Mission Cost:** ~$985 million (excluding launch vehicle)

**Mission Status:** Active -- en route. Mars gravity assist in 2026; arrival at Psyche in August 2029.

---

### 2.6 Hayabusa -- JAXA

**Mission Objective (Stated):** Demonstrate technologies for asteroid sample return; collect and return surface material from near-Earth asteroid Itokawa

**Spacecraft Name:** Hayabusa (MUSES-C)

**Agency:** JAXA

**Launch Date:** May 9, 2003, on M-V rocket

**Target Object:** 25143 Itokawa
- Discovery Date: September 26, 1998
- Itokawa dimensions: ~535 x 294 x 209 m (elongated, rubble-pile)
- Itokawa mass: ~3.51 x 10^10 kg

**Spacecraft Mass:**
- Launch mass: ~510 kg
- Dry mass: ~380 kg
- Xenon propellant: ~66 kg

**Propulsion System:**
- Four xenon ion engines (mu-10), each producing ~8 mN thrust
- Bipropellant (NTO/hydrazine) thrusters for attitude control
- Ion engines operated on microwave discharge

**Payload and Instrumentation:**
- AMICA (Asteroid Multi-band Imaging Camera)
- NIRS (Near-Infrared Spectrometer)
- XRS (X-ray fluorescence spectrometer)
- LIDAR (Light Detection and Ranging)
- MINERVA mini-lander (deployment failed)
- Sample collection horn

**Encounter Velocity:** Rendezvous (station-keeping), not high-speed flyby

**Deflection Capability:** No. The spacecraft mass is negligible relative to Itokawa. Even a deliberate impact at station-keeping velocity would produce unmeasurable orbit change.

**Nuclear Capability:** No
**Kinetic Impact Capability:** No

**Mission Cost:** ~$170 million

**Mission Status:** Completed. Sample capsule returned June 13, 2010. Recovered microscopic particles from Itokawa -- first asteroid sample return.

**Anomalies:** 
- Fuel leak from reaction control system
- Two of four reaction wheels failed
- Ion engine neutralizer failures
- Communication losses
- Despite severe anomalies, mission succeeded through innovative engineering workarounds

---

### 2.7 Hayabusa2 -- JAXA

**Mission Objective (Stated):** Collect and return subsurface and surface samples from C-type near-Earth asteroid Ryugu; deploy surface science packages; test Small Carry-on Impactor (SCI)

**Spacecraft Name:** Hayabusa2

**Agency:** JAXA

**Launch Date:** December 3, 2014, on H-IIA rocket

**Target Object:** 162173 Ryugu
- Discovery Date: May 10, 1999
- Ryugu diameter: ~900 m
- Ryugu mass: ~4.5 x 10^11 kg

**Spacecraft Mass:**
- Launch mass: 600 kg
- Dry mass: 490 kg
- Xenon propellant: ~48 kg

**Propulsion System:**
- Four xenon ion engines (mu-10 improved), each ~10 mN
- Chemical thrusters (hydrazine) for attitude control and proximity operations

**Payload and Instrumentation:**
- ONC (Optical Navigation Camera) -- telescopic and wide-angle
- TIR (Thermal Infrared Imager)
- NIRS3 (Near-Infrared Spectrometer)
- LIDAR
- SCI (Small Carry-on Impactor) -- 2 kg copper projectile fired by shaped charge explosive
- DCAM3 -- deployable camera to observe SCI impact
- MINERVA-II rovers (1A, 1B, 2)
- MASCOT lander (DLR/CNES)
- Sample collection horn with tantalum projectile

**SCI (Small Carry-on Impactor) Details:**
- Mass: ~2 kg copper liner projectile
- Propelled by shaped-charge explosive
- Impact velocity: ~2 km/s
- Created artificial crater ~14.5 m diameter on Ryugu
- Purpose: expose subsurface material for sampling
- This was NOT a deflection test -- the crater was for science

**Encounter Velocity:** Rendezvous mission; station-keeping at ~20 km altitude

**Deflection Capability:**
- The SCI impactor demonstrated kinetic impact on an asteroid surface, but at a scale far too small to alter Ryugu's orbit
- SCI projectile momentum: ~2 kg x 2,000 m/s = 4,000 kg*m/s -- negligible against Ryugu's mass
- Demonstrated the TECHNOLOGY of impacting an asteroid, but not the CAPABILITY to deflect one

**Nuclear Capability:** No (but SCI used explosive charge for propulsion of projectile)
**Kinetic Impact Capability:** Partial (demonstrated impact technology at small scale)

**Mission Cost:** ~$150 million

**Mission Status:** Completed. Sample capsule returned December 6, 2020 (5.4 grams including gas). Extended mission (Hayabusa2#) to fly by additional asteroids.

---

### 2.8 Rosetta/Philae -- ESA

**Mission Objective (Stated):** First mission to orbit and land on a comet; study the origin of comets and the relationship between cometary and interstellar material

**Spacecraft Name:** Rosetta (orbiter) + Philae (lander)

**Agency:** ESA

**Launch Date:** March 2, 2004, on Ariane 5 G+

**Target Object:** 67P/Churyumov-Gerasimenko
- Discovery Date: September 20, 1969
- Comet nucleus dimensions: ~4.3 x 4.1 km (bilobed)
- Mass: ~1.0 x 10^13 kg

**Spacecraft Mass:**
- Rosetta total launch mass: 2,900 kg
- Rosetta propellant: ~1,670 kg
- Rosetta science payload: 165 kg
- Philae lander: 100 kg (including 21 kg science instruments)

**Propulsion System:**
- 24 bipropellant 10N thrusters (MMH/NTO)
- Used for heliocentric orbit corrections and rendezvous

**Delta-V:** Substantial -- mission included multiple gravity assists (Earth x3, Mars x1) and asteroid flybys (2867 Steins, 21 Lutetia)

**Payload and Instrumentation (Rosetta Orbiter -- 11 instruments):**
- ALICE (UV imaging spectrometer)
- CONSERT (nucleus sounding experiment)
- COSIMA (ion mass spectrometer)
- GIADA (grain impact analyser)
- MIDAS (micro-imaging dust analysis)
- MIRO (microwave instrument)
- OSIRIS (optical imaging system -- narrow and wide angle)
- ROSINA (mass spectrometer)
- RPC (plasma instruments)
- RSI (radio science)
- VIRTIS (visible and infrared spectrometer)

**Philae Lander (10 instruments):**
- APXS, CIVA, CONSERT, COSAC, Ptolemy, MUPUS, ROLIS, ROMAP, SD2, SESAME

**Communications:** 2.2 m diameter high-gain antenna; up to 22 kbps data rate via ESA 35m ground stations

**Encounter Velocity:** Rendezvous (not flyby); matched comet's orbit and escorted it around the Sun

**Deflection Capability:** No. The comet's mass (~10^13 kg) is enormously larger than the spacecraft. Even if Rosetta had deliberately impacted 67P at orbital velocity, the momentum transfer would be unmeasurable.

**Nuclear Capability:** No
**Kinetic Impact Capability:** No (Rosetta did intentionally crash into the comet at end of mission, but at very low velocity ~0.9 m/s -- this was not a deflection attempt)

**Mission Cost:** ~1.4 billion EUR

**Mission Status:** Completed. Philae landed November 12, 2014 (bounced, settled in shadow, limited operations). Rosetta operated through September 30, 2016 (controlled impact on 67P surface).

---

### 2.9 Deep Impact / EPOXI -- NASA

**Mission Objective (Stated):** Study the interior composition of comet 9P/Tempel 1 by firing an impactor into its surface and observing the resulting crater and ejecta

**Spacecraft Name:** Deep Impact (flyby bus + impactor)

**Agency:** NASA / University of Maryland (PI) / JPL

**Launch Date:** January 12, 2005, on Delta II 7925

**Target Objects:**
- Primary: 9P/Tempel 1 (impact July 4, 2005)
- Extended (EPOXI): 103P/Hartley 2 (flyby November 4, 2010)

**Target Discovery Dates:**
- Tempel 1: April 3, 1867
- Hartley 2: March 15, 1986

**Spacecraft Mass:**
- Total launch mass: ~973 kg
- Flyby spacecraft: ~601 kg
- Impactor: ~372 kg (with 113 kg copper mass concentrate for cratering)
- Impactor had ~8 kg hydrazine for targeting

**Propulsion System:**
- Flyby bus: Hydrazine monopropellant
- Impactor: Small hydrazine system (~25 m/s delta-V capacity)

**Payload and Instrumentation:**
- Flyby: HRI (High Resolution Instrument -- 30 cm telescope with CCD and IR spectrometer), MRI (Medium Resolution Instrument -- 12 cm telescope with CCD)
- Impactor: ITS (Impactor Targeting Sensor -- identical to MRI CCD)

**Encounter Velocity:** 10.2-10.3 km/s relative velocity at impact

**Impact Energy:** ~19 GJ (equivalent to 4.8 tons of TNT)

**Momentum Transfer:**
- Impactor momentum: 372 kg x 10,200 m/s = ~3.79 x 10^6 kg*m/s
- Tempel 1 mass: ~7.9 x 10^13 kg
- Theoretical delta-V to comet: ~4.8 x 10^-8 m/s -- completely unmeasurable
- Crater created: ~100 m diameter estimated

**Deflection Capability:**
- Designed to study impact science, NOT to deflect the comet
- Impact energy was scientifically significant but deflection-irrelevant given comet's mass
- However, the mission provided critical validation of autonomous terminal targeting technology later used in DART

**Nuclear Capability:** No
**Kinetic Impact Capability:** Yes (demonstrated kinetic impact on a solar system body) -- but at a scale producing no measurable deflection

**Mission Cost:** ~$267 million (Deep Impact), ~$42 million additional (EPOXI)

**Mission Status:** Completed. Contact lost August 2013.

---

### 2.10 Stardust / NExT -- NASA

**Mission Objective (Stated):** Collect cometary dust and interstellar particles and return them to Earth; extended mission to revisit Tempel 1

**Spacecraft Name:** Stardust

**Agency:** NASA / JPL

**Launch Date:** February 7, 1999, on Delta II 7426

**Target Objects:**
- 81P/Wild 2 (flyby January 2, 2004)
- 5535 Annefrank (flyby November 2, 2002)
- 9P/Tempel 1 (NExT flyby February 15, 2011)

**Spacecraft Mass:**
- Total mass: ~385 kg (launch)
- Sample return capsule: ~46 kg
- Dry mass: ~254 kg

**Propulsion System:**
- Hydrazine monopropellant thrusters
- Delta-V provided by ground-based navigation and propulsive maneuvers

**Payload and Instrumentation:**
- Navigation Camera (used for science imaging)
- Cometary and Interstellar Dust Analyzer (CIDA)
- Dust Flux Monitor Instrument (DFMI)
- Aerogel collector for sample capture

**Encounter Velocity:**
- Wild 2 flyby: ~6.1 km/s at 236 km distance
- Tempel 1 (NExT): ~10.9 km/s at 181 km distance

**Deflection Capability:** No. Pure flyby/sample collection mission. No contact with target bodies.

**Nuclear Capability:** No
**Kinetic Impact Capability:** No

**Mission Cost:** ~$200 million (Stardust), ~$29 million (NExT)

**Mission Status:** Completed. Sample return capsule landed January 15, 2006. NExT flyby February 15, 2011. Spacecraft decommissioned March 24, 2011.

---

### 2.11 Hera -- ESA

**Mission Objective (Stated):** Detailed post-impact characterization of the DART impact outcome at Didymos/Dimorphos; determine Dimorphos mass, crater properties, and momentum transfer efficiency

**Spacecraft Name:** Hera

**Agency:** ESA

**Launch Date:** October 7, 2024, on SpaceX Falcon 9

**Target Object:** Didymos/Dimorphos binary system (same target as DART)

**Spacecraft Mass:**
- Launch mass: 1,128 kg
- Body dimensions: 1.6 x 1.6 x 1.7 m
- Solar array span: 11.5 m

**Propulsion System:**
- Bipropellant chemical propulsion (MMH/NTO)
- Delta-V capability: ~1,300 m/s

**Payload and Instrumentation:**
- AFC (Asteroid Framing Cameras) -- 2 cameras for imaging and optical navigation
- HyperScout-H (hyperspectral imager)
- TIRI (Thermal Infrared Imager)
- PALT (Planetary Altimeter)
- Radar for sub-surface investigation
- Milani CubeSat (dust and mineralogy)
- Juventas CubeSat (gravity field, internal structure via radar)

**Deflection Capability:** No. Hera is purely an assessment mission to measure the outcome of DART's impact. It does not carry any impactor or deflection hardware.

**Nuclear Capability:** No
**Kinetic Impact Capability:** No

**Mission Cost:** ~320 million EUR

**Mission Status:** Active -- en route. Planned arrival at Didymos system late 2026.

---

### 2.12 NEOWISE -- NASA

**Mission Objective (Stated):** Originally WISE (Wide-field Infrared Survey Explorer) for all-sky infrared survey; repurposed as NEOWISE to detect and characterize near-Earth objects

**Spacecraft Name:** WISE / NEOWISE

**Agency:** NASA / JPL / UCLA

**Launch Date:** December 14, 2009, on Delta II 7320

**Target:** All-sky infrared survey, with emphasis on NEO detection in extended mission

**Spacecraft Mass:** 661 kg

**Instruments:** 40 cm infrared telescope with four detector arrays (3.4, 4.6, 12, 22 micrometers); only two shortest wavelength bands operational in NEOWISE phase

**Deflection Capability:** None. Survey telescope only. No physical interaction with any asteroid.

**Mission Status:** Decommissioned August 2024 (re-entered atmosphere)

**Key Achievement:** Detected >34,000 asteroids, including >700 NEOs, and >250 comets

---

### 2.13 NEO Surveyor -- NASA

**Mission Objective (Stated):** First space telescope specifically designed for planetary defense; detect and characterize potentially hazardous NEOs

**Agency:** NASA / JPL / University of Arizona

**Launch Date:** Planned September 2027 -- June 2028

**Spacecraft Mass:** <1,300 kg

**Orbit:** Earth-Sun L1 Lagrange point

**Instruments:** 50 cm diameter infrared telescope operating in two thermal infrared wavelength bands

**Deflection Capability:** None. Detection/survey mission only.

**Mission Cost:** ~$1.2 billion (estimated)

**Mission Status:** In development

---

### 2.14 NEA Scout -- NASA

**Mission Objective (Stated):** Use solar sail propulsion to fly by and image a near-Earth asteroid

**Spacecraft Name:** NEA Scout

**Agency:** NASA / MSFC / JPL

**Launch Date:** November 16, 2022, on Artemis I (SLS)

**Target Object:** 2020 GE (small NEA, ~18 m)

**Spacecraft Mass:** ~14 kg (6U CubeSat with deployable solar sail ~86 m^2)

**Propulsion:** Solar sail (no propellant)

**Deflection Capability:** None. 14 kg spacecraft with no impact capability.

**Mission Status:** Failed -- lost contact shortly after deployment. Never acquired signal.

---

### 2.15 Tianwen-2 -- CNSA

**Mission Objective (Stated):** Sample return from near-Earth quasi-satellite Kamo'oalewa; extended mission to comet 311P/PanSTARRS

**Spacecraft Name:** Tianwen-2

**Agency:** CNSA (China National Space Administration)

**Launch Date:** May 28, 2025, on Long March 3B

**Target Objects:**
- 469219 Kamo'oalewa (Earth quasi-satellite, diameter ~40-100 m)
  - Discovery Date: April 27, 2016
- 311P/PanSTARRS (main-belt comet for extended mission)

**Spacecraft Mass:**
- Launch mass: ~2,100 kg (total, orbiter + return capsule)
- Dry mass: ~1,000 kg estimated

**Propulsion System:** Chemical propulsion (details not fully published)

**Payload and Instrumentation:**
- Multispectral camera
- Infrared spectrometer
- High-resolution camera
- Radar sounder (subsurface)
- Magnetometer
- Dust and gas analyzers
- Charged particle detectors
- Sample collection system (3 techniques: hovering, touch-and-go, anchoring)

**Sampling Methods:** Three techniques -- hovering sampling, touch-and-go, anchoring and attachment

**Deflection Capability:** No. Sample return science mission. The spacecraft has no impactor payload and is not designed for deflection.

**Nuclear Capability:** No
**Kinetic Impact Capability:** No

**Mission Status:** Active. Arrived at Kamo'oalewa (first images released). Sample return expected ~2027.

---

### 2.16 Comet Interceptor -- ESA/JAXA

**Mission Objective (Stated):** Multi-spacecraft flyby of a dynamically new long-period comet or interstellar object

**Spacecraft Name:** Comet Interceptor (3 spacecraft: A, B1, B2)

**Agency:** ESA (lead) / JAXA (B2 spacecraft)

**Launch Date:** Planned 2029 (co-manifested with ARIEL on Ariane 6.2)

**Target Object:** To be determined -- will wait at Sun-Earth L2 until a suitable long-period comet is discovered

**Spacecraft Mass:** ~1,000 kg total for all three spacecraft

**Deflection Capability:** No. Flyby science mission.

**Mission Status:** In development. Passed Mission Adoption Review 2022.

---

### 2.17 NEAR Shoemaker -- NASA

**Mission Objective (Stated):** First spacecraft to orbit an asteroid; study the near-Earth asteroid 433 Eros

**Launch Date:** February 17, 1996

**Target Object:** 433 Eros
- Dimensions: 34.4 x 11.2 x 11.2 km
- Mass: 6.687 x 10^15 kg

**Spacecraft Mass:**
- Launch mass: 805 kg
- Dry mass: 487 kg

**Propulsion:** Hydrazine monopropellant (bipropellant option)

**Payload:** MSI, NIS, XRS, GRS, magnetometer, laser rangefinder

**Deflection Capability:** No. Orbiter that ultimately performed a controlled descent/landing on Eros. Spacecraft mass negligible relative to Eros.

**Mission Cost:** ~$224 million

**Mission Status:** Completed (2001)

---

### 2.18 Dawn -- NASA

**Mission Objective (Stated):** Study two of the largest protoplanets in the asteroid belt -- 4 Vesta and 1 Ceres

**Launch Date:** September 27, 2007

**Target Objects:** 4 Vesta (orbited 2011-2012), 1 Ceres (orbited 2015-2018)

**Spacecraft Mass:**
- Launch mass: 1,218 kg
- Dry mass: 747 kg
- Xenon: 425 kg

**Propulsion:** Three NSTAR xenon ion engines (same heritage as Deep Space 1)

**Deflection Capability:** No. Targets are among the largest bodies in the asteroid belt (Vesta ~525 km, Ceres ~940 km diameter). Deflection is physically impossible with any spacecraft.

**Mission Cost:** ~$473 million

**Mission Status:** Completed (2018 -- ran out of hydrazine, still orbiting Ceres)

---

## 3. DEFLECTION CAPABILITY MATRIX

### Classification System:
- **D** = Demonstrated deflection capability
- **T** = Tested impact technology (without achieving measurable deflection)
- **P** = Planned/designed for deflection (not yet executed or cancelled)
- **C** = Could theoretically produce some momentum transfer if deliberately crashed
- **N** = No deflection capability whatsoever

| Mission | Designed for Deflection? | Demonstrated Deflection? | Could Theoretically Deflect? | Classification |
|---------|--------------------------|--------------------------|------------------------------|----------------|
| **DART** | YES | YES (33 min period change) | YES -- proven | **D** |
| OSIRIS-REx | No | No | Negligible (880 kg vs 7.3e10 kg target) | N |
| OSIRIS-APEX | No | No | Negligible | N |
| Lucy | No | No | No (flyby only, targets in Jupiter orbit) | N |
| Psyche | No | No | No (target mass ~2.4e19 kg) | N |
| Hayabusa | No | No | Negligible | N |
| **Hayabusa2 (SCI)** | No (SCI was for science) | No (unmeasurable) | Negligible (2 kg projectile) | **T** |
| Rosetta | No | No | Negligible | N |
| **Deep Impact** | No (science impactor) | No (unmeasurable) | Negligible on comet-scale target | **T** |
| Stardust | No | No | No (flyby only) | N |
| Hera | No | No | No (assessment mission) | N |
| NEOWISE | No | No | No (telescope only) | N |
| NEO Surveyor | No | No | No (telescope only) | N |
| NEA Scout | No | No | No (14 kg CubeSat) | N |
| Tianwen-2 | No | No | Negligible | N |
| Comet Interceptor | No | No | No (flyby only) | N |
| NEAR Shoemaker | No | No | Negligible | N |
| Dawn | No | No | Negligible | N |
| **Don Quijote** | YES | N/A (cancelled) | Was designed for it | **P** |

### Summary:
- **1 mission has DEMONSTRATED deflection:** DART
- **2 missions demonstrated impact technology** (without measurable deflection): Deep Impact, Hayabusa2 SCI
- **1 planned deflection mission was cancelled:** Don Quijote
- **All other missions:** No deflection capability, not designed for deflection, and could not meaningfully deflect their targets even if deliberately crashed

---

## 4. DART RESULTS -- ACTUAL MEASURED DEFLECTION DATA

### Pre-Impact Conditions
| Parameter | Value |
|-----------|-------|
| Target | Dimorphos (moonlet of Didymos) |
| Dimorphos diameter | ~151 m |
| Dimorphos estimated mass | ~4.3 x 10^9 kg (density ~2,400 kg/m^3) |
| Pre-impact orbital period | 11 hours 55 minutes (around Didymos) |
| DART impact mass | ~580 kg |
| Impact velocity | 6.14 km/s |
| Impact angle | ~73 degrees from surface normal |
| Impact date/time | September 26, 2022, 23:14 UTC |

### Impact Physics
| Parameter | Value |
|-----------|-------|
| Kinetic energy at impact | ~11 GJ |
| Spacecraft momentum at impact | 580 x 6,140 = 3.56 x 10^6 kg*m/s |
| Effective momentum (with ejecta, beta=3.61) | ~1.29 x 10^7 kg*m/s |

### Measured Results
| Parameter | Value | Source |
|-----------|-------|--------|
| Orbital period change | -33 +/- 1 minutes | NASA/APL ground observations |
| New orbital period | 11 hours 23 minutes | Multiple observatories |
| Along-track velocity change (Dimorphos) | -2.70 +/- 0.10 mm/s | Cheng et al. 2023, Nature |
| Beta (momentum enhancement factor) | 3.61 +/- 0.25 (at density 2,400 kg/m^3) | Cheng et al. 2023, Nature |
| Beta range (density-dependent) | 2.2 to 4.9 | For density range 1,500-3,300 kg/m^3 |
| Ejecta tail length | >10,000 km | Hubble, ground observations |
| Estimated ejecta mass | Tens of thousands of kg | Multiple estimates |

### Interpretation of Beta Factor
- Beta = 1.0 would mean: only the spacecraft's own momentum was transferred (no ejecta contribution)
- Beta = 3.61 means: the EJECTA contributed ~2.6x MORE momentum than the spacecraft itself
- This is a critical finding for planetary defense: kinetic impactors are MORE effective than "billiard ball" physics alone
- The rubble-pile structure of Dimorphos led to copious ejecta that enhanced the deflection

### What This Means for Planetary Defense
- A 580 kg spacecraft at 6.1 km/s changed the orbital velocity of a ~4.3 billion kg asteroid by 2.7 mm/s
- This was sufficient to change the orbital period of a small moonlet by 33 minutes
- For a standalone asteroid on an Earth-impact trajectory, this velocity change would need to be applied YEARS in advance to produce a meaningful miss distance
- Rule of thumb: 1 cm/s velocity change, applied 10 years before impact, shifts the asteroid's position by ~1 Earth diameter at the time of closest approach

---

## 5. COMPARISON: STATED MISSION vs. DEFLECTION POTENTIAL

### CRITICAL DISTINCTION: Three separate questions for each mission

**Question A: Was this spacecraft DESIGNED to deflect an asteroid?**
**Question B: Could this spacecraft THEORETICALLY produce a measurable trajectory change?**
**Question C: Is there any evidence this spacecraft was ACTUALLY INTENDED for deflection beyond its stated mission?**

| Mission | A: Designed for Deflection? | B: Could Theoretically Deflect? | C: Evidence of Hidden Deflection Intent? |
|---------|----------------------------|--------------------------------|------------------------------------------|
| DART | YES | YES -- PROVEN | N/A -- deflection was the stated mission |
| OSIRIS-REx | No | Only if deliberately crashed into a very small body at high velocity; momentum would be ~880 x v. Against Bennu: completely negligible | No. Extensive public documentation of science objectives. Trajectory was incompatible with impacting Bennu at high velocity. |
| Lucy | No | Theoretically, if crashed into a small target at flyby speed (~km/s), but all targets are massive and far from Earth | No. Trojan asteroids are not near-Earth threats. |
| Psyche | No | No meaningful capability against any realistic target | No. Target is a main-belt asteroid of planetary scale. |
| Hayabusa/2 | No | Negligible even in theory | No. Japanese sample return missions with full transparency. |
| Rosetta | No | Negligible | No. |
| Deep Impact | No (science impactor) | Demonstrated impact but not at deflection-relevant scale | No. But the technology was a precursor to DART. |
| Hera | No | No | No. Assessment mission by design. |

### Assessment of "Hidden Payload" Theory

For any spacecraft to carry a hidden deflection payload, it would need:
1. **Concealed mass** -- mass budgets for spacecraft are tightly constrained and publicly documented
2. **Undisclosed propulsion** -- would need to be hidden from ground tracking
3. **Additional guidance systems** -- autonomous targeting requires known hardware
4. **Power budget** -- every watt is accounted for in thermal models

None of the missions reviewed show any evidence of unexplained mass, power, or capability margins that would suggest a hidden deflection payload. Spacecraft mass budgets are publicly documented to the kilogram level and verified by launch vehicle providers.

---

## 6. PHYSICS OF ASTEROID DEFLECTION -- WHAT IT ACTUALLY REQUIRES

### Fundamental Equation
**Momentum transfer: p = m * v**
- p = momentum (kg*m/s)
- m = impactor mass (kg)
- v = impact velocity (m/s)

**Velocity change to asteroid: delta_V = (beta * m_impactor * v_impact) / M_asteroid**

Where beta is the momentum enhancement factor from ejecta (DART measured beta ~3.6).

### Deflection Requirements by Asteroid Size

For a deflection to prevent Earth impact, the asteroid's trajectory must be shifted by at least 1 Earth radius (~6,371 km) at the time of closest approach.

Required delta-V (approximate, assuming 10-year warning time):
| Asteroid Diameter | Asteroid Mass (approx) | Required delta-V | Required Momentum | Feasible with Single Kinetic Impactor? |
|-------------------|----------------------|-------------------|-------------------|---------------------------------------|
| 50 m | ~1.6 x 10^8 kg | ~1 cm/s | ~1.6 x 10^6 kg*m/s | YES -- DART-class spacecraft sufficient |
| 140 m | ~3.6 x 10^9 kg | ~1 cm/s | ~3.6 x 10^7 kg*m/s | YES -- multiple DART-class or single larger impactor |
| 300 m | ~3.5 x 10^10 kg | ~1 cm/s | ~3.5 x 10^8 kg*m/s | Challenging -- requires very large impactor or multiple impacts |
| 500 m | ~1.6 x 10^11 kg | ~1 cm/s | ~1.6 x 10^9 kg*m/s | Very difficult with kinetic impact alone |
| 1 km | ~1.3 x 10^12 kg | ~1 cm/s | ~1.3 x 10^10 kg*m/s | NOT feasible with kinetic impact; nuclear standoff required |
| 10 km | ~1.3 x 10^15 kg | ~1 cm/s | ~1.3 x 10^13 kg*m/s | NOT feasible; requires nuclear or other advanced methods |

### Deflection Methods Ranked by Effectiveness

1. **Nuclear standoff detonation** -- most effective for large asteroids; vaporizes surface material creating propulsive jet; can deliver ~10^17-10^18 kg*m/s equivalent momentum change; only method viable for >500 m asteroids with short warning times
2. **Kinetic impactor** -- DART demonstrated this; effective for <300 m asteroids with >10 year warning; scalable by using heavier spacecraft or higher velocities; enhanced by ejecta (beta > 1)
3. **Gravity tractor** -- spacecraft hovers near asteroid, using gravitational attraction to slowly tug it; requires years to decades; effective for very small bodies or as fine-tuning after kinetic impact
4. **Ion beam deflection** -- directing ion engine exhaust at asteroid surface; slow but continuous
5. **Mass driver** -- landing on asteroid and ejecting surface material; never demonstrated
6. **Solar concentrator/laser ablation** -- vaporizing surface material using focused sunlight or laser; conceptual only

### Key Physical Constraints
- **Warning time is the dominant factor.** A tiny velocity change applied 20 years early is worth more than a huge impulse applied 6 months before impact.
- **No existing spacecraft (other than DART) was designed for deflection.**
- **No classified deflection missions are publicly documented.** While nuclear standoff capability exists in theory (nuclear warheads exist; delivery to an asteroid is an engineering challenge, not a physics one), no dedicated asteroid-deflection nuclear mission has been built or launched.

---

## 7. HIDDEN PAYLOAD FEASIBILITY ANALYSIS

### Could Any Reviewed Mission Carry a Hidden Deflection Payload?

For each mission, examining whether unexplained mass/power margins exist:

| Mission | Total Mass Budget Accounted? | Unexplained Mass Margin | Could Hide Impactor Payload? |
|---------|------------------------------|------------------------|------------------------------|
| DART | Yes -- every kg documented for impact mass calculation | No -- mass directly affects mission outcome metric | No -- this WAS the impactor |
| OSIRIS-REx | Yes -- 2,110 kg fully documented (880 dry + 1,230 propellant) | Margins within normal spacecraft design (~5-10%) | No significant unexplained mass. TAGSAM was the payload. |
| Lucy | Yes -- 1,550 kg documented | No | No |
| Psyche | Yes -- 2,747 kg documented, 1,085 kg is xenon propellant | No | No |
| Hayabusa2 | Yes -- 600 kg documented | No | No -- SCI was openly declared |
| Rosetta | Yes -- 2,900 kg fully documented | No | No |
| Deep Impact | Yes -- impactor mass specifically documented for science | No | The impactor WAS the payload |
| Hera | Yes -- 1,128 kg documented | No | No |

### Power Budget Analysis
- Spacecraft power budgets are designed with margins of ~10-20% for contingencies
- These margins are consumed by thermal management, aging solar cells, and operational flexibility
- No mission shows a power surplus consistent with operating undisclosed active systems
- All instrument suites are publicly documented and their power draws are published

### Communications Analysis
- All missions use standard deep space network (DSN) communications
- Communications schedules and data rates are publicly documented
- No evidence of covert communication channels

### Assessment
There is NO credible evidence that any reviewed spacecraft carries hidden deflection hardware. The mass budgets, power budgets, and communication systems are fully documented and mutually consistent. Spacecraft are designed under intense weight constraints -- every kilogram costs thousands of dollars to launch, creating strong incentives to document and justify all mass.

---

## 8. KEY SOURCES TABLE

| Source | Type | Missions Covered | Key Data |
|--------|------|-------------------|----------|
| Cheng et al. 2023, Nature (doi:10.1038/s41586-023-05878-z) | Peer-reviewed paper | DART | Beta factor = 3.61, delta-V = 2.70 mm/s |
| NASA DART Mission page (dart.jhuapl.edu) | Official mission site | DART | Spacecraft specs, mission design |
| NASA NSSDCA Spacecraft Database (nssdc.gsfc.nasa.gov) | Official database | All NASA missions | Spacecraft parameters |
| ESA Rosetta Factsheet (esa.int) | Official factsheet | Rosetta/Philae | Mass, instruments, propulsion |
| ESA Hera Mission Overview (esa.int) | Official mission site | Hera | Spacecraft specs, timeline |
| eoPortal (eoportal.org) | Technical database | Multiple | Detailed spacecraft specifications |
| Gunter's Space Page (space.skyrocket.de) | Technical database | Multiple | Launch masses, propulsion details |
| JAXA Hayabusa2 instruments page (global.jaxa.jp) | Official site | Hayabusa2 | Instrument details, SCI specifications |
| JPL Psyche Quick Facts (jpl.nasa.gov) | Official site | Psyche | Mass, propulsion, mission timeline |
| NASA Science mission pages (science.nasa.gov) | Official | Multiple | Mission overviews |
| The Planetary Society (planetary.org) | Educational | Multiple | Mission summaries, context |
| SpaceNews (spacenews.com) | News | NEO Surveyor, Tianwen-2 | Launch dates, status updates |
| NASASpaceFlight.com | News | Tianwen-2 | Launch coverage |
| NASA NTRS (ntrs.nasa.gov) | Technical reports | DART, OSIRIS-APEX | Detailed technical papers |
| arXiv | Preprints | Multiple | Technical details on Hera instruments |

---

## 9. ASSESSMENT

### Summary of Findings

1. **DART is the ONLY mission that has demonstrated actual asteroid deflection.** It successfully changed Dimorphos's orbital period by 33 minutes through a kinetic impact at 6.14 km/s. The momentum enhancement factor (beta = 3.61) showed that ejecta from the rubble-pile target significantly amplified the deflection beyond what the spacecraft's own momentum would have achieved.

2. **Deep Impact and Hayabusa2's SCI demonstrated impact technology** on solar system bodies (comet and asteroid respectively), but at scales that produced no measurable orbit change on their targets. These missions provided technology heritage that informed DART's design.

3. **No other reviewed mission was designed for, capable of, or intended for asteroid deflection.** This includes OSIRIS-REx/APEX, Lucy, Psyche, Rosetta, Stardust, Hera, NEAR Shoemaker, Dawn, NEOWISE, NEO Surveyor, NEA Scout, Tianwen-2, and Comet Interceptor.

4. **The distinction between "could theoretically deflect" and "was designed to deflect" is critical:**
   - ANY spacecraft with mass and velocity can theoretically transfer some momentum to a target. But the delta-V produced on any asteroid larger than a few meters would be unmeasurably small for all non-DART missions.
   - Only DART was specifically engineered, targeted, and operated as a deflection demonstration.

5. **No evidence exists of hidden, classified, or dual-use deflection capability** in any of the reviewed missions. Mass budgets are fully documented and publicly available. There are no unexplained mass margins, power surpluses, or communication anomalies consistent with covert deflection hardware.

6. **For asteroids >500 m, kinetic impactors alone are insufficient** with realistic warning times. Nuclear standoff detonation remains the only theoretically viable method for large asteroid deflection, but no dedicated nuclear deflection mission has ever been built, launched, or (to public knowledge) seriously planned beyond conceptual studies.

7. **Planetary defense infrastructure is still nascent:**
   - Detection: NEO Surveyor (planned 2027-2028) will be the first dedicated NEO detection telescope
   - Assessment: Hera (arriving 2026) will characterize the DART impact outcome
   - Deflection: DART was a one-off demonstration. No operational deflection system exists
   - No standing capability to respond to a newly discovered impactor on short notice

8. **The cancelled Don Quijote mission (ESA)** and the original AIDA concept were the only other missions explicitly designed for deflection testing. Both were superseded by the DART/Hera combination.

### Capability vs. Intent Matrix

| Category | Missions |
|----------|----------|
| Designed AND demonstrated deflection | DART (1 mission only) |
| Designed for deflection but not executed | Don Quijote (cancelled), AIDA original concept (superseded) |
| Demonstrated impact technology (not deflection) | Deep Impact, Hayabusa2 SCI |
| Scientific observation only | OSIRIS-REx/APEX, Lucy, Psyche, Rosetta, Stardust, NEAR, Dawn, Hayabusa, Hera, Tianwen-2, Comet Interceptor |
| Detection/Survey only | NEOWISE, NEO Surveyor |
| Failed before reaching target | NEA Scout |

---

## 10. UNRESOLVED QUESTIONS

1. **DART beta factor precision:** Hera's arrival at Didymos (late 2026) will provide direct measurement of Dimorphos's mass and the impact crater, which will refine the beta factor from its current range of 2.2-4.9 to a precise value. This is the single most important pending measurement for planetary defense planning.

2. **Dimorphos post-impact shape:** Observations suggest Dimorphos may have been significantly reshaped by the DART impact. An anomalous ongoing orbital decay of Dimorphos's orbit has been reported. Hera will determine whether the impact fundamentally altered the body's structure.

3. **Scalability of kinetic impact:** DART deflected a 151 m moonlet. Would the same beta factor apply to a standalone asteroid? Would a larger rubble pile produce more or less ejecta per unit impact energy? These are open physics questions.

4. **Nuclear standoff capability gap:** No nation has built or tested a nuclear asteroid deflection device. While the physics is understood (ablation-driven momentum transfer), the engineering has never been validated in space. The gap between "nuclear weapons exist" and "we can deflect a large asteroid with a nuclear device" is significant.

5. **Short warning time scenarios:** All current deflection concepts assume years to decades of warning. For a newly discovered impactor with <1 year warning, no viable deflection method has been demonstrated. This remains the most dangerous gap in planetary defense.

6. **Chinese and other national capabilities:** CNSA's Tianwen-2 demonstrates growing Chinese capability in asteroid operations. Future Chinese planetary defense missions have been discussed but not formally announced. India (ISRO), South Korea (KARI), and other agencies have discussed asteroid mission concepts but none are in development as of mid-2026.

7. **Classified programs:** By definition, classified programs cannot be assessed from open sources. No publicly available evidence suggests any nation has built or deployed a covert asteroid deflection capability. The physics requirements (large spacecraft, high velocity, long lead time) make truly covert operations extremely difficult -- launch vehicles, tracking data, and orbital mechanics are observable by multiple independent parties worldwide.

8. **Gravity tractor viability:** No mission has ever demonstrated gravity tractor capability. The concept remains theoretical. OSIRIS-REx's extended proximity operations at Bennu provide the closest analog to the station-keeping requirements, but no deliberate gravitational tug was attempted or measured.

---

*Research compiled by Agent 06 -- Spacecraft Mission Research*
*Sources: NASA, ESA, JAXA, CNSA official documentation; peer-reviewed literature (Nature, Planetary Science Journal); mission databases (eoPortal, NSSDCA, Gunter's Space Page); news sources (SpaceNews, NASASpaceFlight.com)*
