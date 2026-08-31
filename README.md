# Huawei MA5608T Monitoring — Zabbix + Grafana

Dashboard de monitoramento para OLT Huawei MA5608T utilizando Zabbix, SNMP e Grafana.

## 📊 Sobre o projeto

![Dashboard Huawei MA5608T](screenshots/dashboard-overview.png)

Este projeto foi desenvolvido para monitoramento de uma OLT Huawei MA5608T, permitindo acompanhar métricas operacionais e de hardware através do Zabbix e visualizar os dados em um dashboard no Grafana.

### Principais métricas monitoradas

- CPU das placas
- Temperatura dos FANs
- Rotação dos FANs
- Uptime da OLT
- Status dos uplinks
- ONUs online por porta PON
- Status das portas PON
- Tráfego Bits In / Bits Out
- Potência TX
- BIAS
- Estado do laser
- Temperatura
- Voltagem

## 🛠 Tecnologias

- Zabbix
- Grafana
- SNMP
- Linux
- Huawei MA5608T
- GPON

## 📁 Estrutura

```text
Monitoramento-OLT-Huawei-MA5608T/
├── README.md
├── LICENSE.txt
├── zabbix/
├── grafana/
└── docs/
    └── installation.md
```
