# label-workflows

A collection of label workflows.

## Description

A collection of label workflows implemented as Reusable Workflows for GitHub Actions.

## Usage

### Reusable Workflows

```yaml
jobs:
  call:
    uses: tmknom/label-workflows/.github/workflows/reusable-workflows.yml@v0
    permissions:
      contents: read
      pull-requests: write
```

## Release notes

See [Releases](https://github.com/tmknom/label-workflows/releases).

## License

Apache 2 Licensed. See [LICENSE](/LICENSE) for full details.
