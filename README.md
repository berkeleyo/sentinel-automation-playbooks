
# Microsoft Sentinel Automation Playbooks

Starter Logic App you can connect to incidents or scheduled alerts.

## Deploy
```bash
az deployment group create -g rg-sentinel -f playbooks/notify-teams.json -p logicAppName=la-notify-teams
```
