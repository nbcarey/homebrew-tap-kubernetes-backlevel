# nbcarey/tap-kubernetes-backlevel

This homebrew tap provides the package `kubernetes-cli` at version `1.23.6`.

Due to `AWS-CLI` [issue #6920](https://github.com/aws/aws-cli/issues/6920),
`kubernetes-cli` version `1.24.0` is broken on AWS, in particular the `kubectl`
command.

This tap allows one to [easily] install the last working version (`1.23.6`).

## How do I install these formulae?

`brew install nbcarey/tap-kubernetes-backlevel/kubernetes-cli@1.23.6`

Or `brew tap nbcarey/tap-kubernetes-backlevel` and then `brew install kubernetes-cli@1.23.6`.

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
