# Local fork of interfaces that feel

Reviewed against source `9039f1b72ed6f92d2a445ad1ad616c58b823902d` on 2026-09-17. This guide describes tracked implementation and does not assert live deployment state.

## Purpose and architecture

An upstream-authored agent skill under `skills/`, with the original README and author attribution retained. This fork is documentation/configuration content, not a running application.

## Setup and development

Read the skill files before installing them into an agent. The original README install command points to the upstream author; installing upstream does not install local fork changes. To use this fork, select this repository explicitly in your skill installer and pin a reviewed revision.

## Verification

Review Markdown, examples and referenced files. There is no package build, automated test suite or hosted service in this repository.

## Deployment and operations

A release means distributing a reviewed skill revision. Do not claim that an upstream release or third-party installation is a deployment owned by this fork. Record local content changes and the installed commit when an actual installation occurs.

Every actual deployment needs a distinct record under [changelogs](../changelogs/README.md), including exact revision/artifact, environment, outcome and operational notes. A source merge or successful build is not deployment evidence.

## Interfaces and further reading

No HTTP API. The integration contract is the skill instruction content consumed by a compatible agent.

## Architecture diagrams

Read [the current architecture and data-flow maps](diagrams/README.md) before planning changes. Proposed behavior is labeled separately from implemented behavior.
