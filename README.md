# 📝 🤓 👨‍💻 Java developer's SRE notes
## SLI, SLO, SLA
- SLI (Service Layer Indicator) - defined quantitative measure of some 
  aspect of service that is provided. F.e., latency, RPS, percentiles etc.
- SLO (Service Layer Objective) - target value or range of values for a
  service which are measured by SLI. F.e., latency <= 10s,
  yearly uptime <= 99.99%
- SLA (Service Layer Agreement) - explicit contract between your users, 
  that includes consequences of meetings (or missings) of SLOs of the service.s 
