# Incident 02: DNS Resolution Investigation

## Alert Summary
Network connectivity and domain name resolution were tested following reports of potential access issues.

---

## Investigation Process
The following diagnostic steps were performed:

- Executed `nslookup` to verify DNS resolution for valid domains
- Performed `ping` tests to confirm network reachability
- Tested invalid domain resolution to observe DNS failure behavior

---

## Evidence Collected
- `nslookup google.com` successfully returned valid IP address
- `ping google.com` confirmed active network connectivity
- `nslookup fakeexample.invalid` returned expected failure (NXDOMAIN)
- Screenshot evidence captured and stored in repository

---

## Analysis
DNS resolution for valid domains is functioning normally. Network connectivity is stable, and no evidence of DNS outage or misconfiguration was observed.

The failed lookup for a non-existent domain confirms expected DNS behavior rather than a system issue.

---

## Risk Assessment
**Risk Level: Low**

No indicators of DNS compromise or service failure were identified during this investigation.

---

## Recommendation
- No immediate remediation required
- Continue monitoring DNS resolution if user-reported issues occur
- Verify DNS settings if future connectivity issues arise
