<!--
Org Profile README
Repo name must be: .github
File path must be: profile/README.md
-->

<div align="center">

# Aalberts HFC

Engineering organization focused on connected hydronic systems, digital building solutions,
and energy management technologies.

</div>

---

## 📘 Engineering Knowledge Base (start here)

The **Aalberts Digital Buildings Knowledge Base** is the central, version-controlled source of truth
for Digital Buildings engineering knowledge.

👉 **[Aalberts Digital Buildings Knowledge Base](https://github.com/aalbertshfc/aalberts-digital-buildings-knowledge-base)**

It contains:
- System and platform architecture
- Device landscape and ownership
- Communication protocols (LoRaWAN, Modbus, MQTT, …)
- OTA, bootloader and recovery procedures
- Integration patterns (southbound / northbound)
- Architectural decision records (ADRs)

**Information not documented there should not be treated as authoritative.**

---

## What we do
- **Connected hydronic devices**: Thermostatic heads, sensors, and embedded control platforms.
- **Digital building integration**: EMS/BMS connectivity and interoperability.
- **Energy management systems**: Monitoring, control, and optimization of thermal energy assets.

---

## Current focus areas
- **LoRaWAN thermostatic heads**: Connected radiator control and telemetry.
- **Smart Heat Vault**: Monitoring and control of thermal storage systems.
- **Cloud integration tooling**: Data pipelines, testing tools, and automation.

---

## Key repositories

### LoRaWAN thermostatic devices
- **[LoRa Radiator Valve Testbench](https://github.com/aalbertshfc/lora-radiator-valve-testbench)** &rarr; End-to-end testing and validation tooling.

- **[LoRa Radiator Encoder / Decoder](https://github.com/aalbertshfc/lora-radiator-valve-encoder-decoder)**  &rarr; Payload formats and protocol handling.

### Smart Heat Vault
- **[Smart Heat Vault Testing Tool](https://github.com/aalbertshfc/smart-heat-vault-testing-tool)**  &rarr; Validation and system-level testing utilities.

---

## Engineering principles
- **Source of truth in Git** — documentation is versioned and reviewed.
- **Device-first architecture** — systems are designed from field constraints upward.
- **Interoperability by design** — preference for open and documented protocols.
- **Docs are a feature** — ADRs and runbooks are mandatory for critical changes.
- **Decisions are traceable** — major technical choices are documented with context and rationale (ADRs).

---

## How to contribute
1. Start with the **Engineering Knowledge Base**.
2. Changes go through Pull Requests.
3. Major technical decisions require an ADR.
4. Keep documentation close to implementation and kept up to date.

