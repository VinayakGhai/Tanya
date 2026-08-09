<p align="center">
  <a href="https://github.com/VinayakGhai/Tanya">
    <img src="assets/logo.png" width="240" alt="Tanya Logo" style="border-radius: 16px; box-shadow: 0 10px 30px rgba(139,92,246,0.3);">
  </a>
</p>

<h1 align="center">📰 Tanya - Polyglot News Engine</h1>
<p align="center">
  <b>Polyglot News Aggregator (Rust, C++, Go, Java, Python, Julia, Elixir)</b>
</p>

<p align="center">
  <a href="https://github.com/VinayakGhai/Tanya/releases/latest"><img src="https://img.shields.io/badge/Windows-Download_.exe-0078D4?style=for-the-badge&logo=windows" alt="Windows Download"></a>
  <a href="https://github.com/VinayakGhai/Tanya/releases/latest"><img src="https://img.shields.io/badge/Linux-Download_.AppImage-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux Download"></a>
  <a href="https://github.com/VinayakGhai/Tanya/releases/latest"><img src="https://img.shields.io/badge/macOS-Download_.dmg-000000?style=for-the-badge&logo=apple" alt="macOS Download"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-GPLv2-8b5cf6?style=for-the-badge" alt="License"></a>
</p>

---

Tanya (Trending And New Yielded Articles) is a **real polyglot news aggregator**—not a demo. Each language does actual work.

**Python is only ~20%** of the codebase. The rest is 22 other languages.

---



## 📌 Project Overview

Tanya is a multi-language news aggregation platform that demonstrates how different programming languages can work together in a modular architecture.

Each language in the project handles a specific responsibility such as scraping, processing, analytics, API serving, or UI rendering. The goal is to showcase interoperability between languages while building a real working news aggregation system.

This project is suitable for contributors interested in:
- Polyglot architecture
- Distributed systems
- Cross-language integration
- Performance comparisons between languages
---
---

## 📁 Project Structure

Below is a simplified overview of the repository layout:

- `app.py` – Streamlit UI layer (Python)
- `rust/` – Core RSS fetching and storage engine
- `cpp/` – Duplicate detection logic
- `go/` – Background worker service
- `java/` – REST API server
- `js/` – Alternative scraper
- `c/` – Low-level RSS parser
- `kotlin/` – JVM-based scraper
- `julia/` – Analytics module

Refer to individual folders for language-specific build and run instructions.


## 🏗️ Architecture

| Language | Component | What It Does |
|----------|-----------|--------------|
| **Python** | UI Layer | Streamlit web interface (~10%) |
| **Rust** | Core Engine | RSS fetching, full-text search, storage |
| **C++** | Processing | High-speed duplicate detection |
| **Go** | Worker | Background news fetching daemon |
| **Java** | API | REST API server |
| **Node.js** | Scraper | Alternative RSS scraper |
| **JavaScript** | Frontend | UI components |
| **C** | Parser | RSS parsing |
| **Kotlin** | Scraper | JVM-based scraper |
| **Julia** | Analytics | Scientific computing & stats |
| **Elixir** | Fetcher | Functional RSS fetcher |
| **Lua** | Scraper | Lightweight scraper |
| **Ada** | Validator | RSS validation |
| **Assembly** | Parser | Header parsing |
| **Perl** | Text | Text processing |
| **Fortran** | Stats | Statistical analysis |
| **R** | Analytics | Data analytics |
| **C#** | Notifications | Desktop notifications |
| **Ruby** | Newsletter | Newsletter delivery |
| **PHP** | Webhooks | HTTP callbacks |
| **Delphi** | Desktop | Desktop UI |
| **Scratch** | Prototype | Visual prototype |

---

## 🚀 Quick Start

### UI Only (Python)
```bash
pip install -r requirements.txt
streamlit run app.py
```

### Full Polyglot
See [INSTALL.md](INSTALL.md) for all languages, then:
```bash
./build.sh
streamlit run app.py
```

---

## 🛠️ Usage by Language

| Language | Run Command |
|----------|-------------|
| Rust | `./rust/target/release/rss_fetcher` |
| C++ | `./cpp/bin/dedup stats` |
| Go | `go run go/cmd/worker.go --once` |
| Java | `cd java/src && java APIServer` |
| Node.js | `node js/src/scraper.js` |
| C | `gcc -o bin/parser c/rss_parser.c && ./bin/parser` |
| Kotlin | `kotlinc -include-runtime -d rss.jar kotlin/src/rss_scraper.kt` |
| Julia | `julia julia/src/analyzer.jl` |
| Elixir | `mix run elixir/lib/rss_fetcher.exs` |
| Lua | `lua lua/scraper.lua` |
| Ada | `gnatmake ada/src/ada_validator.adb` |
| Assembly | `nasm -f elf64 asm/src/asm_parser.asm && ld` |

---

## 📥 Installation

See [INSTALL.md](INSTALL.md) for complete setup on Ubuntu, macOS, Windows (WSL).

---

## 🤝 Contributing

Contributions in any language are welcome!

To contribute:

1. Fork the repository.

2. Create a new branch:
   ```bash
   git checkout -b feature-name
3. Make your changes.

Commit your changes:

git commit -m "Describe your changes"


4. Push your branch:

git push origin feature-name


5. Open a Pull Request.


Save the file.

---





# ✅ After Pasting

Save the file.

Then run:

```bash
git add README.md
git commit -m "Improve documentation: enhanced contributing section clarity and formatting"
git push origin improve-docs

## 📜 License

MIT License - see [LICENSE](LICENSE).

---

<div align="center">

**Built with ❤️ by [Nayak](https://github.com/Nayak-indie)**

*Python: 10% | 22 Other Languages: 90%*

</div>


---

Documentation improvements contributed by @Chandana-basude
