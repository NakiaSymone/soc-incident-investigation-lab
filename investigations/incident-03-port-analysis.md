# Incident 03: Network Connection and Port Activity Analysis

## Alert Summary
Active network connections and listening ports were reviewed to assess system network activity and identify any unusual or unnecessary services.

---

## Investigation Process
The following analysis steps were performed:

- Executed `lsof -i` to identify active network connections and listening services
- Reviewed established and listening connections for expected system behavior
- Analyzed running applications communicating over the network

---

## Evidence Collected
- Active network connections identified using `lsof -i`
- Multiple established and listening connections observed
- No unknown or untrusted external connections identified during review
- Screenshot evidence stored in repository for validation

---

## Analysis
Observed network activity is consistent with normal system operations. Applications such as system services and user applications maintain expected network connections.

No indicators of suspicious services, unauthorized listening ports, or abnormal external communication were identified.

---

## Risk Assessment
**Risk Level: Low to Medium**

While no active threats were detected, open network connections should always be monitored to ensure no unauthorized services are running.

---

## Recommendation
- Periodically review active network connections
- Disable unnecessary network services where possible
- Monitor for unfamiliar external IP connections
- Ensure firewall rules are properly configured
