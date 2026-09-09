# Contributing

Thanks for your interest in `terraform-provider-azgraph`.

This project is in early, active development — expect the schema and
internals to change without notice until a tagged `v0.x` release.

## Code of Conduct

This project follows the [Contributor Covenant](CODE_OF_CONDUCT.md). By
participating, you agree to abide by its terms.

## Getting started

Requirements:

* Go (see `go.mod` for the minimum version once initialized)
* Terraform or OpenTofu, for exercising the provider locally

```sh
go build ./...
go test ./...
```

## Reporting issues

Open a GitHub issue with:

* What you expected to happen
* What actually happened
* Terraform/OpenTofu and provider versions
* A minimal `.tf` snippet that reproduces the problem

## Pull requests

* Keep changes focused — one logical change per PR
* Add or update tests for any behavior change
* Run `go vet ./...` and `gofmt -l .` before opening the PR
* Describe the *why*, not just the *what*, in the PR description

## License

By contributing, you agree that your contributions will be licensed under
the project's [MPL-2.0 license](LICENSE).
