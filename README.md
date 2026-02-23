# API Monitoring Dashboard

## Pages & Features

### 1. Dashboard
- Global health status (all APIs at a glance)
- Uptime percentage cards per API
- Response time chart (P50, P95, P99)
- Active incidents banner
- Error rate trends

### 2. Monitors
- Monitor list with status (up, degraded, down)
- Create monitor (URL, method, interval, expected status)
- Monitor detail: uptime chart, response time history, logs
- Health check configuration (timeout, retries, headers)
- SSL certificate expiry monitoring
- Pause / resume monitors

### 3. Incidents
- Active & past incidents list
- Incident detail: timeline, affected monitors, root cause
- Create / acknowledge / resolve incident
- Incident severity levels (minor, major, critical)
- Post-mortem notes

### 4. Status Page (Public)
- Public status page for end users
- Per-service status indicators
- Incident history & updates
- Scheduled maintenance announcements
- Subscribe to updates (email / webhook)

### 5. Alerts
- Alert rules per monitor (down for X minutes, slow response)
- Notification channels (email, Slack, Discord, SMS, webhook)
- Escalation policies
- Alert history & acknowledgment
- On-call rotation scheduling

### 6. Logs & History
- Request / response log per check
- Filter by status code, response time, date
- Detailed inspection (headers, body, timing)
- Error pattern detection

### 7. Multi-Location
- Check from multiple geographic locations
- Per-location response time comparison
- Location-specific alerting

### 8. Reports
- Uptime report by period (daily, weekly, monthly)
- SLA compliance tracking
- Response time trends & degradation
- Incident frequency analysis
- Export as PDF / CSV

### 9. Settings
- Team management & notification routing
- Global alert defaults
- Status page customization (branding, domain)
- API key management
- Integration settings (PagerDuty, OpsGenie)
