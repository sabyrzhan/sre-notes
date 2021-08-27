# 📝 🤓 👨‍💻 Java developer's SRE notes
## SLI, SLO, SLA
- SLI (Service Layer Indicator) - defined quantitative measure of some 
  aspect of service that is provided. F.e., latency, RPS, percentiles etc.
- SLO (Service Layer Objective) - target value or range of values for a
  service which are measured by SLI. F.e., latency <= 10s,
  yearly uptime <= 99.99%
- SLA (Service Layer Agreement) - explicit contract between your users, 
  that includes consequences of meetings (or missings) of SLOs of the services

## LCE - Launch Coordination Engineer
LCE consists of SRE engineers from all related products and have most experience.
Their first responsibility is to provide appropriate domain knowledge before launching
the product. The domain knowledge consists from checklist that includes launch requirements:
- compliance with company standards and best practices, provide actions to improve reliability
- connecting and synchronizing the teams from related products
- driving technical aspects
- educate developers with best practices, guide to integrate or reuse existing services if
  exists, provide appropriate documentation and internal training resources
