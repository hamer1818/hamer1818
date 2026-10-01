<!-- ═══════════════════════════════════════════════════════════
     HAMZA ORTATEPE · github.com/hamer1818
     ═══════════════════════════════════════════════════════════ -->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,50:3d59a1,100:7aa2f7&height=230&section=header&text=Hamza%20Ortatepe&fontSize=70&fontColor=ffffff&fontAlignY=36&desc=Language%20Designer%20%C2%B7%20Backend%20Engineer%20%C2%B7%20Systems%20Tinkerer&descSize=18&descAlignY=57&animation=fadeIn" alt="Hamza Ortatepe" />
</div>

<div align="center">
  <a href="https://github.com/hamer1818/TulparLang">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=7AA2F7&center=true&vCenter=true&width=640&lines=Building+TulparLang+%F0%9F%90%B4+my+own+programming+language;Python-easy+syntax.+C-class+performance.;LLVM+%C2%B7+AOT+%C2%B7+native+HTTP+out+of+the+box;Rust+%C2%B7+C%2B%2B+%C2%B7+C+%C2%B7+Python+%C2%B7+Linux" alt="typing" />
  </a>
</div>

<p align="center">
  <a href="https://hamza.tr"><img src="https://img.shields.io/badge/hamza.tr-1a1b26?style=flat-square&logo=googlechrome&logoColor=7aa2f7" /></a>
  <a href="https://tulparlang.dev"><img src="https://img.shields.io/badge/tulparlang.dev-1a1b26?style=flat-square&logo=llvm&logoColor=bb9af7" /></a>
  <a href="https://linkedin.com/in/hamzaortatepe"><img src="https://img.shields.io/badge/LinkedIn-1a1b26?style=flat-square&logo=linkedin&logoColor=7aa2f7" /></a>
  <a href="mailto:info@hamza.tr"><img src="https://img.shields.io/badge/info@hamza.tr-1a1b26?style=flat-square&logo=maildotru&logoColor=7aa2f7" /></a>
  <img src="https://komarev.com/ghpvc/?username=hamer1818&label=views&color=7aa2f7&style=flat-square" />
</p>

<br/>

## 👋 About Me

<table>
<tr>
<td width="56%" valign="top">

```go
// about.tpr — yes, it's written in my own language 🐴
import "wings";

str name     = "Hamza Ortatepe";
str location = "Türkiye 🇹🇷";

func about(req) {
    return {
        "role":      "Backend Architect & Language Designer",
        "education": {
            "degree": "Computer Programming — Ege University",
            "gpa":    3.86,
            "rank":   "Top graduate",
            "next":   "MIS @ Anadolu University"
        },
        "speaks":    ["Türkçe", "English"],
        "writes":    ["C", "C++", "Rust", "Python", "TypeScript"],
        "focus":     ["Compilers", "High-perf backends", "Linux"],
        "building":  "TulparLang"
    };
}

get("/about", about);
serve(8080);
```

</td>
<td width="44%" valign="top">

