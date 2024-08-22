# hyke/.github

This repo is used for template files / files that are shared across HYKE's organization repositories.

### Contents

#### Workflows

- `dependencies.repos` : example file - how to list dependent repositories for the workflows
- `.github/workflows/` :  contains template workflow files:
  - `build-dependencies.yaml` : build test using github runners
  - `build-dependencies-self-hosted.yaml` : build test using Hyke runners
  - `launch-nodes-self-hosted.yaml` : spin nodes for 60s to detect launch failures
  - `unit-test-self-hosted.yaml` : unit test all packages in workspace (see workflow for exclusion patters)

#### Other

- `.github/pull_request_template.md` : copy this path+file into your repository and it will be used as a template for new PRs to master

---

*Note:*  Hyke's public README at `profile/README.md` is visible on the organization profile.
