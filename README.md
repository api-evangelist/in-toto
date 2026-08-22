# in-toto (in-toto)

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

in-toto is a CNCF graduated framework for securing the integrity of software supply chains. It provides a specification for generating and verifying metadata about each step in a software supply chain, from source code to deployment. in-toto ensures that each step is performed by the authorized party and that materials and products are not tampered with between steps.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/in-toto/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Cloud Native, Graduated, Security, Software Integrity, Supply Chain Security, Verification

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-28

## APIs

### in-toto Attestation Specification

The in-toto specification defines the metadata format for recording software supply chain steps. It includes layout metadata that defines the expected steps and their authorized functionaries, and link metadata that records what actually happened at each step including materials consumed and products produced. Verification compares layouts against links to detect tampering.

**Human URL:** [https://in-toto.io/docs/specs/](https://in-toto.io/docs/specs/)

#### Tags:

 - Attestation, Specification, Supply Chain

#### Properties

- [Documentation](https://in-toto.io/docs/specs/)
- [Reference](https://github.com/in-toto/docs/blob/master/in-toto-spec.md)
- [JSONSchema](json-schema/in-toto-layout-schema.json)
- [JSONSchema](json-schema/in-toto-link-schema.json)
- [JSONSchema](json-schema/in-toto-attestation-schema.json)
- [JSON-LD](json-ld/in-toto-context.jsonld)

### in-toto Attestation Framework

The in-toto Attestation Framework provides a specification for generating verifiable claims about any aspect of how a piece of software is produced. It defines a fixed lightweight Statement structure with a subject and predicate, and a set of standard predicate types covering common use cases such as SLSA provenance.

**Human URL:** [https://github.com/in-toto/attestation](https://github.com/in-toto/attestation)

#### Tags:

 - Attestation, SLSA, Specification, Supply Chain

#### Properties

- [Documentation](https://github.com/in-toto/attestation/blob/main/README.md)
- [Reference](https://github.com/in-toto/attestation/tree/main/spec/v1)
- [GitHubRepository](https://github.com/in-toto/attestation)
- [JSONSchema](json-schema/in-toto-attestation-schema.json)
- [JSON-LD](json-ld/in-toto-context.jsonld)

### in-toto Python Reference Implementation

The Python reference implementation of in-toto provides tools and libraries for creating and verifying in-toto metadata. It includes the in-toto-run command for wrapping supply chain steps, in-toto-record for multi-command steps, and in-toto-verify for checking the full supply chain layout.

**Human URL:** [https://github.com/in-toto/in-toto](https://github.com/in-toto/in-toto)

#### Tags:

 - Python, Reference Implementation, SDK, Supply Chain

#### Properties

- [Documentation](https://in-toto.readthedocs.io/)
- [Getting Started](https://in-toto.io/docs/getting-started/)
- [GitHubRepository](https://github.com/in-toto/in-toto)

### in-toto Go Implementation

A Go implementation of the in-toto specification that enables supply chain integrity verification in Go-based build and deployment pipelines. It supports ITE-7 for X.509-based signing via SPIFFE/SPIRE integration.

**Human URL:** [https://github.com/in-toto/in-toto-golang](https://github.com/in-toto/in-toto-golang)

#### Tags:

 - Go, Implementation, SDK, Supply Chain

#### Properties

- [Documentation](https://pkg.go.dev/github.com/in-toto/in-toto-golang)
- [GitHubRepository](https://github.com/in-toto/in-toto-golang)

## Common Properties

- [Website](https://in-toto.io)
- [Documentation](https://in-toto.io/docs/)
- [Getting Started](https://in-toto.io/docs/getting-started/)
- [Blog](https://in-toto.io/blog/)
- [Community](https://in-toto.io/community/)
- [FAQ](https://in-toto.io/docs/faq/)
- [GitHubOrganization](https://github.com/in-toto)
- [JSONSchema](json-schema/in-toto-layout-schema.json)
- [JSONSchema](json-schema/in-toto-link-schema.json)
- [JSONSchema](json-schema/in-toto-attestation-schema.json)
- [JSON-LD](json-ld/in-toto-context.jsonld)
- [Rules](rules/in-toto-rules.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
