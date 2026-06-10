# HarnessWorks

HarnessWorks builds prompt-first harness engineering tools for durable
coding-agent workflows.

The goal is simple: move repeated agent mistakes out of chat history and into
repository-owned context that can be inspected, tested, reviewed, and improved.

## What We Build

- Durable agent instructions that route work through the repository's source of
  truth.
- Drift checks that catch stale docs, missing memory, and unsafe harness changes.
- Failure and decision records that keep solved problems from coming back.
- Adoption workflows that fit the target repository instead of forcing a single
  architecture.
- Effectiveness evidence that separates harness health from actual agent
  outcomes.

## Projects

- [harness-starter-kit](https://github.com/harnessworks/harness-starter-kit) -
  the prompt-first starter kit for adding harness engineering to a repository.
- [harness_starter_kit_django](https://github.com/harnessworks/harness_starter_kit_django) -
  a Django adoption and dogfood target.
- [today-bus](https://github.com/harnessworks/today-bus) - a product-task
  dogfood target for harness effectiveness tracking.
- [harness-erp](https://github.com/harnessworks/harness-erp) - a Spring Boot
  and frontend dogfood target for workflow, failure-memory, and verification
  evidence.

## Principles

- The target repository is the source of truth.
- Useful harness rules should become enforceable where practical.
- Memory belongs in durable files, not only in prompts.
- Evidence should be explicit about what was measured and what was not.
- Templates should stay conservative and adapt to the project in front of them.

## Start Here

Use the starter kit with a target repository:

```text
https://github.com/harnessworks/harness-starter-kit
```

Then ask your coding agent to read the kit and apply the prompt-first harness
engineering workflow to the target project.
