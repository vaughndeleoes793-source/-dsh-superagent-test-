# -dsh-superagent-test-

## Architecture

- The project is organized around a single README-driven repository that documents the system's structure and design intent.
- Work is tracked through GitHub issues and pull requests, with the orchestrator routing tickets to worker agents that implement changes in isolated branches.
- The DeepSeek Harness provides the execution environment, tooling, and skill catalog that workers use to read context, make changes, and verify results.