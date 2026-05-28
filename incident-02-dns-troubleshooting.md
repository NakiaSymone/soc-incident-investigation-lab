
# Incident 02: DNS Troubleshooting Investigation

## Description
User experienced potential network name resolution issues. DNS functionality was tested using command-line tools to confirm connectivity.

## Evidence Collected
- nslookup google.com returned valid IP address
- ping google.com confirmed network connectivity
- nslookup fakeexample.invalid returned failed resolution (expected behavior)
- Screenshot evidence stored in repository

## Tools Used
- Terminal (macOS)
- nslookup
- ping

## Analysis
DNS resolution is functioning normally for valid domains. Failed lookup for invalid domain confirms DNS is properly rejecting non-existent entries. No evidence of DNS outage detected.

## Risk Level
Low

## Conclusion
No DNS-related incident detected. System name resolution is operating as expected.

## Recommended Actions
- No immediate action required
- Continue monitoring DNS performance if user complaints arise
