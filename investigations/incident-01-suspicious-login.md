# Incident 01: Suspicious Authentication Activity Investigation

## Alert Summary
Multiple authentication events were reviewed due to unusual login patterns observed in system activity logs.

---

## Investigation Process
The following steps were taken during analysis:

- Reviewed system login history using macOS terminal (`last`)
- Examined authentication-related system activity
- Identified repeated login attempts within a short timeframe

---

## Evidence Collected
- Multiple login attempts detected in system login history
- Timestamped authentication events reviewed for anomalies
- No confirmed successful unauthorized access identified
- Screenshot evidence stored in repository for validation

---

## Analysis
The observed login pattern may indicate repeated authentication attempts. However, no confirmed compromise or successful unauthorized access was detected based on available system evidence.

Possible explanations include:
- User credential entry errors
- Automated login attempts
- Brute-force behavior (not confirmed)

---

## Risk Assessment
**Risk Level: Medium**

At this time, there is no evidence of system compromise. However, repeated authentication attempts warrant continued monitoring.

---

## Recommendation
- Enable or verify account lockout policies
- Monitor future authentication logs for repeated failures
- Review remote login settings if enabled
- Continue logging authentication activity for anomaly detection

## Evidence Reference
Supporting screenshots and raw command outputs are stored in the `/screenshots` and `/logs` directories for validation and audit purposes. 
