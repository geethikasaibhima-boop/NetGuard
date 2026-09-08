# NetGuard – Network Intrusion Detection System

## 📌 Project Overview

NetGuard is a Network Intrusion Detection System (NIDS) and log analysis project designed to monitor network traffic, detect suspicious activities, centralize security alerts, and support incident response.

The project uses Wireshark for network traffic analysis, Snort 3 for intrusion detection, and the ELK Stack for centralized log monitoring and visualization.

## 🎯 Objectives

- Capture and analyze network traffic
- Detect suspicious network activities using custom Snort rules
- Integrate Snort alerts with an ELK-based SIEM
- Monitor security alerts through Kibana
- Simulate incident response activities
- Document the complete detection and response workflow

## 🏗️ Architecture

```text
Network Traffic
      ↓
   Wireshark
      ↓
    Snort 3
      ↓
 Custom Snort Rules
      ↓
  Snort Alert Logs
      ↓
    Logstash
      ↓
 Elasticsearch
      ↓
     Kibana
      ↓
Threat Monitoring & Incident Response
