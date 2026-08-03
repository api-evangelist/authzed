# Authzed

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