**🔭 Right now**
- 🐴 Shipping **[TulparLang](https://github.com/hamer1818/TulparLang)** — an LLVM-backed, AOT-compiled language
- 🎮 Building **[tulpar-engine](https://github.com/hamer1818/tulpar-engine)**, a C++ game engine
- 🎓 Studying Management Information Systems

**⚙️ How I work**
- Native > bloated. Single binary > 400 MB of `node_modules`
- If I do it twice, I automate it
- I run my own servers — Ubuntu · Nginx · Docker

**🤝 Open to**
- Compiler / systems collaborations
- OSS contributions & freelance backend work

<sub>⏰ GMT+3 · usually replies within 24h · ☕ filter coffee powered</sub>

</td>
</tr>
</table>

## 🐴 Featured — TulparLang

<p>
  <a href="https://github.com/hamer1818/TulparLang"><img src="https://img.shields.io/github/stars/hamer1818/TulparLang?style=flat-square&color=7aa2f7&labelColor=1a1b26&logo=github" /></a>
  <a href="https://github.com/hamer1818/TulparLang/commits/main"><img src="https://img.shields.io/github/last-commit/hamer1818/TulparLang?style=flat-square&color=bb9af7&labelColor=1a1b26" /></a>
  <img src="https://img.shields.io/badge/backend-LLVM%2018--22-9ece6a?style=flat-square&labelColor=1a1b26&logo=llvm" />
  <img src="https://img.shields.io/badge/license-MIT-e0af68?style=flat-square&labelColor=1a1b26" />
</p>

> **Python-easy syntax. C-class performance. HTTP-ready out of the box.**
> A statically-typed, ahead-of-time compiled language that turns `.tpr` files into dependency-free native binaries.

<table>
<tr>
<td width="50%" valign="top">

**A REST API in 6 lines**

```go
import "wings";

func home(req) {
    return {"hello": "world", "ts": now_iso8601()};
}

get("/", home);
serve(8080);
```

```bash
curl -fsSL https://tulparlang.dev/install.sh | bash
```

</td>
<td width="50%" valign="top">

**Why it's interesting**

- ⚡ **AOT via LLVM** — no VM, no interpreter, native code only
- 🌐 **`wings` stdlib** — HTTP/HTTPS server with 4 listener models
- 🧩 **First-class JSON** — literals + dot access, zero libraries
- 🛡️ **Gradual typing** — annotated code is checked at compile time
- 🇹🇷 **Bilingual** — Turkish & English keywords, UTF-8 everywhere
- 📦 **Single binary** — ~7 MB toolchain, nothing to install on target

</td>
</tr>
</table>

**Ecosystem** · [Docs site](https://github.com/hamer1818/tulpar-lang-web) · [VS Code extension](https://github.com/hamer1818/TulparLang-ext) · [Package example](https://github.com/hamer1818/tulpar-pkg-helloworld) · LSP & formatter built in

## 🛠 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,rust,python,ts,php,bash&theme=dark" /><br/>
<sub><b>LANGUAGES</b></sub>
<br/>
<img src="https://skillicons.dev/icons?i=llvm,cmake,qt,fastapi,nodejs,postgres,mysql,mongodb,supabase&theme=dark" /><br/>
<sub><b>SYSTEMS · BACKEND · DATA</b></sub>
<br/>
<img src="https://skillicons.dev/icons?i=astro,react,tailwind,vite&theme=dark" /><br/>
<sub><b>FRONTEND</b></sub>
<br/>
<img src="https://skillicons.dev/icons?i=linux,arch,ubuntu,docker,nginx,git,github,vscode&theme=dark" /><br/>
<sub><b>INFRA · TOOLING</b></sub>

</div>

## 🏆 Projects

<table>
<tr>
<th align="left" width="33%">⚙️ Systems & Native</th>
<th align="left" width="33%">🐧 Linux & Dev Tools</th>
<th align="left" width="34%">🖥️ Apps</th>
</tr>
<tr>
<td valign="top">

**[tulpar-engine](https://github.com/hamer1818/tulpar-engine)**<br/>
<sub>Game engine written from scratch</sub><br/>
<code>C++</code>

**[OwnCam](https://github.com/hamer1818/OwnCam)**<br/>
<sub>Android phone → Wi-Fi webcam with background removal</sub><br/>
<code>Rust</code>

**[lan-share](https://github.com/hamer1818/lan-share)**<br/>
<sub>High-performance LAN file sharing server</sub><br/>
<code>C++</code>

**[wallpaper-anim](https://github.com/hamer1818/wallpaper-anim)**<br/>
<sub>Animated wallpaper engine for Windows</sub><br/>
<code>C++</code>

</td>
<td valign="top">

**[frostbite-lcd](https://github.com/hamer1818/frostbite-lcd)**<br/>
<sub>CPU temperature on AIO cooler LCDs under Linux</sub><br/>
<code>Python</code>

**[TulparTools](https://github.com/hamer1818/TulparTools)**<br/>
<sub>Terminal app store on top of winget</sub><br/>
<code>CLI</code>

**[tpr-yt](https://github.com/hamer1818/tpr-yt)**<br/>
<sub>YouTube playlist → high-quality MP3</sub><br/>
<code>Shell</code>

**[fake-form-filler](https://github.com/hamer1818/fake-form-filler)**<br/>
<sub>Chrome extension that fills forms with Turkish test data</sub><br/>
<code>JavaScript</code>

</td>
<td valign="top">

**[fastci-ascii-generator](https://github.com/hamer1818/fastci-ascii-generator)**<br/>
<sub>ASCII art studio for images & videos</sub><br/>
<code>Python</code>

**[O-File-Process](https://github.com/hamer1818/O-File-Process)**<br/>
<sub>Multi-language file manager</sub><br/>
<code>PyQt6</code>

**[fastapiSocketChat](https://github.com/hamer1818/fastapiSocketChat)**<br/>
<sub>Real-time chat over WebSockets</sub><br/>
<code>FastAPI</code>

**[rent-a-car-with-python](https://github.com/hamer1818/rent-a-car-with-python)**<br/>
<sub>Car rental automation with DB integration</sub><br/>
<code>Python</code>

</td>
</tr>
</table>

<p align="right"><a href="https://github.com/hamer1818?tab=repositories"><sub>all repositories →</sub></a></p>

## 📊 GitHub Activity

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=hamer1818&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1b26&count_private=true&include_all_commits=true&rank_icon=github&hide=issues" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hamer1818&layout=compact&theme=tokyonight&hide_border=true&bg_color=1a1b26&langs_count=8&hide=html,css,mdx" />
  <br/>
  <img height="165" src="https://streak-stats.demolab.com/?user=hamer1818&theme=tokyonight&hide_border=true&background=1a1b26&ring=7aa2f7&fire=bb9af7&currStreakLabel=7aa2f7" />
</div>

<br/>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hamer1818/hamer1818/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hamer1818/hamer1818/output/github-contribution-grid-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/hamer1818/hamer1818/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

<br/>

<div align="center">
  <sub>🐴 <i>Tulpar</i> — the winged horse of Turkic mythology. Built with coffee, compiler warnings and a lot of <code>-O3</code>.</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:3d59a1,100:1a1b26&height=110&section=footer" width="100%" />
