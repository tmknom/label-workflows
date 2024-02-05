# label-workflows

Collection of label workflows.

## Description

A collection of label workflows implemented as Reusable Workflows for GitHub Actions.

## Usage

### Composite Action

```yaml
jobs:
  call:
    uses: tmknom/label-workflows/.github/workflows/composite-action.yml@v0
    permissions:
      contents: read
      pull-requests: write
```

### Reusable Workflows

```yaml
jobs:
  call:
    uses: tmknom/label-workflows/.github/workflows/reusable-workflows.yml@v0
    permissions:
      contents: read
      pull-requests: write
```

## Related projects

- [configurations](https://github.com/tmknom/configurations): Collection of configurations.
- [template-composite-action](https://github.com/tmknom/template-composite-action): Template repository for Composite Action.
- [template-reusable-workflows](https://github.com/tmknom/template-reusable-workflows): Template repository for Reusable Workflows.
- [cross-labeler-action](https://github.com/tmknom/cross-labeler-action): Run [actions/labeler][labeler] with configuration shared across repositories.

## Release notes

See [GitHub Releases][releases].

## License

Apache 2 Licensed. See [LICENSE](LICENSE) for full details.

[labeler]: https://github.com/actions/labeler
[releases]: https://github.com/tmknom/label-workflows/releases
