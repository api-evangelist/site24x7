# Site24x7

Site24x7 is a full-stack cloud monitoring platform with a REST API for managing monitors, on-call schedules, alerts, SLAs, and accessing availability and performance metrics. The platform covers website uptime, server infrastructure, cloud services (AWS, Azure, GCP), application performance (APM), real user monitoring (RUM), network devices, databases, and synthetic transactions.

## Links

- **Website:** https://www.site24x7.com/
- **API Documentation:** https://www.site24x7.com/help/api/
- **GitHub:** https://github.com/site24x7
- **LinkedIn:** https://www.linkedin.com/company/site24x7
- **Blog:** https://www.site24x7.com/blog/
- **Pricing:** https://www.site24x7.com/site24x7-pricing.html
- **Status Page:** https://status.site24x7.com/
- **X / Twitter:** https://x.com/Site24x7

## APIs

Site24x7 provides a single REST API (v2.0) authenticated via OAuth 2.0 through the Zoho Developer Console. Major capability areas include:

- **Monitors** — Create, update, delete, and manage website, API, server, database, cloud, and synthetic transaction monitors
- **Monitor Groups & Subgroups** — Hierarchical organization of monitors
- **Current Status & Alerts** — Real-time health data and alert management
- **Availability & Performance Reports** — Historical metrics across custom time ranges
- **SLA Reports** — Availability, response time, and composite SLA tracking
- **On-Call Schedules** — Rotation-based alert escalation management
- **Notification Profiles** — Alert channel configuration (email, SMS, webhooks, Slack, PagerDuty, ServiceNow)
- **Threshold Profiles** — Performance baseline and anomaly configuration
- **IT Automation** — Triggered scripts and remediation actions
- **Maintenance Windows** — Scheduled downtime management
- **Users & Groups** — Role-based access control
- **Integrations** — Third-party webhook and SaaS tool connections
- **APM Insight** — Application performance tracing
- **RUM Applications** — Real user monitoring analytics
- **Cloud Services** — AWS (EC2, RDS, S3, Lambda, CloudFront, etc.), Azure, VMware resource monitoring
- **MSP & Business Units** — Multi-tenant account management
- **Audit Logs** — Activity tracking for compliance

## Authentication

OAuth 2.0 via the Zoho Developer Console. Access tokens expire after 3,600 seconds; use the permanent refresh token to regenerate them without user re-authentication.

Authorization header: `Authorization: Zoho-oauthtoken {access_token}`

## Regional Endpoints

Site24x7 operates dedicated API endpoints for: United States, Europe, India, Australia, Japan, Canada, United Kingdom, UAE, and Saudi Arabia.

## Maintainers

- Kin Lane (kin@apievangelist.com)
