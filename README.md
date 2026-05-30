# Setup tox test environments

Find all tox environments configured by "type"

## Example Usage

```
  setup:
    uses: infrabits/ci-run-tox-env/.github/workflows/run.yml@main
    with:
      environments: '["black", "test"]'
      services: '{"test": ["mysql"]}'
```

or

```
    steps:
      - uses: infrabits/ci-run-tox-env@main
        with:
          environment: black
```
