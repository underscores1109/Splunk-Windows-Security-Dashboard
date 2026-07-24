# Windows Security Monitoring Dashboard using Splunk

## Overview

This project demonstrates the use of Splunk Enterprise as a Security Information and Event Management (SIEM) solution for monitoring Windows Security Event Logs. The dashboard provides real-time visibility into authentication events, login trends, security event distribution, and potential brute-force attacks using Search Processing Language (SPL).

---

## Features

- Monitor Windows Security Event Logs
- Track successful and failed logins
- Display total security events
- Visualize login trends over time
- Identify top login users
- Analyze Windows Event ID distribution
- Detect potential brute-force login attempts
- View recent security events

---

## Technologies Used

- Splunk Enterprise 10.4.1
- Search Processing Language (SPL)
- Windows Event Logs
- Windows 11

---

## Dashboard Overview

![Dashboard Overview](screenshots/dashboard_overview.png)

---

## Dashboard Panels

### Total Security Events

![Total Security Events](screenshots/total_security_events.png)

### Total Successful Logins

![Total Successful Logins](screenshots/total_successful_logins.png)

### Total Failed Logins

![Total Failed Logins](screenshots/total_failed_logins.png)

### Successful Login Trend

![Successful Login Trend](screenshots/successful_logins_trend.png)

### Failed Login Trend

![Failed Login Trend](screenshots/failed_logins_trend.png)

### Top Login Users

![Top Login Users](screenshots/top_login_users.png)

### Event Distribution

![Event Distribution](screenshots/event_distribution.png)

### Recent Security Events

![Recent Security Events](screenshots/recent_security_events.png)

### Brute Force Detection

![Brute Force Detection](screenshots/brute_force_detection.png)

---

## SPL Queries

All SPL queries used to build the dashboard are available in the `spl_queries` folder.

---

## Project Structure

```
Splunk-Windows-Security-Dashboard/
│
├── README.md
├── LICENSE
├── screenshots/
├── spl_queries/
└── report/
```

---

## Future Improvements

- Real-time alerts
- Email notifications
- Scheduled reports
- Threat intelligence integration
- Detection of suspicious PowerShell activity
- Account lockout monitoring

---

## Author

**Bhargav Naidu**

Cybersecurity Student | SOC Analyst Enthusiast