# MATLAB

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

MATLAB is the MathWorks programming platform for engineers and scientists, and its interface surface is unusually split. Most of it is in-process language bindings — the MATLAB Engine APIs for Python, Java, C++, C, Fortran and .NET, the MEX API, the C++ Data API and the Compiler SDK — which embed MATLAB into other programs rather than exposing it over HTTP. Two surfaces are callable over the network: the ThingSpeak REST and MQTT APIs for IoT channel data, hosted by MathWorks, and the MATLAB Production Server RESTful API, which customers run themselves. On top of both sits a large first-party agent layer: the official MATLAB MCP Server and 212 published Agent Skills.

**Areas:** Data Analysis · Engineering · Machine Learning · Numerical Analysis · Scientific Computing

## MATLAB on APIs.io

Everything profiled for MATLAB is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/matlab/](https://apis.io/providers/matlab/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [MATLAB Engine API for Python](https://apis.io/apis/matlab/matlab-engine-api-for-python/) — Call MATLAB from Python, allowing Python programs to start MATLAB, execute MATLAB functions, and exchange data between Python and MATLAB.
- [MATLAB Engine API for Java](https://apis.io/apis/matlab/matlab-engine-api-for-java/) — Execute MATLAB functions from Java programs and exchange data between Java and MATLAB.
- [MATLAB Engine API for C++](https://apis.io/apis/matlab/matlab-engine-api-for-c/) — Call MATLAB from C++ programs with object-oriented programming support.
- [MATLAB Engine API for C and Fortran](https://apis.io/apis/matlab/matlab-engine-api-for-c-and-fortran/) — Call MATLAB from C and Fortran programs using the MATLAB engine library, enabling MATLAB as a computation engine for native applications.
- [MATLAB Engine API for .NET](https://apis.io/apis/matlab/matlab-engine-api-for-net/) — Call MATLAB from .NET programming languages, enabling .NET programs to launch MATLAB, evaluate MATLAB functions with arguments, and exchange data…
- [MATLAB RESTful Web Services](https://apis.io/apis/matlab/matlab-restful-web-services/) — Create and deploy RESTful web services from MATLAB functions using MATLAB Production Server.
- [MATLAB Production Server RESTful API](https://apis.io/apis/matlab/matlab-production-server-restful-api/) — RESTful API for executing MATLAB functions on MATLAB Production Server, including function execution, discovery and diagnostics, and secure management of…
- [MATLAB Web App Server](https://apis.io/apis/matlab/matlab-web-app-server/) — Host MATLAB apps and Simulink simulations as interactive web apps, with support for authentication, role-based access, and server management via…
- [MATLAB Data API for C++](https://apis.io/apis/matlab/matlab-data-api-for-c/) — Work with MATLAB data types in C++ applications.
- [MATLAB HTTP Interface](https://apis.io/apis/matlab/matlab-http-interface/) — RESTful web services support for making HTTP requests from MATLAB.
- [MATLAB MEX API](https://apis.io/apis/matlab/matlab-mex-api/) — Build MEX functions that enable calling C, C++, and Fortran code from MATLAB, with support for both the C++ MEX API and the C Matrix API.
- [MATLAB Compiler SDK API](https://apis.io/apis/matlab/matlab-compiler-sdk-api/) — Build C/C++ shared libraries, .NET assemblies, Java classes, and Python packages from MATLAB programs for integration with custom applications.
- [ThingSpeak REST API](https://apis.io/apis/matlab/thingspeak-rest-api/) — IoT analytics platform REST API for reading and writing data to channels, creating and managing channels, and analyzing IoT data with MATLAB in the cloud.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Matlab Thingspeak Events](https://apis.io/asyncapis/matlab/matlab-thingspeak-events/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [MATLAB MCP Server](https://apis.io/servers/matlab/matlab-mcp-server/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Matlab Authentication](https://apis.io/security/matlab/matlab-authentication/)
- [Matlab Domain Security](https://apis.io/security/matlab/matlab-domain-security/)
- [Matlab Trust Center](https://apis.io/security/matlab/matlab-trust-center/)
- [Matlab Vulnerability Disclosure](https://apis.io/security/matlab/matlab-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Matlab Plans Pricing](https://apis.io/plans/matlab/matlab-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Matlab Rate Limits](https://apis.io/rate-limits/matlab/matlab-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Matlab Finops](https://apis.io/finops/matlab/matlab-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.mathworks.com)
- [Documentation](https://www.mathworks.com/help/index.html)
- [Pricing](https://www.mathworks.com/pricing-licensing.html)
- [Sign up](https://www.mathworks.com/mwaccount/register)
- [Support](https://www.mathworks.com/support.html)
- [Blog](https://blogs.mathworks.com/)
- [Terms of service](https://www.mathworks.com/matlabcentral/content/terms-of-use.html)
- [Privacy policy](https://www.mathworks.com/company/aboutus/policies_statements/privacy-policy.html)
- [GitHub](https://github.com/mathworks)
- [Status](https://status.mathworks.com/)

## API Evangelist rating

**Kin Score 70.8** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 83.3 |
| Contract quality | 45.3 |
| Contract governance | 4.5 |
| Operational transparency | 92.1 |
| Developer ergonomics | 88.1 |
| Access clarity | 92.1 |

**Agent readiness 33.5** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 32.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/matlab/](https://apis.io/providers/matlab/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for MATLAB: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/matlab/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
