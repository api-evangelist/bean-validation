# Bean Validation (bean-validation)
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
