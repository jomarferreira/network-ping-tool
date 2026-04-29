# 📡 Network Ping Tool

## 🇧🇷 Descrição
Conjunto de scripts em Python desenvolvidos para realizar testes de conectividade de rede através do comando ping.

O projeto permite verificar o status de um host (ativo/inativo) e executar múltiplos pings com quantidade definida, simulando ferramentas básicas de diagnóstico de rede.

---

## 🇺🇸 Description
A set of Python scripts designed to perform network connectivity tests using the ping command.

This project allows checking the status of a host (online/offline) and executing multiple pings with a defined count, simulating basic network diagnostic tools.

---

## 🚀 Funcionalidades | Features
- Verificação de status de um host (online/offline)  
- Execução de múltiplos pings com quantidade definida  
- Execução via terminal (CLI)  
- Geração de saída em arquivo (`ping.txt`)  
- Simulação de ferramentas de diagnóstico de rede  

---

## 🧠 Tecnologias utilizadas | Tech Stack
- Python  
- ping3  
- OS (system calls)  

---

## 📦 Pré-requisitos | Requirements
Antes de executar, instale as dependências:
```bash
pip install -r requirements.txt
```

---

## ▶️ Como executar | How to run
```bash
git clone https://github.com/jomarferreira/network-ping-tool.git
cd network-ping-tool
pip install -r requirements.txt
```

---

### Verificar status de um host | Check host status
```bash
python ping_status.py
```

---

### Executar múltiplos pings | Run multiple pings
```bash
python ping_count.py google.com 4
```