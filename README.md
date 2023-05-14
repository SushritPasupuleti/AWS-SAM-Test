# AWS-SAM-Test
Using SAM to locally develop AWS lambda functions

## Setup

Install `sam` and `aws` cli from the respective resources.

Create app:

```bash
sam init
```

Select appropriate template.

**Note**: The below steps require `docker` to be setup and running. As such in some cases, running the command with `sudo` may be necessary as well.

Build:

```bash
sam build
# build with `-u` to resolve zlib issues
```

Run locally:

```bash
sam local invoke
```
