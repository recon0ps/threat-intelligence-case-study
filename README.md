# 🔍 Case Study — Multi-Asset Fraud Campaign

> **Disclaimer:** All domains, providers, brands, and sensitive indicators have been anonymized for portfolio purposes. No intrusive methods were used. The entire analysis was conducted based on passive reconnaissance and publicly observable artifacts.

---

## 📋 Executive Summary

This case study documents the passive OSINT analysis of a coordinated digital fraud operation leveraging multiple online assets, cloud-hosted infrastructure, social engineering channels, and payment funnels.

The operation used government-themed visual identity, deceptive narratives around registration/tax assistance, messaging platforms, and fake administrative interfaces to deceive victims and monetize generated traffic.

---

## 🚨 Key Findings

### 🔴 Critical
- Fraudulent operator/administrator portal hosted on a cloud provider
- Government impersonation campaign targeting Brazilian users
- Structured payment funnel for monetization

### 🟠 High
- Multiple coordinated subdomains with distinct roles in the campaign
- Simulated backend architecture mimicking legitimate services
- Infrastructure distributed across multiple providers

### 🟡 Medium
- Search engine suppression via `robots.txt`
- Soft 404 behavior in SPA (Single Page Application)
- Public exposure of deployment metadata

---

## 🛠️ Observed Technical Indicators

### Frontend / Application Behavior
- Local HTTP interception via mock libraries
- Embedded static JSON datasets
- Simulated balances, receipts, and dashboards
- No legitimate backend communication observed

### Infrastructure Patterns
- Public cloud hosting with rapid rotation capability
- Multiple domains with segmented roles in the campaign
- Payment checkout flows on separate assets
- Messaging channels for social engineering-based conversion

---

## 🔄 Campaign Funnel (Observed)

```
1. Acquisition    →  Organic search / app discovery
2. Engagement     →  Themed landing pages
3. Conversion     →  Messaging channels
4. Monetization   →  Payment requests
5. Operations     →  Fake administrative panel
```

---

## 🧩 Identified TTPs

| Technique | Description |
|---|---|
| Institutional Impersonation | Misuse of government visual identity |
| Social Engineering | Psychological manipulation to induce payments |
| Multi-Domain Campaign | Multiple assets with coordinated roles |
| Fake Interface | Simulated dashboards and receipts to build trust |
| Brand Confusion | Names and visuals similar to legitimate entities |
| Rapid Asset Rotation | Infrastructure prepared for quick replacement |
| Trust Laundering | Abuse of reputable provider infrastructure |

---

## 🛡️ Defensive Recommendations

- **Immediate takedown** of hosted malicious assets
- **Cross-provider coordination** for abuse reporting
- **Monitoring and blocklisting** of identified IOCs
- **User awareness** campaigns on impersonation themes
- **Continuous monitoring** of lookalike domains

---

## 🔬 Research Methodology

> **Passive OSINT Only** — no active or intrusive techniques were used.

- DNS / domain analysis
- HTTP response analysis
- Client-side artifact inspection
- Infrastructure correlation
- Attribution signals from open sources

---

## 💼 Demonstrated Skills

```
✔ Threat Intelligence         ✔ OSINT Investigation
✔ Infrastructure Correlation  ✔ IOC Development
✔ Fraud Analysis              ✔ Technical Reporting
✔ Campaign Mapping            ✔ Risk Assessment
```

---

## 📁 Repository Structure

```
📦 threat-intel-fraud-campaign/
 ┣ 📄 README.md          ← This file
 ┣ 📁 iocs/              ← Indicators of compromise (anonymized)
 ┣ 📁 analysis/          ← Analysis notes and artifacts
 ┗ 📁 reports/           ← Exported reports
```

---

## ⚠️ Disclaimer

This repository is **strictly educational and for portfolio purposes**. All sensitive identifiers have been removed or anonymized. None of the described techniques were applied actively, intrusively, or in violation of any system or service.

---

<p align="center">
  <sub>Made with a focus on learning and ethics in offensive/defensive security 🔐</sub>
</p>
