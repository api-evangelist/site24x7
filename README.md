# Site24x7

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
