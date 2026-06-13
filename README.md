# Authzed

Authzed is a SpiceDB-based authorization platform providing REST and gRPC APIs for Zanzibar-style relationship-based access control. It enables developers to manage schemas, write relationship tuples, and execute fine-grained permission checks at scale. Authzed Cloud delivers hosted SpiceDB infrastructure with pay-as-you-grow billing, processing tens of billions of permission checks daily across enterprise and AI-native applications.

**Website:** https://authzed.com  
**Documentation:** https://authzed.com/docs  
**GitHub Org:** https://github.com/authzed  
**Pricing:** https://authzed.com/pricing  
**Status:** https://status.authzed.com/  
**Blog:** https://authzed.com/blog  
**LinkedIn:** https://www.linkedin.com/company/authzed  
**X:** https://twitter.com/authzed  

## APIs

- **SpiceDB Permissions API** — gRPC and HTTP/JSON interface for CheckPermission, WriteRelationships, LookupResources, LookupSubjects, ReadRelationships, DeleteRelationships, WriteSchema, and ReadSchema operations
- **Authzed Cloud API** — Managed cloud with Restricted API Access, service account role policies, and multi-region SpiceDB infrastructure

## Client Libraries

| Language | Repository |
|----------|------------|
| Go | https://github.com/authzed/authzed-go |
| Node.js | https://github.com/authzed/authzed-node |
| Python | https://github.com/authzed/authzed-py |
| Ruby | https://github.com/authzed/authzed-rb |
| Java | https://github.com/authzed/authzed-java |
| .NET | https://github.com/authzed/authzed-dotnet |

CLI tool: https://github.com/authzed/zed

## Files

| File | Description |
|------|-------------|
| `apis.yml` | APIs.json 0.19 index |
| `plans/authzed-plans-pricing.yml` | Pricing plans (Open Source, Cloud, Dedicated, Self-Hosted) |
| `rate-limits/authzed-rate-limits.yml` | Per-operation limits and throughput figures |
| `finops/authzed-finops.yml` | FinOps Framework 1.0 FOCUS-aligned cost guidance |
