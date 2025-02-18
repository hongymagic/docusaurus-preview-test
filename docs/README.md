# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ pnpm install
```

### Local Development

```
$ pnpm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ pnpm build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true pnpm deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> pnpm deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

## GitHub Pages Setup Requirements

For PR Preview deployments to work correctly, you need to configure your repository's GitHub Pages settings:

1. Set the **Source** to "Deploy from a branch"
2. Create an environment named `gh-pages` and configure it to allow deployments from:
   - The `gh-pages` branch (for main deployments)
   - PR deployment branches (for preview deployments)
