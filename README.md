# in-toto (in-toto)

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
