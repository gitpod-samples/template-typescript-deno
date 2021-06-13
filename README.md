# A Deno app on Gitpod

This is a [Deno](https://deno.land/) template configured for ephemeral development environments on [Gitpod](https://www.gitpod.io/).

## Next Steps

Click the button below to start a new development environment:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/from-referrer/)

## How To Get Started With Your Project

To get started with Deno on Gitpod, add a `.gitpod.Dockerfile` with the following content:

```dockerfile
FROM gitpod/workspace-full

RUN curl -fsSL https://deno.land/x/install/install.sh | sh
```

Then, add a [`.gitpod.yml`](./.gitpod.yml) file which contains the configuration to improve the developer experience on Gitpod. To learn more, please see the [Getting Started](https://www.gitpod.io/docs/getting-started) documentation.
