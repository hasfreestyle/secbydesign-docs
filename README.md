# secbydesign-docs

SecByDesign AI – Official Documentation, Support & Privacy Policy
Publisher: MHM DIGITAL SOLUTIONS

1. Documentation & User Guide
Overview
SecByDesign AI automates "Security by Design" and "Compliance by Design" assessments directly inside Jira Cloud issues. It helps Engineering, Security (CISO), and Compliance (DPO) teams identify technical vulnerabilities, regulatory obligations, and data residency risks before development begins.

Admin Configuration (Jira Administrators Only)
Open Jira Apps > SecByDesign AI - Admin & Policy (or click ⚙️ Admin Governance Settings inside any Jira ticket panel).
Select Mandatory Regulatory Framework:
EU (Europe): ISO/IEC 27001:2022 (A.8.25/A.8.26), GDPR Art. 25 & 32, NIS2 Directive, DORA, OWASP ASVS v4.0.
GCC (Middle East): UAE IA (TDRA), NESA/SIA, UAE Federal PDPL, ADGM/DIFC, KSA NCA ECC & CCC, SAMA Cyber Security Framework, KSA PDPL (SDAIA), Qatar NIA/QCB.
US & Global SaaS: AICPA SOC 2 Type II (CC6/CC7/CC8), NIST CSF 2.0 / SP 800-53, CCPA/CPRA, HIPAA, PCI-DSS v4.0.
Select AI Engine & Sovereignty Mode:
Built-in SecByDesign Cloud: Ready to use out-of-the-box (up to 1,000 audits/month included).
BYOK (Bring Your Own Key): Connect your corporate Mistral AI (EU Sovereign), OpenAI, Anthropic Claude, or Google Gemini API key for unlimited audits under your own enterprise data agreement.
Custom Enterprise Architecture Rules: Define internal rules (e.g., mandatory Keycloak OIDC, sovereign cloud hosting) to enforce them across every ticket audit.

Running an Audit & Generating Compliance Evidence
Open any Jira issue and click the SecByDesign AI panel.
Click 🛡️ Run Security & Compliance Audit.
Review the Readiness Score (0–100), Risk Level, Security by Design Controls, and Compliance & Data Sovereignty Rules.
Click 📥 Post Official Audit Stamp to Ticket Comments to record a timestamped compliance table in the issue comments for ISO 27001, SOC 2, GDPR, or NCA/UAE IA auditors.

2. Privacy & Data Security Policy
Effective Date: October 2026

Data Accessed: SecByDesign AI only accesses the Summary and Description of a Jira issue when an authorized user explicitly triggers an audit.
Data Storage & Persistence: Audit results, organization policy settings, and encrypted BYOK API keys are stored exclusively inside Atlassian Forge hosted storage (KVS) within your Atlassian Cloud tenant. MHM DIGITAL SOLUTIONS does not operate any external database and never stores your Jira ticket contents on its own servers.
AI Processing: When an audit is triggered, the issue summary and description are transmitted over encrypted TLS 1.3 to the selected AI provider (Google Gemini API by default, or the customer's configured OpenAI, Mistral AI, or Anthropic endpoint) solely to generate the real-time security assessment. Data is not used to train foundation models.
Data Deletion: Uninstalling SecByDesign AI removes app access immediately, and all data stored in Atlassian Forge KVS follows Atlassian Cloud data retention and deletion policies.

3. Customer Support & SLA
Vendor: MHM DIGITAL SOLUTIONS

Support Channel (Email):  hassenmeddeb@gmail.com
Support Hours: Monday to Friday, 9:00 AM – 6:00 PM CET (Paris) / GST.
Response Time SLA: Within 24 business hours for all inquiries, bug reports, and enterprise compliance questions.
