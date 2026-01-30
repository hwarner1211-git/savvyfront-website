# SavvyFront Terms of Service (Draft V1.0)

**Effective Date:** [Date of Publication]

These Terms of Service ("Agreement") govern your use of the hosting services ("Services") provided by SavvyFront ("We," "Us," or "Our"), which are founded upon a resilient infrastructure utilizing Proxmox Virtualization and Ceph distributed storage. By ordering or using any Service, you agree to be bound by this Agreement.

## 1. Introduction & Acceptance
1.1. **Agreement:** You agree to adhere to these terms, our Acceptable Use Policy (AUP), and our Privacy Policy.
1.2. **Service Definition:** Services include VPS hosting environments configured on Our clustered infrastructure.
1.3. **Acceptable Use Policy (AUP):** You must adhere to the AUP located in Section 5 of this document/linked separately. Violations may result in immediate suspension.

## 2. Service Provision & Uptime
2.1. **Infrastructure Basis:** Services are provided utilizing a clustered environment based on Proxmox and Ceph storage to maximize reliability.
2.2. **Uptime Guarantee/SLA:** We guarantee 99.9% uptime, subject to the limitations detailed below. Service Level Agreement credits (if applicable) are managed via the Blesta billing system.
2.3. **Limitations of Guarantees:** The SLA does not cover downtime caused by: client application faults, client-side misconfiguration, scheduled maintenance windows (which We will attempt to keep under 1 hour per quarter), or Force Majeure events.

## 3. Billing, Payments, and Cancellations
3.1. **Pricing:** All pricing is managed through the Blesta billing system. Prices are subject to change with 30 days written notice.
3.2. **Payment Terms:** Payment is required in advance. Services are activated only upon successful payment processing by Blesta.
3.3. **Cancellation/Refunds:** We offer a 14-day money-back guarantee on new service setups. After this period, cancellation is effective upon request, and service terminates at the end of the paid billing cycle.
3.4. **Data Retention:** Upon termination (cancellation or breach), client data will be purged from the Ceph cluster within [X] days.

## 4. Data Responsibility & Backups
4.1. **Client Responsibility:** You retain 100% responsibility for the content, legality, and security of all data and applications hosted on your VPS.
4.2. **Backup Disclaimer:** Due to the nature of our high-availability cluster, while data is protected against hardware failure, **SavvyFront does not provide routine, client-level backups.** Clients are required to implement their own external backup strategy for critical data.

## 5. Limitation of Liability & Indemnification
We will not be liable for any indirect, incidental, special, consequential, or punitive damages, including lost profits, arising from the use of Services, except as explicitly covered by our SLA. You agree to indemnify and hold Us harmless from any claims arising from your use of the Services.

## 6. Termination of Service
We reserve the right to suspend or terminate service immediately without notice for severe breaches of the AUP or non-payment.

## 7. Acceptable Use Policy (AUP) - INCORPORATED BY REFERENCE
*See Section 5 below for the detailed AUP outline.*

---
***LEGAL WARNING: This is a draft outline. You must consult a legal professional to draft the final, binding TOS document.***

## Privacy Policy Outline
1.  <strong>Introduction:</strong>
    *   Who we are (SavvyFront) and what this policy covers.
2.  <strong>Information We Collect:</strong>
    *   <strong>Data Collected via Website:</strong> Browsing data (cookies, analytics - if used), contact forms.
    *   <strong>Data Collected via Blesta/Service:</strong> Name, email, billing address, payment tokenization status (Blesta handles card data, you hold account data).
    *   <strong>Data from Infrastructure:</strong> Basic server usage metrics (CPU/RAM load for Proxmox monitoring).
3.  <strong>How We Use Your Information:</strong>
    *   To provide the service (provisioning via Proxmox API).
    *   To process payments (via Blesta integration).
    *   For customer support.
4.  <strong>Data Sharing and Disclosure:</strong>
    *   Sharing with necessary subprocessors (e.g., Blesta itself, perhaps payment gateways).
    *   Legal requirements disclosure.
5.  <strong>Data Security:</strong>
    *   Measures taken to secure data (mentioning infrastructure hardening efforts).
6.  <strong>Your Rights (GDPR/UK Focus):</strong>
    *   Right to access, rectification, erasure ("right to be forgotten").

---
## Acceptable Use Policy (AUP) Outline for SavvyFront

<strong>CRITICAL WARNING:</strong> This is a boilerplate outline for structural planning. <strong>You must have a qualified legal professional review and finalize this document</strong> before it is published or enforced.

### 1. Prohibited Activities
Services provided by SavvyFront (powered by Proxmox/Ceph) must not be used for:
*   <strong>Illegal Activities:</strong> Any activity violating local, UK, or international laws (e.g., distributing malware, copyright infringement).
*   <strong>Spam and Unsolicited Communication:</strong> Sending mass unsolicited emails, hosting content for phishing, or running any service designed primarily for spamming.
*   <strong>Abuse of Resources:</strong> Running cryptocurrency mining operations (including Monero/XMR), mail relays, or any process that causes sustained, excessive load that impacts other cluster tenants (even with high availability, resources are shared).
*   <strong>Security Violations:</strong> Hosting malicious content, running botnets, or performing unauthorized scanning/attacking of other systems (including the Unraid host or other SavvyFront clients).
*   <strong>Content Restrictions:</strong> Hosting illegal pornography, terrorism-related material, or content promoting hate speech.

### 2. Data Responsibility & Backups
*   <strong>Client Responsibility:</strong> The customer is 100% responsible for the content, legality, and security of all data and applications running on their VPS.
*   <strong>Backup Disclaimer:</strong> While the infrastructure (Ceph) protects against hardware failure, <strong>SavvyFront does not provide routine, client-level backups.</strong> Clients must maintain their own backup strategy for their data, as data loss due to application error, misconfiguration, or client-side neglect is not covered under the Uptime SLA.

### 3. Service Suspension & Termination
*   <strong>AUP Violation:</strong> Any breach of this AUP will result in immediate suspension of service pending investigation, with full right to termination without refund if terms are violated.
*   <strong>Non-Payment:</strong> Services will be suspended immediately upon non-payment as managed by Blesta, and data purged after [X] days of non-payment.