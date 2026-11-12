# SDK — INSTRUMENT.Distortion

Every Distortion model this library drives, and how to drive it. Each model answers the same five verbs over HTTP (its own port), WebSocket, a Unix socket and the bus; one page per model below lists its routes and every command.

← [Manual and Artifacts](INDEX.md)

| Verb | What it does |
|---|---|
| `get` | reads one value |
| `set` | writes one value |
| `nab` | reads more than one thing (observation, telemetry) |
| `rig` | configures several arguments at once |
| `do` | executes an action; takes no value |

| Model | Maker | get | set | nab | rig | do | Port |
|---|---|---:|---:|---:|---:|---:|---:|
| [HP_8903B](SDK/HP_8903B.md) | HP / Agilent / Keysight | 288 | 670 | 289 | 0 | 45 | 15900 |
| [Porta_one](SDK/Porta_one.md) | Audio Precision | 288 | 670 | 289 | 0 | 45 | 15901 |
