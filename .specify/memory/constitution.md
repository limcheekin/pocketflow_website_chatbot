# PocketFlow Website Chatbot Constitution
<!-- Constitution for the PocketFlow Website Chatbot project. -->

## Core Principles

### I. Command-based Architecture
New features should be implemented as self-contained commands using the `args` package. Each command must have a clear, single responsibility.

### II. Effective Testing
All commands must have corresponding unit tests using the `test` package, following the patterns established by `very_good_cli`. Tests are non-negotiable.

### III. Clear Documentation
All public APIs and commands must have clear and concise Dart-doc comments that explain their purpose, inputs, and outputs.

### IV. Dependency Management
Dependencies listed in `pubspec.yaml` must be actively maintained and curated to keep the application lean and secure. Unused or redundant dependencies should be removed.

### V. Asynchronous Code
Use `Future`s and `Stream`s for asynchronous operations, such as I/O or network requests, following modern Dart best practices to ensure a non-blocking and responsive CLI.

## Additional Constraints
<!-- This section can be used for technology stack requirements, compliance standards, etc. -->

[SECTION_2_CONTENT]

## Development Workflow
<!-- This section can be used for code review requirements, quality gates, etc. -->

[SECTION_3_CONTENT]

## Governance
<!-- The constitution supersedes all other practices. Amendments require documentation and approval. -->

All pull requests and code reviews must verify compliance with this constitution. Complexity must be justified against the principles of simplicity and maintainability.

**Version**: 1.0.0 | **Ratified**: 2025-10-03 | **Last Amended**: 2025-10-03
