# Nuxt Static Quickstart
> Starter template for a Nuxt project using the static setup

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/nuxt-static-quickstart?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/nuxt-static-quickstart/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node.js](https://img.shields.io/badge/Node.js->%3D12-blue?logo=node.js&logoColor=white)](https://nodejs.org)
[![Made with Yarn](https://img.shields.io/badge/Yarn->%3D1-blue?logo=yarn&logoColor=white)](https://yarnpkg.com/)

[![Package - nuxt](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/nuxt-static-quickstart/nuxt)](https://www.npmjs.com/package/nuxt)
[![dependency - vue](https://img.shields.io/badge/dependency-vue-blue?logo=vue.js&logoColor=white)](https://www.npmjs.com/package/vue)


## Preview

<div align="center">
    <img src="/sample.png" alt="Sample screenshot" title="Sample screenshot" width="400" />
</div>

<br>

<div align="center">

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/nuxt-static-quickstart/generate)

</div>


## About

This Nuxt project uses Yarn, JavaScript (no TS), Vue and Vue templates.

See the [Nuxt homepage](https://nuxtjs.org/) for more info.

Follow [Documentation](#documentation) instructions below to setup and run the app locally.

Content is in the [pages](/pages/) directory as `.vue` files. The [Examples](https://nuxtjs.org/examples) section of the Nuxt docs covers a Hello World example which has multiple pages and can be run in the online sandbox.

Related project:

- [![MichaelCurrin - nuxt-default-quickstart](https://img.shields.io/static/v1?label=MichaelCurrin&message=nuxt-default-quickstart&color=blue&logo=github)](https://github.com/MichaelCurrin/nuxt-default-quickstart)


## Create a fresh project

See the [Getting Started / Installation](https://nuxtjs.org/docs/2.x/get-started/installation) Nuxt docs for more info.

This project was generated with this command:

```sh
$ yarn create nuxt-app nuxt-static-quickstart
```

The SPA, static and `jsconfig.json` options were chosen as different from the default values.

```
? Project name: nuxt-static-quickstart
? Programming language: JavaScript
? Package manager: Yarn
? UI framework: None
? Nuxt.js modules: (Press <space> to select, <a> to toggle all, <i> to invert selection)
? Linting tools: (Press <space> to select, <a> to toggle all, <i> to invert selection)
? Testing framework: None
? Rendering mode: Single Page App
? Deployment target: Static (Static/Jamstack hosting)
? Development tools: jsconfig.json (Recommended for VS Code if you're not using typescript)
? What is your GitHub username? michaelcurrin
? Version control system: Git
```


## Documentation

### Installation

Install dependencies

```sh
$ yarn install
```

### Usage

Serve with hot-reload at `localhost:3000`.

```sh
$ yarn dev
```

### Deploy

#### Build

Build for production.

```sh
$ yarn build
```

Launch server.

```sh
$ yarn start
```

#### Static

Generate static build output in `dist` directory. This seems to need the build command first. This can be deployed as a GitHub Pages site.

```sh
$ yarn generate
```

Recommended:

- Add a `deploy` command to `package.json` as per docs.
- Or use GitHub Actions to build the site and commit the site to `gh-pages` branch.

See info on [GitHub Pages deployment](https://nuxtjs.org/docs/2.x/deployment/github-pages/) in the Nuxt docs.

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
