![Cover Art](https://alain.xyz/blog/raw-webgl/assets/cover.jpg)

# WebGL Seed

[![License][license-img]][license-url]
[![Unit Tests][travis-img]][travis-url]
[![Dependency Status][david-img]][david-url]
[![devDependency Status][david-dev-img]][david-dev-url]

A simple hello triangle example you could use to as a basis when starting WebGL.

- [🔳 Codepen Example](https://codepen.io/alaingalvan/pen/OMEqKa)

- [💬 Blog Post](https://alain.xyz/blog/raw-webgl)

## Setup

First install:

- [Git](https://git-scm.com/)

- [Node.js](https://nodejs.org/en/)

- A Text Editor such as [Visual Studio Code](https://code.visualstudio.com/).

Then type the following in any terminal your such as [VS Code's Integrated Terminal](https://code.visualstudio.com/docs/editor/integrated-terminal).

```bash
# 🐑 Clone the repo
git clone https://github.com/alaingalvan/webgl-seed

# 💿 go inside the folder
cd webgl-seed

# 🔨 Start building the project
npm start
```

> Refer to [this blog post on designing web libraries and apps](https://alain.xyz/blog/designing-a-web-app) for more details on Node.js, packages, etc.

## Project Layout

As your project becomes more complex, you'll want to separate files and organize your application to something more akin to a game or renderer, check out this post on [game engine architecture](https://alain.xyz/blog/game-engine-architecture) and this one on [real time renderer architecture](https://alain.xyz/blog/realtime-renderer-architectures) for more details.

```bash
├─ 📂 node_modules/   # 👶 Dependencies
│  ├─ 📁 gl-matrix      # ➕ Linear Algebra
│  └─ 📁 ...            # 🕚 Other Dependencies (TypeScript, Webpack, etc.)
├─ 📂 src/            # 🌟 Source Files
│  ├─ 📄 renderer.ts    # 🔺 Triangle Renderer
│  └─ 📄 main.ts        # 🏁 Application Main
├─ 📄 .gitignore      # 👁️ Ignore certain files in git repo
├─ 📄 package.json    # 📦 Node Package File
├─ 📄 license.md      # ⚖️ Your License (Unlicense)
└─ 📃readme.md        # 📖 Read Me!
```

Some key dependencies are:

- [gl-matrix](http://glmatrix.net/) - WebGL's best linear algebra library, perfect for people used to linear algebra libraries like [GLM](https://glm.g-truc.net/0.9.9/index.html) or the built in GLSL data structures.

- [Webpack](https://webpack.js.org/) - Compiles our TypeScript files and creates binaries for us to use.

- [TypeScript](https://github.com/microsoft/typescript) - JavaScript with types, makes it significantly easier to program web apps with instant autocomplete and type checking.

[license-img]: https://img.shields.io/:license-unlicense-blue.svg?style=flat-square
[license-url]: https://unlicense.org/
[david-url]: https://david-dm.org/alaingalvan/webgl-seed
[david-img]: https://david-dm.org/alaingalvan/webgl-seed/status.svg?style=flat-square
[david-dev-url]: https://david-dm.org/alaingalvan/webgl-seed#info=devDependencies
[david-dev-img]: https://david-dm.org/alaingalvan/webgl-seed/dev-status.svg?style=flat-square
[travis-img]: https://img.shields.io/travis/com/alaingalvan/webgl-seed.svg?style=flat-square
[travis-url]:https://www.travis-ci.com/github/alaingalvan/webgl-seed