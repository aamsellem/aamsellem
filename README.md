```
  ██████╗ ██████╗ ██████╗ ███████╗    ██╗███████╗   ██████╗  ██████╗ ███████╗████████╗██████╗ ██╗   ██╗
 ██╔════╝██╔═══██╗██╔══██╗██╔════╝    ██║██╔════╝   ██╔══██╗██╔═══██╗██╔════╝╚══██╔══╝██╔══██╗╚██╗ ██╔╝
 ██║     ██║   ██║██║  ██║█████╗      ██║███████╗   ██████╔╝██║   ██║█████╗     ██║   ██████╔╝ ╚████╔╝
 ██║     ██║   ██║██║  ██║██╔══╝      ██║╚════██║   ██╔═══╝ ██║   ██║██╔══╝     ██║   ██╔══██╗  ╚██╔╝
 ╚██████╗╚██████╔╝██████╔╝███████╗    ██║███████║   ██║     ╚██████╔╝███████╗   ██║   ██║  ██║   ██║
  ╚═════╝ ╚═════╝ ╚═════╝ ╚══════╝    ╚═╝╚══════╝   ╚═╝      ╚═════╝ ╚══════╝   ╚═╝   ╚═╝  ╚═╝   ╚═╝
```

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=FF9EAA&center=true&vCenter=true&random=false&width=600&lines=Hey+%F0%9F%91%8B+I'm+Aur%C3%A9lien;Swift+%7C+SwiftUI+%7C+macOS+native;AI-powered+tools+builder;Privacy+first%2C+always+%F0%9F%94%92" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white" />
  <img src="https://img.shields.io/badge/SwiftUI-0071E3?style=for-the-badge&logo=swift&logoColor=white" />
  <img src="https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude_Code-blueviolet?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Olares-0078D4?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" />
  <img src="https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white" />
</p>

---

### `$ whoami`

```swift
struct Developer: Identifiable {
    let id = UUID()
    let name = "Aurélien Amsellem"
    let handle = "@aamsellem"
    let location = "Paris, France 🇫🇷"
    let role = "Software Engineer & AI Toolmaker"

    var passions: [String] {
        ["macOS native apps", "AI-augmented workflows", "Privacy-first design", "Gamification"]
    }

    var currentQuest: String {
        "Building companions that make devs 10x — without selling their soul (or data)"
    }

    var philosophy: String {
        "100% local. Zero telemetry. Your machine, your data, your rules."
    }
}
```

---

### `$ ls ~/projects/`

<table>
<tr>
<td width="50%">

#### <img src="https://img.shields.io/badge/🍡-FF9EAA?style=flat-square" /> [Mochi Mochi](https://github.com/aamsellem/mochi-mochi)
**Compagnon virtuel gamifié pour macOS**
> SwiftUI + Claude Code sous le capot. Un Mochi qui gagne de l'XP pendant que vous bossez. Boutique cosmétique, streaks, vue Kanban, sync Notion.
>
> `Swift` `SwiftUI` `Rive` `Sparkle` `Claude Code`

</td>
<td width="50%">

#### <img src="https://img.shields.io/badge/🤖-blueviolet?style=flat-square" /> [ULY](https://github.com/aamsellem/uly)
**L'assistant IA qui vous connaît vraiment**
> Mémoire persistante, 8 personnalités, automatisations. CLI-first, 100% local. Le cerveau derrière Mochi Mochi.
>
> `Claude Code` `Shell` `Markdown` `Notion API`

</td>
</tr>
<tr>
<td width="50%">

#### <img src="https://img.shields.io/badge/🧠-0078D4?style=flat-square" /> [Orales Market](https://github.com/aamsellem/orales-market)
**LLM models for the Olares Store**
> Alternative app source for Olares — deploy open-weight LLMs (Qwen, Llama) via llama.cpp & vLLM. Helm charts, GPU-accelerated, one-click install.
>
> `Helm` `Kubernetes` `llama.cpp` `GGUF` `CUDA`

