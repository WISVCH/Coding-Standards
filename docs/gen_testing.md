---
id: gen_testing
title: Testing
sidebar_label: Testing
---

* Where possible, tests should be present, this includes unit, integration and end-to-end tests
* Test-driven development (TDD) is highly encouraged!
* At Bytecode, we aim to always achieve at least 80% of test coverage, preferably 90%+
* For all projects (even for HTML websites and WordPress themes), a CI-pipeline should be set up, to ensure the code compiles, there are no missing dependencies and there are no linting errors
* Always test your own code before sending your code to QA or requesting a merge-request review

## Testing frameworks

*Not including testing frameworks included in the language itself*

| Framework | Language | Used for |
| - | - | - |
| Jest | JS/TS | Unit testing and integration testing of logic, including mocks etc.
| Enzyme | JS/TS | Testing of ReactJS components
| Testify | Golang | Asserting and mocking in large Go projects