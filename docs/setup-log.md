# Setup Log

## P0 - Kickoff & Setup

### P0-T01: Git repo
- Tạo repo: https://github.com/ThanhNhatt/minisoc-
- Cấu trúc thư mục khởi tạo xong

### P0-T02: Tailscale
- SOC Server (Ubuntu): 100.75.21.55
- Agent Windows (kongtuong): 100.89.183.81
- Agent Linux (congtuong04): 100.64.139.72

### P0-T03: Docker
- Docker: 29.1.3
- Docker Compose: 1.29.2
- Service: active (running)

### P2-T01: Windows Agent
- Agent name: windows-agent
- Agent IP: 100.89.183.81
- Wazuh Agent version: 4.7.5
- Status: active ✅


### P1-T01,T02,T03: Wazuh Deploy
- Wazuh Manager: v4.7.5 - active ✅
- Wazuh Indexer: port 9200 - active ✅
- Wazuh Dashboard: port 443 - active ✅
- API: https://localhost:55000 - OK ✅
- API user: wazuh-wui
- Deploy method: Docker Compose

