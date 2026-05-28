
# Incident 03: Port and Network Activity Analysis

## Description
Active network connections and listening ports were reviewed to identify potentially unnecessary or suspicious network activity.

## Evidence Collected
- Active network connections identified using lsof -i
- Multiple listening and established connections observed
- Screenshot evidence stored in repository

## Tools Used
- Terminal (macOS)
- lsof -i

## Analysis
Network analysis identified active applications and services communicating over the network. Open ports and established connections are expected during normal system activity, but unknown services should always be reviewed during investigations.

## Risk Level
Medium

## Conclusion
No immediately suspicious activity identified during review. Continued monitoring of unknown connections and exposed services is recommended.

## Recommended Actions
- Disable unused network services
- Monitor unfamiliar external connections
- Review firewall settings regularly
