```
ooooo                                      oooo  oooo              
`888'                                      `888  `888              
 888          .ooooo.   .ooooo.   .oooo.    888   888  oooo    ooo 
 888         d88' `88b d88' `\"Y8 `P  )88b   888   888   `88.  .8'
 888         888   888 888        .oP\"888   888   888    `88..8'
 888       o 888   888 888   .o8 d8(  888   888   888     `888'
o888ooooood8 `Y8bod8P' `Y8bod8P' `Y888\"\"8o o888o o888o     .8'
                                                       .o..P'
                                                       `Y8P'
```

[Locally](https://locally.build) is a local cloud environment that runs entirely on your local machine.

It automatically configures the Azure CLI, HashiCorp Terraform, OpenTofu and Pulumi for use, and supports
deploying both ARM Templates and Bicep too.

You can [find out more about Locally on our website](https://locally.build), [explore the documentation](https://locally.build/docs) and [discover what else integrates with Locally](https://locally.build/docs/guides).

## Get Started

When you've installed Locally, you can launch Locally by running:

```bash
locally build
```

Tooling which supports [Automatic Configuration](https://locally.build/documentation/features/automatic-configuration) can be run against Locally via:

```bash
locally run [cmd] [args]
```

For example, to list the Resource Groups using the Azure CLI you'd run:

```bash
locally run az group list
```

You can [find out more about Locally on our website](https://locally.build), [explore the documentation](https://locally.build/docs) and [discover what else integrates with Locally](https://locally.build/docs/guides).
