## Howdy, I'm `v 1 r t l ✨`

I'm a 16 y.o. full-stack web developer.

[![](https://img.shields.io/badge/website-v1rtl.site-blue?style=flat-square)](https://v1rtl.site) ![](https://img.shields.io/badge/languages-ts,js,go-black?style=flat-square)

- hmu on [Telegram](https://t.me/talentless_guy) or [Twitter](https://twitter.com/v1rtl)
- telegram channel: [@we_use_js](https://t.me/we_use_js)

### I am the creator of

#### [tinyhttp](https://tinyhttp.v1rtl.site) :zap:

_**tinyhttp**_ is a **modern**, **lightweight** and **modular** Express-like web framework for Node.js.

[Site :earth_africa:](https://tinyhttp.v1rtl.site) | [GitHub :octocat:](https://github.com/talentlessguy/tinyhttp) | [Docs :scroll:](https://tinyhttp.v1rtl.site/docs) | [Guide :triangular_flag_on_post:](https://tinyhttp.v1rtl.site/learn)

```ts
import { App } from '@tinyhttp/app'
import logger from '@tinyhttp/logger'

new App().get('/', (_, r) => void r.send('<h1>Hello World</h1>')).listen(3000)
```

* **[parsec](https://github.com/talentlessguy/parsec)** :milky_way: 

_**parsec**_ is a modern asynchronous body parser for Node.js.

[GitHub :octocat:](https://github.com/talentlessguy/parsec)

```ts
import { createServer } = from 'http'
import * as parsec from 'body-parsec'

createServer(async (req, res) => {
  await parsec.json()(req) 
  res.setHeader('Content-Type', 'application/json')
  res.end(req.body.hello) // world
}).listen(3000)
```

* **[react-link-previewer](https://react-link-previewer.now.sh/)

Preview links with page meta tags using React component / hook + Go service.

[Site :earth_africa:](https://react-link-previewer.now.sh) | [GitHub :octocat:](https://github.com/relay-chat/react-link-previewer)

```jsx
import React from 'react'
import { LinkPreview } from 'react-link-previewer'
import 'react-link-previewer/src/style.css'

const Link = () => <LinkPreview href="https://relaychat.app" />
```

* **[go-web-app](https://github.com/talentlessguy/go-web-app)** 📦 - CLI for setting up Go WebAssembly frontend app

[GitHub :octocat:](https://github.com/talentlessguy/go-web-app)

```sh
go get github.com/talentlessguy/go-web-app
go-web-app init my-wasm-app
cd wasm-app
go-web-app dev
```

### I'm working on

* **[Komfy](https://github.com/komfy/)** :closed_lock_with_key: 

Ad-free secure social network.

[Site :earth_africa:](https://komfy.now.sh) | [GitHub :octocat:](https://github.com/komfy) | [Twitter :bird:](https://twitter.com/v1rtl)

* **[react-postprocessing](https://github.com/react-spring/react-postprocessing)** 📬

postprocessing wrapper for React.

[GitHub :octocat:](https://github.com/react-spring/react-postprocessing)

```jsx
import React, { useState } from 'react'
import { EffectComposer, Glitch } from 'react-postprocessing'
import { Canvas } from 'react-three-fiber'

const App = () => (
  <Canvas>
    <mesh onClick={() => setTriggered(!isTriggered)}>
      <boxGeometry args={[1, 1, 1]} />
      <meshBasicMaterial color="red" />
    </mesh>
    <Suspense fallback={null}>
      <EffectComposer>
        <Glitch />
      </EffectComposer>
    </Suspense>
  </Canvas>
)
```
