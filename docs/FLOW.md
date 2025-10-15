## Flow
```mermaid
sequenceDiagram
  participant Sentinel
  participant LogicApp
  participant Teams
  Sentinel->>LogicApp: Incident trigger (webhook)
  LogicApp->>Teams: Adaptive Card (summary + links)
```
