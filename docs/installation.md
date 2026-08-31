# Guia de Instalação

Este documento descreve o processo de instalação e configuração do projeto de monitoramento da OLT Huawei MA5608T utilizando Zabbix, SNMP e Grafana.

## 1. Pré-requisitos

Antes de iniciar, certifique-se de possuir:

- OLT Huawei MA5608T com SNMP habilitado
- Servidor Linux
- Zabbix Server
- Grafana
- Plugin Grafana-Zabbix
- Comunicação SNMP entre o servidor Zabbix e a OLT

## 2. Arquivos do projeto

Os arquivos necessários estão organizados da seguinte forma:

```text
zabbix/
├── template-huawei-ma5608t.yaml
└── externalscripts/
    ├── pon.sh
    └── desprovisionadas.sh

grafana/
└── dashboard-huawei-ma5608t.json
```
