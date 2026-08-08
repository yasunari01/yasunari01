# Yasunari Murayama

**Product Engineer · AI Automation · Desktop & Creative Tools**

I ship practical software for live production, automation, and small-business workflows — released native plugins, deployed applications, tools used in real broadcasts. Fifteen-plus years in video production before that.

📍 Mexico · Available for **remote contract or full-time** work, international

---

### 🎨 [OBS Filters](https://github.com/yasunari01/obs-filters) — three native OBS Studio plugins · *released · full source public*

Released for **macOS and Windows x64**, publicly available and already downloaded by users. Free, pay-what-you-want.

Written in **C against the libobs API**, each with its own **HLSL GPU shader** and CMake build. SkinSoft builds a skin mask from hue/saturation/luminance ranges and protects facial detail with an edge estimate, rather than blurring the whole frame.

→ [SkinSoft](https://yasunarimurayama.com/product/obs-skinsoft/) · [Temperature + Tint](https://yasunarimurayama.com/product/temperature-tint/) · [Colorist Tone](https://yasunarimurayama.com/product/obs-colorist-tone/) · [write-up](https://yasunarimurayama.com/free-obs-filters-by-yasunari-murayama/)

`C` · `HLSL` · `CMake` · `Inno Setup` · `macOS/Windows packaging`

---

### 🔊 [ChatCaster](https://chatcaster.yasunarimurayama.com) — live chat, read aloud · *deployed · used in real broadcasts*

Reads TikTok Live and several YouTube live chats aloud at once, so a streamer with hands on the keyboard doesn't have to watch a chat panel. Ships as a **web application and a macOS desktop app**.

Readers that live in a browser tab stall when the tab loses focus, since browsers throttle background timers — exactly the case when a game is full-screen. The **desktop app connects directly to each source**, one connection per stream; the **web version keeps the queue on the server**, handing the browser one message at a time so no backlog builds up. The queue is bounded by *seconds of lag* rather than message count: a question answered ninety seconds late is noise.

`Python` · `WebSockets` · `nginx` + `systemd` on a VPS · neural TTS

---

### 🛒 [ClientesExpress](https://clientesexpress.com) — inverted marketplace · *deployed · public beta*

A marketplace that runs backwards: clients post what they'll pay, providers respond with offers. A deterministic rule engine screens content **before** anything reaches a model, so most unwanted content is caught by rules that cost nothing to run and only ambiguous cases escalate.

`JavaScript (modular)` · `HTML/CSS` · `rule engine`

---

### 🐝 Colmena — AI sales assistant · *private deployment for a local optical business*

Qualifies customers and books appointments, deployed on a VPS with booking synced to Google Calendar. The interesting problem was what the model should *not* handle: catalog rules, coupon validation, and scheduling constraints run as deterministic logic, so the model handles conversation instead of arithmetic it would get wrong.

`Node.js` · `OpenAI API` · `Google Calendar API` · `VPS deployment`

---

### Also built

**HarpyTrader** — private algorithmic trading research system: modular backtesting with look-ahead controls, out-of-sample validation, and a scheduled research loop feeding a passive shadow simulator *(Python, pandas, scikit-learn, ccxt)* · **Murayama Text Syphon** — real-time text animation for live production, shared over Syphon *(Swift, macOS)* · **AutoClicker** — global-hotkey auto-clicker shipped as a universal `.dmg`, on Quartz `CGEventTap` because the usual Python input library crashes on recent macOS *(Python)* · **Review QR** — QR codes routing customers to a business's Google reviews *(React Native, Expo)* · **Silent MP4 Fixer** — repairs MP4 files with no audio track *(macOS)*

→ [All products](https://yasunarimurayama.com/products/)

---

### How I work

I use AI-assisted development to accelerate implementation while retaining ownership of product definition, system design, integration, debugging, testing, documentation, and release decisions. The judgment doesn't come from the tool — knowing a queue should be bounded by lag rather than length comes from shipping the thing and finding where it breaks.

---

### Technologies

**Languages** — C, Python, JavaScript, TypeScript, Swift, HLSL, Bash
**Systems** — Node.js, React Native / Expo, SQLite, REST APIs, nginx, systemd, VPS deployment, CMake
**AI** — OpenAI API, local models via Ollama, AI-assisted development workflows
**Domain** — OBS Studio plugins, Syphon, DaVinci Resolve, color grading, live streaming, video post-production

---

### Background

Fifteen-plus years in audiovisual production — video, color correction, motion design, VFX, post. I started building software because the tools I needed either didn't exist, charged a subscription for one feature, or were designed by someone who had never had to deliver the shot.

---

### Contact

🌐 [yasunarimurayama.com](https://yasunarimurayama.com) · 🛍️ [murayama7.gumroad.com](https://murayama7.gumroad.com)

Open to remote roles: **Product Engineer · AI Automation Developer · AI Integration Engineer · Solutions Engineer · Creative Tools Developer · Full-stack Developer**
