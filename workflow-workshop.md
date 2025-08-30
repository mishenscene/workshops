## Building CICD Workflow via GitHub Actions

### Terms
CICD -- Continuous Integration and Continuous Delivery

### Notes

Entrypoint in Gitlab - /config/yml
GitHub searches the root of the repository (.git)

```shell
# Create .github directory to mark as root
mkdir -p .github/workflows
```

```shell
# Create a yaml workflow
cat hello_world.yaml
```

Upon push, the github action step will be ran
The steps are run sequentially, so the remaining steps will be skipped, should any of the steps fail

## Links
[GitHub Actions | Documentation](https://docs.github.com/en/actions/get-started/understand-github-actions)
[GitHub, Run a workflow | Documentation](https://docs.github.com/en/actions/how-tos/manage-workflow-runs/manually-run-a-workflow)