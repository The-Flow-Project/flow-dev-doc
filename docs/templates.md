# Templates description

Here you can find the descriptions and the different templates.
If you want to use a template, just copy the markdown-code and insert it at the right place.

## Bug Report

The bug report helps the developer that has found a specific problem or issue with the software, to solve or perform a workaround.

### Typical elements of a bug report

- Description of the problem: describe the problem in detail; write the error message or error code.
- How to identify the problem / causes of the problem: write typical conditions or cases when the problem occurs or what causes the problem.
- Solution: describe the solution in detail. Use a step-by-step solution approach. If no direct solution exists, describe potential workarounds.
- Related documentation: link related documentation files or pages e.g. in the knowledge base , user manual, matching tutorials, product features or in the operation manual.

### Template Bug Report

```markdown
# Bug Report

Date, Time, Who

## Description of the problem

Content: describe the problem in detail; write the error message or error code.

### Error messages

### Error codes

## How to identify the problem

Content: describe how to identify the problem or causes of the problem; write typical conditions or cases when the problem occurs or what causes the problem.

## Solution

Content: describe the solution in detail. Use a step-by-step solution approach. If no direct solution exists, describe potential workarounds.

### Step 1: xxx

### Step 2: xxx

## Related documentation

Content: link related documentation files or pages e.g. in the knowledge base, user manual, matching tutorials, product features or in the operation manual.

```

## Decision

Decision documents contain decision that have been made by the team or someone of the team.
It helps to track and remember those decisions and the explanation, why it has been decided

### Elements of an Decision document

- Introduction: short and brief description
- Theoretical knowledge: provide background information and context
- Reason: Why has this decision been made?
- Examples: provide matching examples, so the reader better understands how to apply the concept in practice (optional)
- Further reading: link additional guides, explanation documents and resources in the product documentation, or external reference (optional)

### Template Decision

```markdown
# Title of Decision

Date, Time, Who

## Introduction

Content: short and brief description about what has been decided

## Theoretical knowledge

Content: background information (brief), in the language of the reader; use images and other rich media
to explain concepts

## Reason

Content: describe, why this decision has been made.

## Examples

Content: well-researched, matching examples so the reader can better understand how to apply the concept in practice

## Further reading

Content: additional guides, explanation documents and resources (internal / external)

```

## Operating Manual

The operating manual contains all necessary information and tasks to operate and manage a service, part of the project or object. It is mostly relevant for the dev team to understand, install, integrate, manage and upgrade the product.

### Typical sections of an Operating Manual

- System overview: main software components, applications, interfaces, external dependencies, host names/IP addresses (if necessary), ports/protocol and firewall rules
- Installation and onboarding:
  1. Prerequisites (specific hardware/software/server configuration and requirements, licenses, …) and check lists
  2. Step by step instructions to install software or system, e.g. how to integrate the Single Sign-On between customer’s cloud provider or on-site Active Directory, and the products user authentication module to integrate the employees
- Testing and Validation: How to check and validate the proper functionality of the system
- Information to handle typical struggles and problems

### Template Operating Manual

```markdown

# Operating Manual

Date, Time, Who

## System Overview

Content: main software components, applications, interfaces, external dependencies, host names/IP addresses (if necessary), ports/protocol and firewall rules

## Installation and onboarding

## Prerequisites

Content: specific hardware/software/server configuration and requirements, licenses, ... and check lists

## Installation process

Content: step-by-step instructions to install software or system, e.g. how to integrate the Single Sign-On between customer’s cloud provider or on-site Active Directory, and the products user authentication module to integrate the employees

## Testing and Validation

How to check and validate the proper functionality of the system and which tests to run for validation.

## Frequently asked questions

Content: Information to handle typical struggles and problems

```

## Glossary

A glossary lists the specific terms and describes it in a user-friendly language. It can be used for complex,
domain-specific products and software applications.

### Elements of a glossary entry

- Term: word or fragment
- Definition: short description of the meaning of the term; not longer than 2-3 sentences
- Alias: (optional) similar terms or synonyms
- Further reading: (optional) list of links to additional pages in the online documentation that are related to the term and e.g. explain the usage or a specific functionality in your software product

### Template Glossary

```markdown
# Glossary entry

Date, Time, Who

## Title: Term

Content: word or fragment

## Definition

Content: short description of the meaning of the term; not longer than 2-3 sentences

## Alias

Content: similar terms or synonyms (optional)

## Further reading

Content: list of links to additional pages in the online documentation that are related to the term and e.g. explain
    the usage or a specific functionality in your software product

```

