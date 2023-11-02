# Update Terraform Provider Versions action

This action checks https://releases.hashicorp.com for latest versions and updates the repositories variables with the info.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

uses: actions/hello-world-docker-action@v2
with:
  who-to-greet: 'Mona the Octocat'
