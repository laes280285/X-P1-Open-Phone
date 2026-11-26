# X-P1 Open Phone — an affordable, DIY, clamshell Linux/Android phone?

[Español](README.md) · [Community call (English)](COMMUNITY_CALL_EN.md) · [Technical specs](docs/ESPECIFICACIONES.md) · [Preliminary BOM](docs/BOM.csv)

> **Concept / recruiting contributors. No working prototype exists yet.** Renderings are AI-generated design illustrations, not verified mechanical or electrical files. Dimensions, pricing, telephony compatibility, battery life, and software support are **not validated**.

**Concept renders pending upload.**

## What is X-P1?

A community-driven concept for a **folding electronic-dictionary-style phone** combining 4G calling, physical QWERTY keyboard, retro-gaming controls, Linux ARM / potential Android, two screens, and user-serviceable storage and battery.

The goal is a **low-cost, independently buildable open-hardware kit**, using parts available online (ideally AliExpress or widely accessible distributors), a custom carrier PCB ordered from a service like PCBWay, and a 3D printed or machined case that can be ordered or made locally. We want an honest bill of materials with pricing for one-off and small-batch builds, editable source files, and detailed assembly instructions—not a closed or vendor-locked product.

## Intended features

- 4G LTE **voice, SMS and data**; incoming calls **answered with the clamshell closed** through an exterior touch E-Paper screen, exterior earpiece and microphone. Carrier VoLTE support **must be tested**.
- 4-inch-ish internal touch IPS display, ~4.7-inch touch E-Paper exterior, inner and outer cameras.
- QWERTY keyboard, two recessed thumbsticks with L3/R3, scroll wheel, and four shoulder buttons **on the rear face of the LOWER BASE, not the upper display lid nor hinge spine**. Controls usable while open.
- Two inward-facing stereo speakers beside the main display, dedicated outside call earpiece, exterior/interior microphones and optional noise-cancel microphone.
- Wi-Fi, Bluetooth, FM radio, infrared and USB-C.
- **Removable protected 7,000 mAh battery pack** and **independently serviceable M.2 2230 NVMe SSD**; neither intended for hot swapping.
- Modular, documented electronics with a custom carrier board and a commercially available ARM compute module.
- Two finishes sharing identical geometry: silver/gray aluminum + plastic, and black with thin orange stripes / orange X-P1 logo.

## Proposed baseline (NOT validated)

- **Radxa CM5 RK3588S2 (8 GB RAM)**, optional eMMC for recovery/boot.
- **SIMCom SIM7600G-H** 4G modem candidate, subject to VoLTE/carrier and Android/Linux checks.
- **M.2 2230 NVMe** via an available CM5 PCIe interface, subject to power, lane allocation and boot strategy.
- Input / housekeeping MCU such as **RP2040**; ultra-low-power mode and E-Paper control to be researched.
- ~**163 × 100 × 30–36 mm** closed: **unverified industrial-design target**, not a fitted CAD model.

## We need contributors!

Interested in **hardware PCB design, power electronics, battery safety, 4G VoLTE/RF, Linux/Android BSP, e-paper driver, keyboard/controls, CAD hinge/flex design, acoustic hardware, supply chain, manufacturing or testing**? We'd love your feedback—especially cost-saving alternatives and realistic BOM estimates.

See the [community collaboration request](COMMUNITY_CALL_EN.md), [open technical challenges](docs/RETOS_TECNICOS.md), and [development roadmap](docs/PLAN_DESARROLLO.md). Please do not purchase parts yet; there is no fundraising or pre-order campaign.

## Is there a community for DIY Linux phones?

Related projects such as [OURS Project](https://github.com/evanman83/OURS-project), [ZeroPhone](https://hackaday.io/project/19035), and [PulsePhone](https://github.com/pulseopen/PulsePhone) show there is an audience for open-hardware phones, but interest in X-P1 itself remains to be tested.

## Status, licensing and references

Everything here is a proposal, not an approved production design. Electrical CAD, PCB fabrication files, 3D mechanical CAD, firmware and tested build instructions **do not exist yet**. We intend to choose explicit open licenses **before collecting source-code/hardware contributions**; see [license decision](docs/LICENCIAS_PENDIENTES.md). No affiliation with suppliers or chip vendors.

Sources: [Radxa CM5](https://radxa.com/products/cm/cm5/) · [CM5 docs](https://docs.radxa.com/en/som/cm/cm5) · [SIMCom SIM7600-H](https://www.simcom.com/product/SIM7600X-H.html) · [LILYGO 4.7-inch E-Paper reference](https://github.com/Xinyuan-LilyGO/T5S3-4.7-e-paper-PRO) · [PCBWay 3D printing](https://www.pcbway.com/rapid-prototyping/3d-printing/)