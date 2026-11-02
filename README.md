# workflow_run fork-boundary lab

Minimal researcher-owned reproduction fixture for `IBM-H1-ARES-WR-001`.

- The `CI` workflow is triggered by pull requests and does not check out or execute pull-request code.
- The downstream workflow intentionally preserves the vulnerable expression-to-shell dataflow under test.
- The privileged cleanup job is restricted to workflow runs created by the controlled researcher account `aslein1412-star` from its fork of this repository.
- The payload used for validation prints only the fixed marker `IBMH1FORK0001`.

This repository is a controlled security-testing artifact. It does not target third-party systems or data.