## Meeting

Meeting documents contain the protocol of a dev-meeting or a full-team-meeting. It should describe what happened, shortly describe decisions and todo's and optionally link to decision documents.

### Elements of a Meeting document

- Date, Time: When was the meeting
- Attendees: Who was there
- Open issues/subjects: List of issues/subjects to discuss
- Discussed subjects: List of subjects that have been discussed. One entry can contain a todo list where the todo's are assigned.
- Next meeting (optional)

### Template Meeting

```markdown
# Meeting protocol

## Date, Time

## Attendees

## Open issues/subjects

Content: List of issues/subjects to discuss

## Discussed subjects

Content: List of subjects that have been discussed. One entry can contain a todo list where the todo's are assigned.

## Next meeting

## Further reading

Content: additional guides, explanation documents and resources (internal / external)

```

## Product Feature

The product feature documentation present the main features and modules. It is a high level
documentation introducing concepts.

### Elements of a product feature document

#### Overview and introduction

- What is xxx: short paragraph introducing the goal or vision of the feature
- System and configuration requirements: what is necessary to use the feature (e.g. specific hardware or software, license, browser version, …)
- Planning and preparation: is a specific checklist or similar preparation steps necessary? An installation guide might be helpful if there are changes necessary on the customers infrastructure or computer.

#### Explore / quick start / getting started

- Samples: prepared examples that indicate the usage, outcome and the gain for the user
- Create your first …: short but specific how-to guide or explanation how the user should use the new feature of the product to get the desired outcome
- Specific examples: if there are different ways or input to get different output, they might be described also in this section

#### Specific feature description

For each of the main features there should be a specific description using how-to guide or explanation

#### Customization

Describes how the user can adapt and customize the new feature – using tutorials and how-to guides as

#### Manage and setup

Describes what and how the administrator and power users can configure the product to use the new features in the best way for the organization

#### Reference and advanced learning

List of references that the user can read to better understand and use the new feature, might also reference existing features and other product documentation types

### Template Product Feature

```markdown
# Product Feature Title

Date, Time, Who

## Introduction

Content:  short paragraph to introduce the vision/goal of the feature - from the user's perspective

### Requirements

Content: What is necessary to use the feature? (e.g. specific hardware or software, license, browser version)

### Preparation

Content: What has the user to do to get this new feature - e.g. add a special configuration setting, contact the vendor for beta-access

## Getting started

Content: shortest way to use the new feature - short, specific - e.g. in how-to format

## Specific feature description

Content: Specific description using how-to guide or explanation for each of the main features

## Customization

Content: How can the user adapt and customize the new feature?

## Manage and setup

Content: What and how can the administrator or power user configure the product to use the new features in the best way for the organization?

## Reference and advanced learning

Content: list of related documents the user can read to better understand and use the new feature, also already existing features and other product documentation types

```

## Release notes

Release notes describe and list the changes of a software version and are normally published to the user and customer of a application or app.

### Elements of a release note

- Software version (optional release & build number), and/or the release date
- Added public features
- Fixed public bugs
- Known issues

Additional information can be added if available or necessary, as e.g.

- Download link
- Supported platforms and environments
- Prerequisites
- Removed features
- Installation & upgrade instructions

### Template Release notes

```markdown
# Release Notes

Date, Time, Who

## Title: Product name + release version

Content: Product name and official release version (optional release & build number), and/or the release date

## Added features

Content: list of new (public visible) features, add links to product documentation (if described there)

## Fixed bugs

Content: list of (public visible/communicated) bugs, add ticket id / case number and related software module (e.g. iOS App, Server, ...)

## Known issues

Content: list of known issues and if possible, link to documentation that describes the problem and a potential workaround

## Additional - use if appropriate

Additional information can be added if available or necessary, as e.g.

## Download link

Content: links to the specific software downloads for each module + platform

## Supported platforms and environments

Content: if the product is available for different platforms and environments, list them along with the supported versions (e.g. Windows 10 x64, Windows 11 x64, ubuntu Server > 20.04.3 LTS, ...)

## Prerequisites

Content: describe required prerequisites relevant for this release (e.g. specific Windows service pack, hardware, ...)

## Removed features

Content: if features have been removed (e.g. because it was only in beta, it was not used by the users, ...), list them here

## Installation & upgrade instructions

Content: describe the installation and upgrade procedure, or link to the appropriate sections in the documentation (must be relevant for this specific version)

```
