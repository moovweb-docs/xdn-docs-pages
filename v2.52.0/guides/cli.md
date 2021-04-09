# CLI

This guide shows you everything you can do with the XDN command line interface.

## Installation

To install the XDN CLI run

```bash
npm i -g @xdn/cli
```

Or with yarn:

```bash
yarn global add @xdn/cli
```

## Commands

### build

Creates a build of your app optimized for production

#### Options

| Name                         | Description                                                                                                                                                                                                                                                                              |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `--skip-framework`           | Alias: "-s". Skips the framework (Next.js, Vue, Angular, etc..) build and simply rebundles your router                                                                                                                                                                                   |
| `--disable-permanent-assets` | Set this to true to suppress errors like "Immutable file (...) content was changed" during deployment.                                                                                                                                                                                   |
| `--include-sources`          | Includes all non-gitignored source files in the bundle uploaded to the XDN. This can be helpful when debugging, especially when working with Moovweb support. You can limit the files that are uploaded using the [sources](/guides/xdn_config#section_sources) config in xdn.config.js. |

#### Example

```bash
xdn build
```

### cache-clear

Clears the cache. If neither `--path` nor `--surrogate-key` is specified, the entire cache for the
specified environment will be cleared.

#### Options

| Name              | Description                                                   |
| ----------------- | ------------------------------------------------------------- |
| `--team`          | (Required) The team name                                      |
| `--site`          | (Required) The site name.                                     |
| `--environment`   | (Required) The environment name.                              |
| `--path`          | A path to clear. Use "\*" as a wildcard.                      |
| `--surrogate-key` | Clears all responses assigned to the specified surrogate key. |

#### Example

```bash
xdn cache-clear --team=my-team --site=my-site --environment=production --path=/p/*
```

### completion

Creates a script that provides autocompletion for xdn cli commands that can be installed in your shell.

#### Example

```bash
xdn completion
```

#### Using ZSH

```bash
xdn completion >> ~/.zshrc
```

#### Using BASH

```bash
xdn completion >> ~/.bashrc
```

### deploy

Builds and deploys your site on the Moovweb XDN.

#### Parameters

| Name   | Description                                                                                                                          |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------ |
| `team` | The name of the team under which the site will be deployed. The site will be deployed to your private space will be used if omitted. |

#### Options

| Name                         | Description                                                                                                                                                                                                                                                                              |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `--site`                     | The name of the site to deploy. By default the `name` field in `package.json` is used.                                                                                                                                                                                                   |
| `--environment`              | The environment to deploy to. By default the `default` environment is used.                                                                                                                                                                                                              |
| `--branch`                   | The name of the source control branch. This is automatically set when using Git.                                                                                                                                                                                                         |
| `--skip-build`               | Skips the build step                                                                                                                                                                                                                                                                     |
| `--token`                    | Authenticates using a deploy token rather than your user credentials. Use this option when deploying from CI.                                                                                                                                                                            |
| `--commit-url`               | The URL at which the commit can be viewed in your source control provided. If your package.json provides the repository attribute the commit URL will be derived automatically if you use GitHub, GitLab, or BitBucket.                                                                  |
| `--include-sources`          | Includes all non-gitignored source files in the bundle uploaded to the XDN. This can be helpful when debugging, especially when working with Moovweb support. You can limit the files that are uploaded using the [sources](/guides/xdn_config#section_sources) config in xdn.config.js. |
| `--disable-permanent-assets` | Set this to true to suppress errors like "Immutable file (...) content was changed" during deployment.                                                                                                                                                                                   |

#### Example

```bash
xdn deploy my-team --environment=production
```

### docs

Open the XDN documentation in your browser.

#### Example

```bash
xdn docs
```

### dev

Runs your project in development mode, simulating the XDN cloud environment. This command is a simplified version of `xdn run`, with only the --cache option being supported.

#### Options

| Name      | Description                                                                                     |
| --------- | ----------------------------------------------------------------------------------------------- |
| `--cache` | Enables caching during local development so that you can test the caching logic in your router. |

#### Example

```bash
xdn dev
```

### init

Run in an existing app to add all required packages and files need to publish your app on the Moovweb XDN

#### Example

```bash
xdn init
```

#### Options

| Name          | Description                                                                                                                                                                                                |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `--connector` | The name of a specific connector package to install, or a path to a directory that implements the [connector interface](/guides/connectors#section_implementing_a_connector_directly_within_your_project). |

### login

Logs into the XDN via the developer console.

#### Example

```bash
xdn login
```

### logout

Logs out of the XDN

#### Example

```bash
xdn logout
```

### run

Runs your app locally. Uses port 3000 by default. You can change this by setting the `PORT` environment variable. For example: `PORT=5000 xdn run`.

#### Options

| Name           | Description                                                                                                                                                                                                                     |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `--production` | Runs a production build of your app, simulating the cloud environment. This can also be achieved by setting the NODE_ENV environment variable to `true`. You need to run `xdn build` first.                                     |
| `--cache`      | Enables caching during local development so that you can test the caching logic in your router. By default caching is turned off in local development to ensure you don't see stale responses as you make changes to your code. |

#### Example

```bash
xdn run --production
```

Or to run a deployment bundle downloaded from the XDN Developer Console, use:

```bash
xdn run /path/to/bundle.zip
```

Production mode is always used whe running downloaded bundles.

### use

Switches the version of all @xdn/\* packages in your project.

#### Example

To install a particular version:

```bash
xdn use 1.45.0
```

To install the latest stable:

```bash
xdn use latest
```

To install the latest preview:

```bash
xdn use next
```

## Troubleshooting

---

### Error: Cannot find module ... on `xdn init`

An uncommon issue when running `xdn init` can present a similar error:

> installing @xdn/core, @xdn/cli, @xdn/prefetch, @xdn/devtools, @xdn/angular… done.
> Error: Cannot find module ‘/Users/myUser/Projects/my-xdn-poc/node_modules/@xdn/angular/bin/init’

This may be related to an outdated global version of XDN CLI. The telltale sign is reference to `/bin/` in the module path. This is an old convention. Recommended approach would be to `npm i -g @xdn/cli@latest` and then run `xdn init` on the project.
