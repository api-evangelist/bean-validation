# Bean Validation (bean-validation)

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

Jakarta Bean Validation (formerly Java Bean Validation / JSR 380) is a Java specification providing a standardized constraint model and API for validating Java beans using annotations. It defines built-in constraints (@NotNull, @Size, @Min, @Max, @Pattern, @Email, etc.), a Validator API, constraint inheritance, and method/constructor parameter validation. The current stable release is Jakarta Validation 3.1. Hibernate Validator is the reference implementation. The specification is governed by the Jakarta EE Working Group under the Eclipse Foundation.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bean-validation/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Bean Validation, Data Quality, Java, Validation, Jakarta EE, Constraints

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### Jakarta Bean Validation Specification 3.1
The Jakarta Bean Validation 3.1 specification defines the constraint model, annotation processor, Validator API, method validation, group sequences, cascaded validation, constraint composition, and the metadata API for introspecting validation constraints on Java classes, fields, methods, and constructors.

**Human URL:** [https://beanvalidation.org/3.1/](https://beanvalidation.org/3.1/)

#### Tags:

 - Bean Validation, Java, Jakarta EE, Specification

#### Properties

- [Documentation](https://beanvalidation.org/3.1/)
- [Specification](https://jakarta.ee/specifications/bean-validation/3.1/)
- [GitHubRepository](https://github.com/jakartaee/validation)

### Hibernate Validator
Hibernate Validator is the reference implementation of Jakarta Bean Validation. Version 9.1.0.Final implements the Jakarta Validation 3.1 specification. It provides the Validator, ValidatorFactory, ConstraintViolation APIs, additional built-in constraints beyond the spec, programmatic constraint definition, and message interpolation.

**Human URL:** [https://hibernate.org/validator/](https://hibernate.org/validator/)

#### Tags:

 - Bean Validation, Java, Reference Implementation, Hibernate

#### Properties

- [Documentation](https://docs.jboss.org/hibernate/stable/validator/reference/en-US/html_single/)
- [GettingStarted](https://hibernate.org/validator/documentation/getting-started/)
- [GitHubRepository](https://github.com/hibernate/hibernate-validator)
- [SDK - Maven Central](https://mvnrepository.com/artifact/org.hibernate.validator/hibernate-validator)

### Jakarta Validation API
The Jakarta Validation API JAR provides the interfaces, annotations, and exception types that constitute the Bean Validation specification contract. Includes @NotNull, @Size, @Min, @Max, @Pattern, @Email, @Future, @Past, @Positive, @Negative constraints, Validator, ValidatorFactory, ConstraintViolation, and Path types.

**Human URL:** [https://jakarta.ee/specifications/bean-validation/3.1/](https://jakarta.ee/specifications/bean-validation/3.1/)

#### Tags:

 - Bean Validation, Java, API, Jakarta EE

#### Properties

- [Specification](https://jakarta.ee/specifications/bean-validation/3.1/)
- [SDK - Maven Central](https://mvnrepository.com/artifact/jakarta.validation/jakarta.validation-api)

## Common Properties

- [Website](https://beanvalidation.org/)
- [Documentation](https://beanvalidation.org/2.0/spec/)
- [GitHubOrganization](https://github.com/jakartaee)
- [Versioning](https://beanvalidation.org/news/)

## Features

| Name | Description |
|------|-------------|
| Annotation-Based Constraints | Define validation constraints on Java beans using annotations such as @NotNull, @Size, @Min, @Max, @Pattern, @Email, and @Past. |
| Method Validation | Validate method and constructor parameters and return values using constraint annotations on method signatures. |
| Constraint Composition | Compose multiple constraints together using @Constraint and meta-annotations to create custom reusable constraint annotations. |
| Group Sequences | Define validation groups and group sequences for ordered, conditional validation scenarios. |
| Cascaded Validation | Trigger validation of nested objects using @Valid annotation for graph-level constraint validation. |
| Programmatic API | Build and configure validators programmatically using the Validator and ValidatorFactory APIs without annotations. |

## Use Cases

| Name | Description |
|------|-------------|
| REST API Input Validation | Validate request body and query parameters in JAX-RS and Spring REST controllers using Bean Validation annotations. |
| Form Validation | Validate user-submitted form data in Jakarta Faces, Spring MVC, and other web frameworks. |
| Domain Model Validation | Enforce business rules and data integrity constraints on JPA entity classes and domain objects. |
| Microservices Contract Validation | Validate inter-service request and response payloads to enforce API contracts in microservices architectures. |

## Integrations

| Name | Description |
|------|-------------|
| Spring Framework | Spring integrates Jakarta Bean Validation for controller method argument validation and service layer validation. |
| Jakarta Persistence (JPA) | JPA providers call the Validator API before persisting entities to enforce database-layer constraint validation. |
| Quarkus | Quarkus uses Hibernate Validator as its Bean Validation implementation with zero-config support in native images. |
| Jakarta Faces (JSF) | Jakarta Faces integrates Bean Validation for automatic form field validation in web applications. |
| Micronaut | Micronaut Framework uses Bean Validation for controller parameter and return value validation. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
