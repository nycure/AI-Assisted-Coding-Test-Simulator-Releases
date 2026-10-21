# AI-Assisted Recruitment Coding Assessment Simulator

An authentic simulation of modern corporate AI-assisted recruitment coding assessments. Prepare for technical interviews and corporate hiring tests in an environment equipped with a guarded scaffolding AI assistant, token budgets, multi-language Monaco editor, automated test runner, and a dual-pillar performance scorecard.

---

## 🌟 Key Features

### 1. Guarded AI Assistant with 5-Step Scaffolding Flow
Unlike general-purpose coding assistants that simply write solutions, this assessment assistant strictly enforces the corporate recruitment scaffolding flow:
1. **Phase 1: Problem Framing** — Candidates must describe the problem in their own words: inputs, expected outputs, and constraints.
2. **Phase 2: Data Structures Planning** — Candidates explain which data structures and variables they plan to use and why.
3. **Phase 3: Algorithmic Approach** — Candidates formulate step-by-step logic and recurrence/base-case reasoning before code is unlocked.
4. **Phase 4: Starter Code Stub** — Generates tailored starter code with an interactive **"Insert in Editor"** button.
5. **Phase 5: Iterative Refinement & Debugging** — Refinements require candidates to explain **WHAT** logic to change and **WHY**.

### 2. Strict DO's & DON'Ts Guardrails
- 🚫 **DON'T request complete solutions**: Prompts like *"write the code"*, *"just solve it"*, or *"give complete answer"* are intercepted with an explanation of assessment rules.
- 🚫 **DON'T ask to "optimize it" or "fix it" without explanation**: The assistant prompts candidates to explain the underlying logic first.
- 🚫 **No conversational drift or prompt injection bypasses**.

### 3. Realistic Assessment Constraints & Monaco Editor
- **Live Countdown Timer**: 20-minute exam timer with visual warning indicators.
- **Character Limit**: Real-time counter enforcing **500 characters** per prompt for clear communication.
- **Token Budget Meter**: Live tracking of token consumption (`Tokens used: X / 2000`) with visual progress bar.
- **Multi-Language Coding Panel**: Supports **Python 3.10**, **C (GCC 11.3)**, **C++**, **JavaScript (Node 18)**, and **Java (OpenJDK 17)**.
- **Monaco Code Editor**: Line numbers, syntax highlighting, bracket colorization, and dark/light themes.
- **Integrated Test Runner**: Built-in test execution for sample and hidden test cases, reporting Passed/Failed status, Expected vs. Actual output, and execution runtime. Also supports **Custom Input** testing.

### 4. Dual-Pillar Performance Scorecard (100 Marks Total)
Evaluates candidates across two equal recruitment pillars upon submission:
- **Pillar 1: Real Coding Marks (0 - 50 Marks)**: Directly based on passing automated test cases against standard and edge cases.
- **Pillar 2: AI Assistance & Collaboration Marks (0 - 50 Marks)**:
  - *Scaffolding Progression (0 - 20 pts)*: Advancement through problem framing, data structures, and approach.
  - *Prompt Quality & Specificity (0 - 15 pts)*: Depth, clarity, and precision of inputs/outputs/constraints.
  - *Rule Adherence & Integrity (0 - 10 pts)*: Following DOs & DON'Ts without asking for direct answers.
  - *Token & Prompt Efficiency (0 - 5 pts)*: Effective utilization of the 2,000-token budget.
- **One-Click Scorecard Export**: Save your complete performance evaluation and hiring verdict as a Markdown (`.md`) report.

---

## 🚀 Quick Start: How to Use

1. **Install**: Click **Install** from the VS Code Marketplace.
2. **Open the Simulator**:
   - Click the **AI Assessment Simulator** icon in the left Activity Bar.
   - Or click the **$(mortar-board) AI Coding Assessment** item in the bottom status bar.
   - Or open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) and select `AI Assessment: Start Practice Assessment`.
3. **Practice**: Browse problems from the **Question Bank**, collaborate with the AI assistant, write code in the editor, and run test cases.
4. **Submit**: Click **Submit Test** when finished to receive your comprehensive 100-mark evaluation scorecard!

---

## ⚡ AI Integration: Google Gemini 2.5 Flash

This extension is powered by **Google Gemini 2.5 Flash** for intelligent scaffolding and candidate evaluation:

* **Interactive Key Configuration**: Click the **`AI API KEY`** button in the AI Assistant header (or run `AI Assessment: Configure Gemini API Key` from the Command Palette) to connect your free API key from Google AI Studio.
* **Encrypted Keychain Storage**: Your API key is stored securely in your operating system's keychain (`SecretStorage`) and is never saved in plain-text configuration files.
* **Offline Practice Mode**: If no API key is configured or you are practicing offline, the simulator runs automatically using the built-in deterministic guardrail engine with full state-machine support.

---

## 📄 License

This extension is licensed under the MIT License.
