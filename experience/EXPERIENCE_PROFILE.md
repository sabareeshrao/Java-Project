# Established Experience Context

This file contains only experience facts that have already been established in the training material. Future question builds should reuse these facts unless the user explicitly updates them.

## Company and domain

- Company context: Aerial Topographic Services
- Period used by the training project: June 2018 to November 2023
- Domain: GIS, aerial mapping, topographic services, survey-data processing, QA, reporting, and project-delivery workflows
- Primary backend language across the core experience: Java 8

## Established progression

### 2018

- Role: Junior Java Developer
- Project: Geospatial Survey Data Management System
- Typical concerns: survey records, coordinate validation, imports, status workflows, PostgreSQL/PostGIS persistence, REST APIs, build/runtime troubleshooting, QA defects

### 2020

- Role: Java Developer
- Project: Aerial Mapping Workflow Management Platform
- Typical concerns: aerial-processing workflows, status transitions, release validation, dependency/security remediation, Jenkins deployment, Linux runtime support

## Established software ecosystem

Depending on the specific question, the experience can legitimately draw from:

- IntelliJ IDEA / Eclipse
- Java 8 JDK
- Spring Boot
- Spring Data JPA / Hibernate
- Maven
- JUnit / Mockito
- PostgreSQL / PostGIS / pgAdmin
- Postman
- Git / Bitbucket
- Jira
- Jenkins
- Linux terminal / Windows Command Prompt
- GeoServer / QGIS when the GIS workflow actually requires them
- Outlook for cross-functional communication when relevant

## Consistency rules

1. Do not create a new unrelated project story when an established GIS project can support the question.
2. Separate build-time, runtime, database, API, deployment, and GIS-layer concerns accurately.
3. Do not preload a solution into simulator startup state. Changes should appear only when their workflow step occurs.
4. Simulator scripts should normally contain no more than 10 meaningful steps.
5. For code-focused simulator steps, the target code must be visible and highlighted on the same Next action.
6. Current files on `main` are canonical. Git history records how the project evolved.
