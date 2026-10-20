# Research approach

Our public work is grounded in an observable security boundary and a reproducible result. The sequence below describes how we prepare a report without exposing an unresolved issue.

## 1. Define the boundary

Record what a caller is allowed to access and the operation that appears to cross that boundary. Note the product version, relevant configuration, and the expected behavior before testing.

## 2. Reproduce in isolation

Use a local or otherwise authorized environment and synthetic data. Keep a control case so a maintainer can distinguish the suspected issue from normal behavior. Record the minimum evidence needed to verify the outcome.

## 3. Report through the preferred channel

Follow the project's `SECURITY.md`, private vulnerability reporting form, or designated security contact. Include impact and environmental assumptions. Do not place unpublished details in public issues, commits, or this repository.

## 4. Support triage and remediation

Answer clarifying questions, correct the report when evidence changes, and review a proposed fix when the maintainer asks. Distinguish a confirmed result from an inference or an untested possibility.

## 5. Coordinate publication

Respect the maintainer's disclosure process. Before adding a public record here, confirm that the advisory is published and the attribution is accurate. The upstream advisory remains the authoritative source for severity, affected versions, and remediation.

For report and follow-up formats, see [disclosure-templates](https://github.com/MutedCybersecurity/disclosure-templates).
