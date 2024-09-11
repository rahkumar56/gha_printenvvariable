# gha_printenvvariable
This repo is used for the print env variable using github actions

# Print Environment Variables

This GitHub Action prints environment variables to the log.

## Inputs

- `envs`: A comma-separated list of environment variables to print. Defaults to `ALL`.

## Example Usage

```yaml
uses: your-username/your-repo/.github/actions/print-env@main
with:
  envs: 'VAR1,VAR2'

