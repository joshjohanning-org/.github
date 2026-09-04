# .github

This repository maintains the [organization's public profile README](https://github.com/joshjohanning-org/.github/blob/main/profile/README.md) and includes a GitHub Actions workflow that automatically generates markdown badges for display in that README.

## Copilot custom agents

The [`agents`](agents) directory contains organization-managed GitHub Copilot custom agents.

The `subagent-orchestrator`, three worker agents, and `marker-verifier` provide a public, sanitized version of an enterprise-managed subagent orchestration test. The orchestrator delegates marker-file creation to each worker and then asks the verifier to validate the combined result.

These public profiles demonstrate the same profile structure used for the enterprise test. Enterprise-wide distribution requires placing the released profiles in the `/agents` directory of the designated `.github-private` governance repository.
