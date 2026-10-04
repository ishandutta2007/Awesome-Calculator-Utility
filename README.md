# Awesome-Calculator-Utility

# Awesome-Calculator-Utility

**Curated List of Commercial Software & Open-Source GitHub Projects**
*Focused on Scientific Calculation, Unit Conversion, Notepad-Style Math & Graphing*
**Last updated: October 2026**

This repository tracks notable **commercial calculator utilities** and **open-source projects** that help users perform everything from basic arithmetic to complex scientific computation, unit conversion, and natural-language math.

**Examples** include Windows Calculator, PCalc, Calcbot, Desmos, SpeedCrunch, Soulver, Wolfram Alpha, HP 12C Calculator, HiPER Scientific Calculator, and Numi (the category leaders).

**Open-source emphasis**: The calculator utility space has an **exceptionally mature and diverse open-source ecosystem**. **Windows Calculator** itself is open source under MIT with **40,387 stars**, shipping standard, scientific, and programmer modes plus unit and currency conversion . **SpeedCrunch** is the highest-rated open-source calculator across AlternativeTo with **128 alternatives ranked below it**, offering high precision, syntax highlighting, and keyboard-first design . **Qalculate!** is the most feature-dense cross-platform calculator with **118 alternatives ranked below it**, supporting arbitrary precision, symbolic calculations, units, and currency conversion . **NoteCalc** brings Soulver-style natural-language math to the browser as a Rust/WASM app . This section documents these production-grade solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [Commercial Software](#commercial-software)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Commercial Software

- **[PCalc](https://pcalc.com/)**
  **The most awarded calculator app for Apple platforms.** Provides standard, scientific, and programmer modes with RPN support, customizable themes, and deep integration with macOS, iOS, and watchOS. **Best for**: Apple users wanting a polished, feature-rich calculator.

- **[Calcbot](https://tapbots.com/calcbot/)**
  **Beautiful calculator for iPhone, iPad, and Apple Watch.** Provides unit conversion, calculation history, and a clean interface from the makers of Tweetbot. **Best for**: Users prioritizing design and simplicity.

- **[Desmos](https://www.desmos.com/)**
  **The leading online graphing calculator.** Provides interactive graphing, sliders, tables, and regression tools. Free for web and mobile with a clean, modern interface. **Best for**: Students, teachers, and anyone needing to visualize mathematical functions.

- **[Soulver](https://soulver.app/)**
  **The original notepad calculator for macOS and iOS.** Type math in plain English and get instant answers alongside your notes. **Best for**: Mac users wanting natural-language calculation without switching apps.

- **[Wolfram Alpha](https://www.wolframalpha.com/)**
  **Computational knowledge engine that solves math, science, and engineering problems.** Provides step-by-step solutions, plots, and expert-level answers across virtually every domain. **Best for**: Students, researchers, and professionals needing deep computational answers.

- **[HP 12C Calculator](https://www.hp.com/us-en/shop/pdp/hp-12c-financial-calculator)**
  **The legendary financial calculator used by professionals for decades.** Provides RPN entry, financial functions, and a proven track record in finance and real estate. **Best for**: Finance professionals and RPN enthusiasts.

- **[HiPER Scientific Calculator](https://hiperlabs.eu/)**
  **Advanced scientific calculator with result history and themes.** Available on Android and Windows. **Open source** (Windows Edition marked "100% open source") . **Best for**: Android and Windows users wanting a feature-rich scientific calculator.

- **[Numi](https://numi.app/)**
  **Handy calculator app for macOS that describes tasks in natural language.** Type `$20 in euro - 5% discount` or `today + 2 weeks` and get instant answers. **Best for**: Mac users wanting natural-language calculation.

## Open-Source GitHub Projects

### Full-Featured Scientific Calculators

- **[Windows Calculator](https://github.com/Microsoft/calculator)**
  **Microsoft's official Windows Calculator, open source under MIT.** **40,387 stars, 31,058 forks** . **Key features**: **Standard Calculator** — basic operations evaluated immediately; **Scientific Calculator** — expanded operations with order of operations; **Programmer Calculator** — conversion between common bases; **Date Calculation** — difference between dates, add/subtract years/months/days; **Unit and currency conversion** based on Bing data; **Infinite precision** for basic arithmetic operations . **Graphing mode** is on the roadmap with community-contributed UI . **Platforms**: Windows 11 (build 22000+) . **Best for**: Windows users wanting the official calculator with community contributions.

- **[SpeedCrunch](https://github.com/agatti/speedcrunch)**
  **The highest-rated open-source calculator on AlternativeTo (128 alternatives ranked below).** **GPL-2.0 licensed** . **Key features**: **High-precision scientific calculation**; **Syntax-highlighted scrollable display**; **Keyboard-first design** — fully usable without mouse; **Auto-completion of functions and variables**; **Formula book** for quick reference; **Quick insertion of constants** from various fields . **Available for Windows, macOS, and Linux** in multiple languages . **Note**: Listed as "Discontinued" on AlternativeTo but the repository remains active . **Best for**: Users wanting a fast, precise, keyboard-driven calculator.

- **[Qalculate!](https://github.com/Qalculate)**
  **The most feature-dense open-source calculator (118 alternatives ranked below).** **GPL-2.0 licensed** . **Key features**: **Arbitrary precision**; **Symbolic calculations**; **Unit support** with full dimensional analysis; **Currency conversion**; **Customizable functions**; **CLI and GUI** (Qt, GTK, and more) . **Available via Flathub and Snap** . **Best for**: Power users, scientists, and engineers needing maximum calculation capability.

### Notepad-Style & Natural Language Calculators

- **[NoteCalc](https://github.com/bbodi/notecalc3)**
  **Free Soulver alternative in your browser.** **Rust/WASM** application . **Key features**: **Notepad with smart built-in calculator**; evaluates expressions as you type; **user-defined functions** (0.4.0); **conditionals and comparisons** (0.4.0); **configurations** (decimal point, font size) . **Run locally** with `./compile_and_run.bat` or **Docker**: `docker run --rm -d -p 5000:5000 notecalc3` . **Best for**: Users wanting Soulver-style natural-language math in the browser.

- **[calced](https://pypi.org/project/calced/)**
  **Notepad calculator that evaluates math in plain text files.** **Tiny, no dependencies** — CLI is a single 47KB Python file (stdlib only), web app is a single 52KB HTML file . **Key features**: **CLI and web app** with same syntax; **Variables**; **Percentages**; **SI prefixes** (k, M, G, T, etc.); **Unit conversions** (length, mass, temperature, data, time, volume); **Rate conversions** with `@rate`; **Date arithmetic** (days, weeks, months, years); **Totals** with `total`/`sum`; **Number formats** (commas, underscores, hex, binary, octal, scientific) . **Installation**: `pip install calced` or `uv tool install calced` . **Best for**: Developers and analysts wanting reproducible plain-text calculations.

### Android & Mobile Calculators

- **[Fossify Calculator](https://github.com/FossifyOrg/Calculator)**
  **Privacy-focused Android calculator with no ads and no internet permission.** **Open source** . **Key features**: **Basic and advanced operations** (roots, powers, common functions); **Unit conversions**; **Offline operation** — no internet permission requested; **Calculation history**; **Customizable colors and themes**; **Button vibration and display preferences** . **Available on F-Droid and OpenAPK** . **Best for**: Android users wanting a privacy-respecting, ad-free calculator.

- **[Uno Calculator](https://github.com/unoplatform/calculator)**
  **C# port of Windows Calculator for iOS, Android, WebAssembly, and Linux.** **380 stars** . **Key features**: **Standard, scientific, and programmer modes**; **Unit and currency conversion**; **Infinite precision** for basic operations . **Available on App Store, Play Store, Snap Store, and web** . **Best for**: Users wanting the Windows Calculator experience on non-Windows platforms.

### Additional Strong Open-Source Options

- **Scientific Calculators**: **Windows Calculator** (MIT, official, 40k+ stars), **SpeedCrunch** (GPL-2.0, keyboard-first), **Qalculate!** (GPL-2.0, most feature-dense), **HiPER Scientific Calculator** (open source, Android/Windows) .
- **Notepad/Natural Language**: **NoteCalc** (Rust/WASM, Soulver alternative), **calced** (Python, plain-text files) .
- **Mobile**: **Fossify Calculator** (Android, privacy-focused), **Uno Calculator** (cross-platform C# port) .
- **Graphing**: **Desmos** (web/mobile, free), **GeoGebra** (open-source graphing calculator) .
- **Linux Desktop**: **KCalc** (KDE), **GNOME Calculator**, **galculator**, **Kalk**, **Qalculate! Qt/GTK** .

**Frameworks for building custom systems**: Combine **Qalculate!** for maximum scientific capability with symbolic math and units, **SpeedCrunch** for fast keyboard-driven calculation, **NoteCalc** or **calced** for notepad-style natural-language math, and **Windows Calculator** for a familiar, polished UI with community contributions. For Android, **Fossify Calculator** provides privacy-first offline calculation . Add **Desmos** or **GeoGebra** for graphing needs .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Calculator utilities handle potentially sensitive financial and personal data; ensure proper privacy practices and avoid entering sensitive information into cloud-based calculators without review.
- **Open-source reality**: The calculator utility space has an **exceptionally mature and diverse open-source ecosystem**. **Windows Calculator** is open source under MIT with 40,387 stars and ships with Windows . **SpeedCrunch** (GPL-2.0) is the highest-rated open-source calculator across AlternativeTo . **Qalculate!** (GPL-2.0) is the most feature-dense with arbitrary precision, symbolic math, and full unit support . **NoteCalc** and **calced** bring Soulver-style natural-language math to the browser and CLI . **Fossify Calculator** delivers privacy-first Android calculation with no internet permission . **Uno Calculator** ports the Windows Calculator experience to iOS, Android, WebAssembly, and Linux . For virtually every calculator need, the open-source path is **genuinely viable and often preferred**.

---

**Made for students, engineers, scientists, finance professionals, and everyday users.**
Let's make calculation more open, precise, and accessible.
