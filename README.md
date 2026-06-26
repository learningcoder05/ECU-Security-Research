# 🚗 ECU Security Research Lab

A personal research repository documenting my exploration of automotive ECU communication, CAN bus analysis, UDS diagnostics, and security testing concepts.

> Understanding vehicle systems by analyzing communication, behaviour, and protocols.

---

## 🎯 Objective

The goal of this repository is to document:

- ECU communication patterns
- CAN bus observations
- UDS service behaviour
- Diagnostic workflows
- Reverse engineering notes
- Security research methodology

---

## 🔬 Areas of Research

### CAN Bus

Topics explored:

- CAN frame structure
- Arbitration IDs
- Data field analysis
- Message behaviour
- Traffic observation

---

### UDS (Unified Diagnostic Services)

Research areas:

- Diagnostic sessions
- Service requests
- Negative Response Codes (NRC)
- ECU state transitions
- Request/response analysis

---

### DTC Analysis

Exploring:

- Diagnostic Trouble Codes
- Fault storage behaviour
- Reading and interpreting diagnostic information

---

### ECU Behaviour Analysis

Documenting:

- ECU responses
- Communication patterns
- Unexpected behaviours
- Testing observations

---

## 🛠 Tools Used

- Python
- CAN utilities
- cantools
- Caring Caribou
- Wireshark
- Linux tools

---

## 📂 Repository Structure

```text
ecu-security-research/
│
├── README.md
│   └── Overview and research documentation
│
├── docs/
│   ├── can-basics.md
│   ├── uds-notes.md
│   ├── dtc-analysis.md
│   ├── ecu-discovery.md
│   └── security-observations.md
│
├── captures/
│   ├── README.md
│   └── sample_logs/
│       └── CAN traffic captures
│
├── scripts/
│   ├── README.md
│   ├── can_parser.py
│   └── uds_helpers.py
│
├── findings/
│   ├── README.md
│   ├── finding_template.md
│   └── discovered_behaviour.md
│
└── images/
    └── diagrams/
```

## ⚠️ Disclaimer

This repository contains educational research and experiments performed on authorized hardware and test environments.

---

## 🚀 Future Work

- Deeper UDS analysis
- ECU firmware analysis
- Protocol automation
- Security testing methodologies
