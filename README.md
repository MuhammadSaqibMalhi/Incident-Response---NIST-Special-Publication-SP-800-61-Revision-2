# Incident-Response  NIST-Special Publication SP 800-61 Revision 2
NIST Incident Response Lifecycle  NIST SP 800-61 defines a four-phase incident response process:

## NIST Incident Response Lifecycle

NIST SP 800-61 defines a four-phase incident response process:

### 1. Preparation

Activities performed before an incident occurs:

* Establish incident response policies and procedures
* Define roles and responsibilities
* Build and train the incident response team
* Deploy security tools (SIEM, EDR, IDS/IPS)
* Create communication and escalation plans
* Conduct exercises and tabletop scenarios

### 2. Detection and Analysis

Identify and validate security incidents:

* Monitor security events and alerts
* Analyze logs and indicators of compromise (IOCs)
* Determine incident scope and impact
* Classify and prioritize incidents
* Document findings

Key questions:

* Is this truly an incident?
* What systems are affected?
* What is the business impact?

### 3. Containment, Eradication, and Recovery

#### Containment

Prevent further damage:

* Isolate affected systems
* Block malicious IPs/domains
* Disable compromised accounts
* Segment networks

#### Eradication

Remove the threat:

* Remove malware
* Close vulnerabilities
* Patch systems
* Reset credentials

#### Recovery

Restore operations:

* Rebuild systems if required
* Restore from backups
* Validate system integrity
* Return systems to production
* Monitor for reinfection

### 4. Post-Incident Activity (Lessons Learned)

After-action review:

* Conduct root cause analysis
* Assess response effectiveness
* Update procedures and controls
* Document lessons learned
* Improve detection and response capabilities

NIST recommends conducting a lessons-learned meeting shortly after the incident while details are fresh.

---

## Typical Incident Severity Classification

Organizations often align incidents to categories such as:

| Severity | Description                                        |
| -------- | -------------------------------------------------- |
| Critical | Major business disruption, ransomware, data breach |
| High     | Significant compromise of systems or accounts      |
| Medium   | Limited impact, contained quickly                  |
| Low      | Minor security events requiring investigation      |

---

## Common NIST Incident Response Roles

* **Incident Response Manager**
* **Incident Handlers/Analysts**
* **Forensic Specialists**
* **System Administrators**
* **Legal and Compliance Teams**
* **Communications/Public Relations**
* **Executive Management**

---

## Mapping to NIST Cybersecurity Framework (CSF 2.0)

Incident response activities primarily fall under:

* **GV (Govern)** – Policies and oversight
* **DE (Detect)** – Event monitoring and detection
* **RS (Respond)** – Response actions
* **RC (Recover)** – Recovery and restoration

---

### Quick Memory Aid

**Prepare → Detect & Analyze → Contain/Eradicate/Recover → Lessons Learned**

This is the core NIST incident response workflow used by many organizations and is often referenced in ISO 27001, SOC 2, and corporate cybersecurity programs.
