# terraform-provider-azgraph

A Terraform provider for querying Azure Resource Graph.

> **Status:** early development. No working code yet — schema, resources,
> and data sources are still being designed. Not published to the Terraform
> Registry.

## Overview

Azure Resource Graph lets you query resources across subscriptions using a
SQL-like query language (KQL). This provider aims to expose that as a
Terraform data source, so query results can feed into Terraform
configuration without a separate `az graph query` step.

## Development

Built with [terraform-plugin-framework](https://github.com/hashicorp/terraform-plugin-framework).

```sh
go build ./...
go test ./...
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). This project follows the
[Contributor Covenant](CODE_OF_CONDUCT.md).

## License

[Mozilla Public License 2.0](LICENSE)
