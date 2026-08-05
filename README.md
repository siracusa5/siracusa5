<p align="center">
  <strong>Software engineer building portable AI systems and production web products.</strong><br>
  Coding environments, context infrastructure, interactive software, and the systems behind them.
</p>

<p align="center">
  <a href="https://johnsiracusa.dev">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/siracusa5">LinkedIn</a>
</p>

<p align="center"><sub>PROJECT NETWORK · SELECT A NODE</sub></p>

```mermaid
flowchart LR
    subgraph left[" "]
        direction TB
        kit@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/main/assets/harness-kit.svg", label: "Harness Kit", pos: "b", w: 60, h: 60, constraint: "on" }
        blanks@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/main/assets/mindyourblanks.svg", label: "Mind Your Blanks", pos: "b", w: 60, h: 60, constraint: "on" }
        portfolio@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/main/assets/johnsiracusa-dev.svg", label: "johnsiracusa.dev", pos: "b", w: 60, h: 60, constraint: "on" }
        hometown@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/main/assets/hometown-media.png", label: "Hometown Media", pos: "b", w: 60, h: 60, constraint: "on" }
        kit ~~~ blanks ~~~ portfolio ~~~ hometown
    end

    hub@{ img: "https://avatars.githubusercontent.com/u/9221725?v=4", label: "John Siracusa", pos: "b", w: 76, h: 76, constraint: "on" }

    subgraph right[" "]
        direction TB
        protocol@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/main/assets/harness-protocol.svg", label: "Harness Protocol", pos: "b", w: 60, h: 60, constraint: "on" }
        cake@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/main/assets/context-cake.svg", label: "ContextCake", pos: "b", w: 60, h: 60, constraint: "on" }
        parlay@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/main/assets/2g1p.svg", label: "2 Girls 1 Parlay", pos: "b", w: 60, h: 60, constraint: "on" }
        protocol ~~~ cake ~~~ parlay
    end

    kit --- hub
    blanks --- hub
    portfolio --- hub
    hometown --- hub
    hub --- protocol
    hub --- cake
    hub --- parlay

    style left fill:transparent,stroke:transparent
    style right fill:transparent,stroke:transparent

    click kit "https://harnesskit.ai" "Open Harness Kit" _blank
    click protocol "https://harnessprotocol.ai" "Open Harness Protocol" _blank
    click cake "https://contextcake.com" "Open ContextCake" _blank
    click blanks "https://mindyourblanks.com" "Open Mind Your Blanks" _blank
    click parlay "https://2girls1parlay.com" "Open 2 Girls 1 Parlay" _blank
    click portfolio "https://johnsiracusa.dev" "Open johnsiracusa.dev" _blank
    click hometown "https://hometownmediatn.com" "Open Hometown Media" _blank
```

## Projects

<table width="100%">
  <tbody>
    <tr>
      <td width="100%" valign="top">
        <a href="https://harnesskit.ai"><img src="assets/harness-kit.svg" width="30" alt=""> <strong>Harness Kit</strong></a><br>
        A toolkit for defining and sharing portable AI coding environments.<br>
        <code>TypeScript</code> <code>macOS</code> <code>CLI</code> &nbsp;·&nbsp;
        <a href="https://harnesskit.ai">Open ↗</a> ·
        <a href="https://github.com/harnessprotocol/harness-kit">Source</a> · <a href="https://harnesskit.ai/docs">Docs</a>
      </td>
    </tr>
    <tr>
      <td width="100%" valign="top">
        <a href="https://harnessprotocol.ai"><img src="assets/harness-protocol.svg" width="30" alt=""> <strong>Harness Protocol</strong></a><br>
        An open specification for portable AI coding configurations.<br>
        <code>YAML</code> <code>JSON Schema</code> <code>Open standard</code> &nbsp;·&nbsp;
        <a href="https://harnessprotocol.ai">Open ↗</a> ·
        <a href="https://github.com/harnessprotocol/harness-protocol">Source</a> · <a href="https://harnessprotocol.ai/docs">Docs</a>
      </td>
    </tr>
    <tr>
      <td width="100%" valign="top">
        <a href="https://contextcake.com"><img src="assets/context-cake.svg" width="30" alt=""> <strong>ContextCake</strong></a><br>
        Layered context resolution for AI agents from local folders and GitHub repositories.<br>
        <code>JavaScript</code> <code>macOS</code> <code>Node.js</code> &nbsp;·&nbsp;
        <a href="https://contextcake.com">Open ↗</a> ·
        <a href="https://github.com/ContextCake/context-cake">Source</a> · <a href="https://contextcake.com/docs">Docs</a> · <a href="https://contextcake.com/install">Install</a>
      </td>
    </tr>
    <tr>
      <td width="100%" valign="top">
        <a href="https://mindyourblanks.com"><img src="assets/mindyourblanks.svg" width="30" alt=""> <strong>Mind Your Blanks</strong></a><br>
        Live and on-demand games with host controls, administration, and production tooling.<br>
        <code>Go</code> <code>Next.js</code> <code>Web</code> &nbsp;·&nbsp;
        <a href="https://mindyourblanks.com">Open ↗</a>
      </td>
    </tr>
    <tr>
      <td width="100%" valign="top">
        <a href="https://2girls1parlay.com"><img src="assets/2g1p.svg" width="30" alt=""> <strong>2 Girls 1 Parlay</strong></a><br>
        Sports coverage, live scores, player-prop research, daily picks, and prediction tracking.<br>
        <code>React</code> <code>Vite</code> <code>TypeScript</code> &nbsp;·&nbsp;
        <a href="https://2girls1parlay.com">Open ↗</a>
      </td>
    </tr>
    <tr>
      <td width="100%" valign="top">
        <a href="https://johnsiracusa.dev"><img src="assets/johnsiracusa-dev.svg" width="30" alt=""> <strong>johnsiracusa.dev</strong></a><br>
        A spatial, canvas-based portfolio for exploring projects and capabilities.<br>
        <code>Canvas</code> <code>Native JavaScript</code> &nbsp;·&nbsp;
        <a href="https://johnsiracusa.dev">Open ↗</a>
      </td>
    </tr>
    <tr>
      <td width="100%" valign="top">
        <a href="https://hometownmediatn.com"><img src="assets/hometown-media.png" width="30" alt=""> <strong>Hometown Media</strong></a><br>
        A marketing site for a Tennessee sports, lifestyle, and content media agency.<br>
        <code>Production website</code> &nbsp;·&nbsp;
        <a href="https://hometownmediatn.com">Open ↗</a>
      </td>
    </tr>
  </tbody>
</table>
