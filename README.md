<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=300&color=gradient&text=I%20build%20what's%20missing&fontAlignY=38&desc=Every%20project%20starts%20with%20something%20that%20annoyed%20me&descAlignY=58"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1400&color=58A6FF&center=true&vCenter=true&width=640&lines=WhatsApp+Desktop+was+eating+900MB+of+my+RAM.;Nobody+had+fixed+it.;So+I+read+the+Win32+docs+and+shipped+the+fix.;That's+the+whole+design+philosophy."/>
</div>

<br/>

### 📖 The story so far

It always starts the same way. Something on my machine is slow, leaky, or just *missing*. I go looking for the fix and it doesn't exist. So I build it, usually somewhere close to the OS or deep in the browser.

Here's the log:

| 😤 The annoyance | 🛠️ What I shipped |
|---|---|
| WhatsApp Desktop ate 900MB of RAM, stole focus, and drained my battery | [**Velocity**](https://github.com/HarshalPatel1972/velocity): a tray app that fixes all three with native Win32 APIs. `Go · Win32` |
| Web apps fall apart the moment the Wi-Fi does | [**GoSync**](https://github.com/HarshalPatel1972/GoSync): a self-hosted, offline-first, real-time sync engine. IndexedDB in the browser, SQLite or Postgres on the server. `Go` |
| Quantum computers will break RSA and ECC, and nobody knows where theirs is hiding | [**Spectra**](https://github.com/HarshalPatel1972/spectra): a scanner that finds quantum-vulnerable crypto in code, certs, and configs. It ships as a CLI, a [VS Code extension](https://github.com/HarshalPatel1972/spectra-vscode), a [GitHub Action](https://github.com/HarshalPatel1972/spectra-action), and a [Homebrew tap](https://github.com/HarshalPatel1972/homebrew-tap). |
| Moving a file from my phone to my PC meant uploading it to someone's cloud | [**Aero**](https://github.com/HarshalPatel1972/aero): end-to-end encrypted transfer over local Wi-Fi. No cloud, no accounts, no app on the phone. `Go` |
| "Is this API key still alive?" shouldn't mean pasting secrets into sketchy sites | [**KeyPulse**](https://github.com/HarshalPatel1972/keypulse): an instant key validity checker that logs nothing. `Next.js · Cloudflare Workers` |
| AI agents drift halfway through long tasks | [**VibeCheck**](https://www.npmjs.com/package/@harshalpatel2868/vibe-check): deterministic checkpointing that keeps them on track. `Node.js` |
| An API only ever knows its present | [**Epoch**](https://github.com/HarshalPatel1972/Epoch): an HTTP server you can query at any point in its past, fork into what-if timelines, and diff. `Go` |
| Managing 60+ repos on GitHub, one click at a time | [**GitFit**](https://github.com/HarshalPatel1972/GitFit): bulk operations, smart filters, a pin editor, and a cross-repo feed. `TypeScript` |

### 🧹 Left codebases better than I found them

When the bug is in someone else's library, I fix it there.

* **`gopsutil`**: cut Windows process listing from $O(N^2)$ to $O(N)$.
* **`getlantern/systray`**: fixed corrupted alpha transparency in tray icons.
* **`fyne-io/systray`**: stopped menus breaking their width when items update.

### ⚡ Tools I reach for

`Rust` · `Go` · `TypeScript` · `Win32` · `Next.js` · `Wasm` · `Python`

### 📬 What's next is up to you

Got something broken that nobody has fixed? [Tell me about it](https://www.linkedin.com/in/harshal-patel-59b9a5278/). That's how most of the projects above started.

<br/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/HarshalPatel1972/HarshalPatel1972/output/github-contribution-grid-snake-dark.svg"/>
  <img width="100%" alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/HarshalPatel1972/HarshalPatel1972/output/github-contribution-grid-snake.svg"/>
</picture>

[portfolio](https://harshal-patel-chi.vercel.app) &nbsp;·&nbsp; [linkedin](https://www.linkedin.com/in/harshal-patel-59b9a5278/) &nbsp;·&nbsp; [youtube](https://www.youtube.com/@ReverieInfinity)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:161b22,100:0d1117&height=60&section=footer"/>

</div>
