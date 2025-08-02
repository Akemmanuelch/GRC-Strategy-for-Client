# Section 2: Risk Assessment Findings

## 2.1 Key Risks Identified

| Risk                   | Likelihood | Impact | Priority |
|------------------------|------------|--------|----------|
| Data Breaches (Encryption gaps) | High       | High   | High     |
| Third-Party Vendor Risks       | High       | High   | High     |
| Non-Compliance Penalties       | Moderate   | High   | High     |
| Incident Response Gaps         | Medium     | High   | High     |

---

## 2.2 Risk Details and Mitigation Steps

| Risk                      | Details                                                                 | Mitigation Steps                                                                 |
|---------------------------|-------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| Data Breaches             | Outdated encryption protocols for stored cardholder data.              | Update encryption keys; use HSM for secure key management.                       |
| Third-Party Vendor Risks  | Vendor lacks SOC 2 certification for cloud storage.                    | Request vendor compliance or transition to certified providers.                  |
| Non-Compliance Penalties  | Incomplete GDPR DPIA documentation; slow handling of CCPA requests.    | Automate DPIA and privacy workflows; assign DPO; review consent management.      |
| Incident Response Gaps    | No recent tabletop drills; email-only reporting delays resolution.     | Schedule tabletop exercises; implement real-time ticketing system.               |
