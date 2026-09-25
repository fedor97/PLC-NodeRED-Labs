# PLC-NodeRED-Labs

Hands-on PLC and Node-RED labs using CLICK PLC, Allen-Bradley Micro820, Modbus RTU, EtherNet/IP, CIP, dashboards, and industrial automation exercises.

## Contents

```
flows/
  lab01-dashboard-flow.json              Node-RED flow export — dashboard UI scaffolding (ui-template/group/page/theme)
  lab02-renewable-energy-bms-flow.json   Node-RED flow export — "Lab 02: Renewable Energy BMS" dashboard
```

## Importing a flow

1. Open the Node-RED editor.
2. Menu (☰) → Import → select a file from `flows/`.
3. Deploy.

## Status

These are early dashboard-layout exports (UI nodes only — no wired logic yet: no Modbus/MQTT/function nodes). Real PLC I/O wiring (CLICK PLC via Modbus RTU, Micro820 via EtherNet/IP/CIP) is not yet included.

## Roadmap

- [ ] Wire lab01 to live CLICK PLC tags over Modbus RTU
- [ ] Wire lab02 (Renewable Energy BMS) to live I/O
- [ ] Micro820 EtherNet/IP + CIP example lab
- [ ] Dashboard screenshots
