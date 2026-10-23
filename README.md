# Dinesh Kumar G

Automation engineer and founder of [ElectronIx](https://electronix.co.in), Coimbatore, India.

I design the panel, program the PLC and write the software that runs your machines. Nine years of industrial automation (PLC and HMI programming, EPLAN panel design, CNC retrofits, machine vision, test rigs, OEE and traceability), and now industrial software in Rust.

## In production

**[ElectronIx DNC](https://electronix.co.in)**: CNC program transfer and drip-feed for Fanuc machines, over Ethernet (FTP) or RS-232 through serial-to-Ethernet converters. One ordinary Windows PC runs about 25 machines with a headless Rust service, over-the-air updates and Ed25519-signed licences. Running on 23 CNC machines at a precision engineering company in Coimbatore. Source is private; signed builds are in [electronix-dnc-releases](https://github.com/Dinesh417G/electronix-dnc-releases).

## Open repositories

| Project | What it does | Stack |
|---|---|---|
| [ElectronIx Tool Store](https://github.com/Dinesh417G/Electronix_tools_store) | Tool-crib software for a CNC tooling store. A fingerprint door terminal identifies the person, they scan items in or out, and an append-only ledger keeps stock on hand and raises low-stock alerts. | Rust, PostgreSQL, TypeScript |
| [ElectronIx Trace](https://github.com/Dinesh417G/Traceability) | Product traceability for manufacturers. Scan a unit and get its full history: parts and lots, process data, operator, machine and test results. Backward and forward (recall) trace. | Rust, PostgreSQL, sqlx |
| [Vision inspection engine](https://github.com/Dinesh417G/Electronix_Vision) | Golden-image inspection that decides OK or NOT-OK for every camera frame. One core runs on a bare-metal microcontroller (no_std), a Raspberry Pi or Jetson, and a PC. | Rust, embedded-hal, MQTT |
| [ElectronIx MES](https://github.com/Dinesh417G/Electronix_MES) | OEE, downtime Pareto, work orders, scheduling, traceability, quality and preventive maintenance for Indian MSMEs. Offline-first edge box per plant, multi-plant cloud. | Rust, Tauri 2, MQTT |
| [ElectronIx Trace website](https://github.com/Dinesh417G/Electronix_traceability_site) | The site for ElectronIx Trace, with 179 Playwright tests on desktop and mobile. [Live](https://electronix-trace-site.vercel.app) | Next.js 16, React 19, Tailwind CSS v4 |
| [RustClass](https://github.com/Dinesh417G/Rust_vedio) | Offline-first desktop classroom for Windows: author a course, then study it. No accounts, no server, no telemetry. | Rust, Tauri |
| [memory-ball](https://github.com/Dinesh417G/Memory_ball) | An append-only graph memory engine. Memories are strands wound onto balls; you recall by rolling the graph. | Rust |

## Private, demo on request

- **ElectronIx Link** (in development): machine monitoring, diagnostics and PLC program backup. A small PLC block (CODESYS first) or a per-machine address map, a Rust edge agent with outbound-only connections, and a read-only web portal with OEE, alarms and a backup vault.
- **ElectronIx Store**: an online store for industrial electrical hardware that checks a panel builder's order for missing parts (ferrules, end sleeves, terminal blocks) before payment. Next.js storefront, rule engine ported to a Rust API.
- **ElectronIx Digital SOP** (in development): touch work-instruction terminals on the line, driven by the model number the line HMI writes over Modbus TCP.

## What I work with

- **PLCs:** Siemens S7-1200/1500 (TIA Portal), Allen Bradley (Studio 5000), Omron NX102 (Sysmac Studio), Mitsubishi, Delta, CODESYS
- **HMI and SCADA:** Weintek EasyBuilder Pro, Siemens WinCC
- **CNC controls:** Fanuc, Siemens 828D, Fagor 8055i
- **Design:** EPLAN Electric P8, AutoCAD Electrical, SolidWorks
- **Protocols:** Profinet, EtherNet/IP, IO-Link, Modbus RTU/TCP, OPC UA, MQTT, Fanuc FOCAS, FTP, RS-232 DNC
- **Software:** Rust (Tauri 2, Axum, Tokio), PostgreSQL, MySQL, TypeScript, Embedded C

## Contact

[LinkedIn](https://www.linkedin.com/in/dinesh417/) · [electronix.co.in](https://electronix.co.in)
