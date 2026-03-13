# Chainloop

- [Chainloop](https://chainloop.dev) ([GitHub](https://github.com/chainloop-dev/chainloop)) is an open-source software supply chain control plane for collecting, attesting, and managing artifacts across CI/CD pipelines
- Chainloop supports **Tekton Pipeline** as a native runner, enabling automatic PipelineRun attestation alongside GitHub Actions, GitLab CI, Azure DevOps, and other CI/CD systems
- The runner auto-detects Tekton pipeline execution, captures Kubernetes and Tekton metadata (namespace, pipeline name, run UID), and supports both `taskRef` and inline `taskSpec` patterns
- We use Tekton as a first-class CI/CD backend for software supply chain attestation with [in-toto](https://in-toto.io/) and [SLSA](https://slsa.dev/) compliance
