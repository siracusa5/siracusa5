# Interactive project-map compatibility test

```mermaid
flowchart TB
    hub((John Siracusa))
    kit@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/codex/project-atlas-profile/assets/harness-kit.svg", label: "Harness Kit", pos: "b", w: 60, h: 60, constraint: "on" }
    protocol@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/codex/project-atlas-profile/assets/harness-protocol.svg", label: "Harness Protocol", pos: "b", w: 60, h: 60, constraint: "on" }
    cake@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/codex/project-atlas-profile/assets/context-cake.svg", label: "ContextCake", pos: "b", w: 60, h: 60, constraint: "on" }
    blanks@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/codex/project-atlas-profile/assets/mindyourblanks.svg", label: "Mind Your Blanks", pos: "b", w: 60, h: 60, constraint: "on" }
    parlay@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/codex/project-atlas-profile/assets/2g1p.svg", label: "2 Girls 1 Parlay", pos: "b", w: 60, h: 60, constraint: "on" }
    portfolio@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/codex/project-atlas-profile/assets/johnsiracusa-dev.svg", label: "johnsiracusa.dev", pos: "b", w: 60, h: 60, constraint: "on" }
    hometown@{ img: "https://raw.githubusercontent.com/siracusa5/siracusa5/codex/project-atlas-profile/assets/hometown-media.png", label: "Hometown Media", pos: "b", w: 60, h: 60, constraint: "on" }

    kit --- hub
    protocol --- hub
    cake --- hub
    blanks --- hub
    parlay --- hub
    portfolio --- hub
    hometown --- hub

    click kit "https://harnesskit.ai" "Open Harness Kit" _blank
    click protocol "https://harnessprotocol.ai" "Open Harness Protocol" _blank
    click cake "https://contextcake.com" "Open ContextCake" _blank
    click blanks "https://mindyourblanks.com" "Open Mind Your Blanks" _blank
    click parlay "https://2girls1parlay.com" "Open 2 Girls 1 Parlay" _blank
    click portfolio "https://johnsiracusa.dev" "Open johnsiracusa.dev" _blank
    click hometown "https://hometownmediatn.com" "Open Hometown Media" _blank
```
