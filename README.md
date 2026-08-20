<div align="center">

# ✦ Gemini Windows Computer-Use Agent ✦

**Direct Desktop GUI Automation • Natural Biomechanical Movement • Multi-Provider Engine**

[![Python 3.10+](https://img.shields.io/badge/Python-3.10%20%7C%203.11%20%7C%203.12-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Platform Windows](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/windows)
[![PySide6 GUI](https://img.shields.io/badge/GUI-PySide6%2060FPS-41CD52?style=for-the-badge&logo=qt&logoColor=white)](https://doc.qt.io/qtforpython/)
[![License: MIT](https://img.shields.io/badge/License-MIT-F59E0B?style=for-the-badge)](https://opensource.org/license/Apache-2.0)
[![Discord RPC](https://img.shields.io/badge/Discord-Rich%20Presence-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com)

*An autonomous, low-latency, free/low-cost Windows desktop computer-use agent powered by Google Gemini (3.5 Flash Lite & 3.7 Flash Thinking), OpenAI-compatible models (Groq LPU, DeepSeek, vLLM), and Ollama Cloud/Local.*

---

[🚀 Quickstart](#-quickstart) •
[🌟 Key Innovations](#-key-innovations) •
[🌐 Multi-Provider Switcher](#-multi-backend-llm-suite) •
[🖐️ Human Biomechanics](#-human-biomechanical-cadence) •
[🏝️ Dynamic Island HUD](#-dynamic-island-floating-hud) •
[⚡ Slash Commands](#-interactive-slash-commands) •
[🛡️ Safety & Takeover](#-safety--takeover-controls)

</div>

---

## Key Innovations

```
┌─────────────────────────────────────────────────────────────────────────────────────────┐
│                           GEMINI WINDOWS COMPUTER-USE RUNTIME                           │
├───────────────────────────┬─────────────────────────────┬───────────────────────────────┤
│     LLM Backend Suite     │    Human-Centric Motion     │      Desktop UI & System      │
├───────────────────────────┼─────────────────────────────┼───────────────────────────────┤
│ • Google AI Studio        │ • Cubic Bézier Mouse Splines│ • PySide6 Dynamic Island HUD  │
│   (3.5 Lite / 3.7 Flash)  │ • Fitts's Law Velocity Tail │ • Soft Cloud Radial Glow      │
│ • OpenAI-Compatible       │ • Biological Micro-Jitter   │ • F8 Hardware Takeover Key    │
│   (Groq LPU, DeepSeek)    │ • Natural Typing Cadence    │ • Discord Live Rich Presence  │
│ • Ollama Cloud & Local    │ • AI Fast Teleport Mode     │ • 10 TrueColor Themes         │
│ • Zero-Delay 429 Failover │ • Rate-Limit Auto-Failover  │ • 8-Step Interactive /guide   │
└───────────────────────────┴─────────────────────────────┴───────────────────────────────┘
```

* 🚀 **Multi-Backend Runtime Switcher (`/api`)**:
  - **Google AI Studio**: Native sub-second reasoning with `gemini-3.5-flash-lite` and deep `gemini-3.7-flash` thinking mode.
  - **OpenAI-Compatible Engine**: Connect directly to ultra-fast **Groq LPUs** (`llama-3.3-70b`), **DeepSeek**, or local **vLLM** instances.
  - **Ollama Cloud & Local**: Zero-setup local vision model support (`qwen2.5-vl`, `minicpm-v`, `llama-vision`).
* 🖐️ **True Biomechanical Human Cadence (`--mode human`)**:
  - **2-Stage Cubic Bézier Curves**: Moves along organic curved wrist paths rather than artificial straight lines.
  - **Fitts's Law Physics**: Rapid ballistic acceleration to peak speed at 35–40%, followed by long smooth deceleration.
  - **Target Overshoot & Correction**: Long sweeps (`>180px`) subtly overshoot by `2–6px` and settle smoothly back to target centers.
  - **Tapered Biological Jitter**: Simulates micro-tremors (`±0.5–1.0px`) that naturally dampen to 0 at destination for pixel-accurate clicks.
  - **Variable Keystroke Dynamics**: Typing pauses, dwell times, and breathing hesitation on punctuation.
* 🏝️ **PySide6 Dynamic Island Floating Glass HUD with Live Plan Checklist**:
  - Ultra-smooth 60 FPS hardware-accelerated frosted glass status pill (`QPainter` antialiasing).
  - **Dynamic Multi-State Morphing**: Compact pill (`290×48px`) when idle, expands into full task card (`390×84px`), and automatically grows into an **Interactive Live Plan Checklist Card** (`410×100-200px`) when executing multi-step plans.
  - **Real-Time Plan Progress Visualization**:
    - `✔` **Done (`[x]`)**: Neon green checkmark (`#4ade80`) with muted text.
    - `◉` **Active (`[/]`)**: Cyan pulsing dot (`#38bdf8`), bold text, and ambient background highlight box.
    - `○` **Pending (`[ ]`)**: Muted dark slate (`#64748b`).
    - `✖` **Blocked (`[!]`)**: Rose red glyph (`#f43f5e`).
    - Top right displays live step counts: `Plan: 2/4 Done` alongside a **traveling laser progress particle**.
    - Auto-ticks all steps `✔ Done` on task finish.
  - **100% Invisible to Vision (`WDA_EXCLUDEFROMCAPTURE`)**: Uses Win32 display affinity (`0x11`) so the AI vision model never sees the overlay in screenshots.
  - Interactive mouse dragging anywhere on the card + right-click context menu (Compact Mode, Hide, Reset).
* 🎯 **Mandatory Rigorous Planning Protocol (`--effort xhigh` & `--effort ultra`)**:
  - Automatically enforces strict Turn 1 plan formulation before touching mouse or keyboard.
  - Formulates structured `GOAL_CHECKLIST:` in thoughts and audits state on every turn before completion.
* 🌌 **Natural Soft Cloud Desktop Glow & Unified Qt Runtime**:
  - Single unified background Qt event loop (`utils/qt_manager.py`) driving both HUD and screen glow with zero GUI collisions.
  - Atmospheric PySide6 radial gradient glow that fades in when the agent is controlling your screen and fades out when it pauses.
  - Non-interactive click-through (`WS_EX_TRANSPARENT`).
* 🔑 **Multi-Key Rotation Pool with 0s Failover**:
  - Pool multiple Gemini API keys in `.env`. The agent auto-detects 429 quota exhaustion and rotates keys in `<0.05s` with zero delays.
* 🚨 **Zero-Latency Emergency Takeover (`F8`)**:
  - Win32 low-level keyboard hook lets you press `F8` (or `Pause`, `Esc`) at any millisecond to immediately freeze the agent and take manual control.
* 👾 **Discord Rich Presence (RPC)**:
  - Real-time status broadcasting on Discord with custom activity details and step counters.
* 🎨 **10 Modern Designer TrueColor Themes (`/theme`)**:
  - Catppuccin Mocha, Tokyo Night, Claude Amber, Dracula, Nord Arctic, Matrix Green, Cyberpunk 2077, Monokai Pro, Rosé Pine, and Gemini Cyber.
* 🧭 **8-Step Interactive Guide Tour (`/guide`)**:
  - Interactive keyboard-controlled walk-through explaining all settings, vision resolutions, and controls on first run.

---

## Comparison with Other Tools

| Feature | **Gemini Windows Agent** (This Project) | **Anthropic Computer Use** | **Open-Interpreter** | **Microsoft UFO / ShowUI** |
| :--- | :---: | :---: | :---: | :---: |
| **Native Windows 10/11 Desktop** | ✅ **Direct Native** | ❌ (Linux/Docker X11 only) | ⚠️ (Code execution only) | ⚠️ (Research Script) |
| **Multi-Provider Engine** | ✅ **Google, Groq/OpenAI, Ollama** | ❌ (Claude only) | ⚠️ (Terminal models) | ❌ (OpenAI only) |
| **Human Bezier Motion & Cadence** | ✅ **Cubic Bézier + Jitter + Typing** | ❌ (Robotic instant) | ❌ (No GUI movement) | ❌ (Robotic instant) |
| **Dynamic Island Floating HUD** | ✅ **PySide6 60FPS Morphing** | ❌ (None) | ❌ (None) | ❌ (None) |
| **Ambient Radial Screen Glow** | ✅ **Soft Cloud PySide6** | ❌ (None) | ❌ (None) | ❌ (None) |
| **Screenshot Invisibility Shield** | ✅ **WDA_EXCLUDEFROMCAPTURE** | ❌ (None) | ❌ (None) | ❌ (None) |
| **Emergency Takeover Key** | ✅ **F8 Win32 Global Hook** | ❌ (None) | ❌ (None) | ❌ (None) |
| **Multi-Key 429 Auto-Failover** | ✅ **Instant 0s Rotation** | ❌ (None) | ❌ (None) | ❌ (None) |
| **Discord Rich Presence (RPC)** | ✅ **Live Telemetry** | ❌ (None) | ❌ (None) | ❌ (None) |
| **Session Replay & Rollback** | ✅ **Full Context Tree** | ❌ (None) | ⚠️ (History text) | ❌ (None) |

---

## Quickstart

### 1. Prerequisites
* **OS**: Windows 10 or Windows 11 (64-bit).
* **Python**: Python 3.10, 3.11, or 3.12.

### 2. Installation
```powershell
# Download from release
cd Gemini-Windows-Computer-Use

# Create virtual environment
python -m venv venv
.\venv\Scripts\Activate.ps1

# Install requirements
pip install -r requirements.txt
```

### 3. Configure API Key
Create a `.env` file (or copy [.env.example](file:///.env.example)):
```env
# Free Google AI Studio API Key (https://aistudio.google.com/)
GEMINI_API_KEY="AIzaSyYourGeminiKeyHere"

# Optional: Pool multiple keys for zero-wait rotation on quota limits
GEMINI_API_KEYS="AIzaSyKey1,AIzaSyKey2,AIzaSyKey3"
```

### 4. Run Agent
```powershell
# Launch interactive developer CLI:
python run.py

# Or launch with preferred defaults:
python run.py --mode human --effort ultra --theme tokyonight
```

---

## Multi-Backend LLM Suite

Switch providers seamlessly at runtime by typing `/api` in the prompt:

### 1. Google AI Studio (Default)
* **`gemini-3.5-flash-lite`**: Ultra-fast, minimal token footprint, low cost.
* **`gemini-3.7-flash`**: High-demand reasoning & deep visual thinking.
* **`gemini-3.1-pro-preview`**: Deep multi-step planning and heavy reasoning.

### 2. OpenAI-Compatible (Groq LPU / DeepSeek / vLLM)
```powershell
# Run with Groq ultra-fast LPU:
python run.py --api-provider openai --base-url https://api.groq.com/openai/v1 --openai-model llama-3.3-70b-versatile
```

### 3. Ollama (Local & Cloud)
```powershell
# Run with local Ollama vision model:
python run.py --api-provider ollama --base-url http://localhost:11434/v1 --ollama-model qwen2.5-vl
```

---

## Interactive Slash Commands

Type these directly into the `✦ >> Enter prompt:` CLI at any time:

| Command | Usage | Description |
| :--- | :--- | :--- |
| **`/guide`** | `/guide` | Launch interactive keyboard-controlled onboarding tour. |
| **`/api`** | `/api [google\|openai\|ollama]` | Switch active LLM backend provider. |
| **`/model`** | `/model <id>` | Switch model (e.g. `gemini-3.7-flash`, `gpt-4o`, `qwen2.5-vl`). |
| **`/effort`** | `/effort [low\|med\|high\|xhigh\|ultra]` | Set reasoning depth & verification turns (`ultra` = max turns). |
| **`/max_turns`** | `/max_turns [1,2,3...\|-1]` | Set maximum execution turns per task (`-1` = dynamic auto choice). |
| **`/mode`** | `/mode [human\|ai]` | Toggle natural human motion vs instant AI automation. |
| **`/theme`** | `/theme [name]` | Switch UI theme with live color swatches (10 palettes available). |
| **`/image_resolution`** | `/image_resolution [low\|med\|high\|original]` | Set vision resolution (low=258 tok, med=516 tok, original=1:1). |
| **`/rpc`** | `/rpc [on\|off]` | Toggle Discord Rich Presence broadcasting. |
| **`/keys`** | `/keys` | View API key rotation pool, quotas, and failover status. |
| **`/add-key`** | `/add-key <key>` | Add a new Gemini API key to rotation pool live. |
| **`/proxy`** | `/proxy [url\|off]` | Configure HTTP/HTTPS/SOCKS5 proxy endpoint. |
| **`/permission`** | `/permission [user\|admin]` | Toggle permissions between standard and elevated admin mode. |
| **`/btw`** | `/btw <question>` | Ask a side question about your screen without moving mouse/keyboard. |
| **`/control-key`** | `/control-key <key>` | Change emergency takeover key (`f8`, `pause`, `esc`, `delete`). |
| **`/resume`** | `/resume [id]` | Resume a previous task session with full history. |
| **`/clear`** | `/clear` | Clear terminal and start fresh conversation context. |
| **`/help`** | `/help` or `?` | Show commands reference table. |
| **`/bye`** | `/bye`, `/by`, `exit`, `q` | Safely close the agent. |

---

## Testing & Verification

Run the automated test suite covering all tools, safety filters, theme palettes, and agent mock loops:

```powershell
python -m unittest discover -s tests
```

---

## License & Open Source

This project is licensed under the **Apache 2.0**. You are free to use, modify, distribute, and integrate this software into personal and commercial projects.

---

<div align="center">
Built with 💙 for the next generation of autonomous desktop AI pair programming.
</div>
