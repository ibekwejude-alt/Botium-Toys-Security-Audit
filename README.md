# Botium Toys: Internal Security Audit

## Project Overview
This project consists of a comprehensive internal security audit for **Botium Toys**, a fictional small business growing its online presence. The audit was conducted to assess the company's compliance with **NIST CSF**, **PCI DSS**, and **GDPR** standards.

## 🔍 Key Objectives
* Identify vulnerabilities in the company's current security posture.
* Assess compliance with international regulations (GDPR) and payment standards (PCI DSS).
* Recommend administrative, technical, and physical controls to mitigate risks.

## 🛠 Skills & Tools Used
* **Frameworks:** NIST Cybersecurity Framework (CSF).
* **Compliance:** GDPR (Data Privacy), PCI DSS (Payment Security).
* **Risk Management:** Risk Assessment, Threat Modeling, Asset Classification.
* **Controls Assessment:** Evaluating Administrative, Technical, and Physical controls.

## 📊 Key Findings
The audit revealed several critical gaps, including:
1.  **High Risk:** Lack of encryption (HTTPS) for online payments (PCI DSS Violation).
2.  **High Risk:** No Disaster Recovery Plan or automated backups.
3.  **Compliance Gap:** No privacy policy or cookie consent mechanism for E.U. customers (GDPR Violation).
4.  **Policy Gap:** Lack of "Separation of Duties" and "Least Privilege" policies.

## 📝 Recommendations
To address these risks, the following remediation strategy was proposed:
* **Immediate:** Implement TLS 1.2+ Encryption for all payment gateways.
* **Immediate:** Revoke administrative privileges for standard users.
* **Medium-Term:** Implement a Disaster Recovery Plan with daily off-site backups.
* **Medium-Term:** Update the website to include GDPR-compliant consent forms.

## 📂 Project Files
* **[Risk Assessment Report](Botium_Risk_Assessment.pdf.pdf):** The initial analysis of Botium Toys' scope, goals, and critical assets.
* **[Controls & Compliance Checklist](Botium_Controls_Checklist.pdf.pdf):** The audit findings, identifying specific gaps in PCI DSS, GDPR, and NIST controls.
---
*This project was completed as part of the Google Cybersecurity Professional Certificate.*
