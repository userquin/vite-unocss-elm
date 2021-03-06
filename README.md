# Vite + UnoCSS + Elm Template

A default template for building Elm applications using Vite. Includes hot-module reload of Elm modules (courtesy of `vite-plugin-elm`).

> Vite (French word for "fast", pronounced /vit/) is a build tool that aims to provide a faster and leaner development experience for modern web projects.

> Elm is a functional language that compiles to JavaScript. It helps you make websites and web apps. It has a strong emphasis on simplicity and quality tooling.

> [UnoCSS](https://github.com/antfu/unocss) is an instant on-demand Atomic CSS engine
> 
## Features

- Hot Module Reload of all code in the app (including Elm)
- Tooling installation via elm-tooling
  - Includes Elm, elm-format, elm-json, and elm-test-rs
- Basic unit test examples
- Github Actions CI for running tests
- Recommends the Elm VS Code extension

## Get Started

```bash
# Clone the template locally, removing the template's Git log
npx degit userquin/vite-unocss-elm my-elm-app

# Enter the project, install dependencies, and get started!
cd my-elm-app
npm install
npm run dev
```

For more information about Vite, check out [Vite's official documentation.](https://vitejs.dev/)

To learn more about Elm, check out [Elm's official homepage](https://elm-lang.org/).

## Credits

Template created from [Vite Elm Template](https://github.com/lindsaykwardell/vite-elm-template)