</td>
<td width="50%">

#### <img src="https://img.shields.io/badge/⚡-FF6B35?style=flat-square" /> [Orales One Market](https://github.com/aamsellem/orales-one-market)
**Optimized AI apps for the Olares One**
> Hand-tuned AI apps for RTX 5090M 24GB. Qwen3.5 35B at **129 t/s**, GLM-4.7-Flash at **131 t/s**, Qwen3-TTS with voice cloning. One-click install via Cloudflare Worker market source.
>
> `Cloudflare Workers` `TypeScript` `Helm` `llama.cpp` `CUDA`

</td>
</tr>
</table>

---

### `$ cat tech_stack.yml`

```yaml
languages:
  daily:    [ Swift, TypeScript, Python ]
  familiar: [ Rust, Go, Shell ]

apple_ecosystem:
  ui:       [ SwiftUI, AppKit, UIKit ]
  tools:    [ XcodeGen, Sparkle, SPM ]
  targets:  [ macOS, iOS ]

ai_tooling:
  runtime:  Claude Code (shell process, not API)
  pattern:  "enriched prompts + local memory + personality layer"
  belief:   "AI should amplify humans, not replace them"

selfhosted_ai:
  platform: Olares One (RTX 5090M 24GB + 96GB DDR5)
  backends: [ llama.cpp, Gradio ]
  models:   [ Qwen3.5-35B-A3B, GLM-4.7-Flash, Qwen3-TTS ]
  speeds:   { Qwen3.5: "129 t/s", GLM-4.7: "131 t/s" }
  format:   Helm charts + Cloudflare Worker market

infrastructure:
  hosting:  GitHub Releases (DMG)
  secrets:  macOS Keychain
  storage:  Local Markdown files  # no database, no cloud
  updates:  Sparkle 2 (EdDSA signed)

principles:
  - "Privacy is not a feature, it's a foundation"
  - "Ship native, not Electron"
  - "Gamify the boring, automate the tedious"
  - "If it leaves your machine, you should know about it"
```

---

### `$ neofetch --stats`

<p align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=aamsellem&theme=rose_pine" width="32%" />
<img src="https://streak-stats.demolab.com?user=aamsellem&theme=rose-pine&hide_border=true&background=0d1117&ring=FF9EAA&fire=FF9EAA&currStreakLabel=FF9EAA" width="32%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=aamsellem&theme=rose_pine" width="32%" />
</p>

<p align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=aamsellem&theme=rose_pine" width="66%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=aamsellem&theme=rose_pine&utcOffset=1" width="32%" />
</p>

---

### `$ tail -f ~/thoughts.log`

```
[2024-01-15] Realized Claude Code + shell process = infinite local AI power
[2024-06-20] ULY v1.0 — persistent memory changes everything
[2025-01-10] Started Mochi Mochi — what if your AI companion was a cute rice ball?
[2025-03-xx] Mochi Mochi ships with gamification, Notion sync, 8 personalities
[2026-03-04] Still shipping. Still local. Still private. 🍡
[2026-03-07] orales-market — bringing open LLMs to the Olares Store 🧠
[2026-03-08] orales-one-market — custom market source for Olares One ⚡
[2026-03-13] Qwen3.5 129 t/s, GLM-4.7 131 t/s, TTS with voice cloning — all on 24GB 🔥
```

---

### `$ echo $CONTACT`

<p align="center">
  <a href="https://github.com/aamsellem">
    <img src="https://img.shields.io/badge/GitHub-aamsellem-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://www.linkedin.com/in/aur%C3%A9lien-amsellem-86472727/">
    <img src="https://img.shields.io/badge/LinkedIn-Aurélien_Amsellem-0A66C2?style=for-the-badge&logo=linkedin" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=aamsellem&color=FF9EAA&style=for-the-badge&label=PROFILE+VIEWS" />
</p>

---

<p align="center">
  <code>while alive { code(); ship(); iterate() }</code>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=FF9EAA&height=80&section=footer" width="100%" />
</p>
