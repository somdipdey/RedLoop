# RedLoop — Learn & practise AI red teaming across the Agile lifecycle with A4SRAI

**RedLoop** is a self-guided, offline learning tool that teaches the **Agile 4 Secure
Responsible AI (A4SRAI)** framework, lets you practise AI red teaming safely, structure your
findings across the lifecycle, and check your understanding — ending with a downloadable
red-team report and a completion certificate.

It is designed both as a standalone learning app for anyone starting to build AI systems, and
as a facilitator tool for workshops. It runs **fully offline**: no API keys, no internet.

---

## What's inside

RedLoop is organised as a learner journey (Connections → Concepts → Concrete Practice →
Conclusions). Use the left sidebar to move between sections:

1. **Home** — onboarding, the A4SRAI diagram, and your progress.
2. **Learn A4SRAI** — an interactive walk through the lifecycle: pick any stage to see what red
   teaming looks like there, which of the four components it belongs to, the responsible-AI
   principles at stake, example activities and controls. Includes concept primers and a glossary.
3. **Attack Library** — red-teaming techniques (prompt injection, jailbreak, data poisoning,
   model inversion, membership inference, bias exploitation, misuse, adversarial examples), each
   tagged with the RAI principle it threatens, its A4SRAI stage, how to test for it, and the
   control that mitigates it. Defensive framing throughout.
4. **Safe Sandbox** — watch a deliberately weak demo bot fail an attack, then watch a control
   block it. Everything is simulated and illustrative — no working exploit payloads.
5. **Threat-Modelling Wizard** — turn **your own** system (or a practice scenario) into concrete
   risks: get a tailored GenAI prompt, add risks one at a time, or paste a table back in.
6. **Risk Register** — an editable register (dropdowns for stage / RAI principle / attack type /
   likelihood / impact) with a live **risk matrix**, a severity-sorted view, and CSV export.
7. **Lifecycle Board** — your findings placed on the A4SRAI lifecycle, with a **deployment gate**
   that blocks while high-severity findings are open.
8. **Coverage & Standards** — a blind-spot **coverage grid** (component × RAI principle) plus a
   mapping of each A4SRAI component to the **EU AI Act**, **NIST AI RMF** and **ISO/IEC 42001**.
9. **Knowledge Check** — a pre-assessment, a post-assessment with feedback and a learning-gain
   score, and a downloadable **certificate**.
10. **Report & Export** — a red-team **report** (PDF or Markdown), register CSV, and **Save /
    Restore session** so your work survives a browser refresh.

---

## 1. Prerequisites

- **Python 3.9 or newer** (`python3 --version`)
- **pip**

## 2. Files

| File | Purpose |
|------|---------|
| `app.py` | The RedLoop application (the A4SRAI diagram is embedded — no separate image file needed) |
| `requirements.txt` | Python dependencies |
| `README.md` | This file |

## 3. Install

Using a virtual environment is recommended but optional.

**macOS / Linux**

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

**Windows (PowerShell)**

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

Or simply:

```bash
pip install -r requirements.txt
```

## 4. Run

```bash
streamlit run app.py
```

Streamlit prints a **Local URL** (usually `http://localhost:8501`) and opens it in your browser.
Press `Ctrl + C` in the terminal to stop.

### Solo learning / one screen
Just run it locally — everything works offline.

### Many learners on their own devices (same network)

```bash
streamlit run app.py --server.address 0.0.0.0
```

Share the **Network URL** Streamlit prints (e.g. `http://192.168.x.x:8501`). Each learner gets an
independent session, so registers and progress never mix between people.

---

## 5. Suggested flow

1. On **Home**, enter your name and take the **pre-assessment** (Knowledge Check → tab 1).
2. Work through **Learn A4SRAI**, the **Attack Library** and the **Safe Sandbox**.
3. Use the **Threat-Modelling Wizard** to turn a system into risks (type them in, or paste a
   table from your GenAI).
4. In the **Risk Register**, set likelihood/impact and **Generate risk matrix**.
5. Review the **Lifecycle Board** and **Coverage & Standards** to spot blind spots.
6. Take the **post-assessment**, download your **certificate**, and export a **report** on the
   Report & Export page.
7. Use **Save session (JSON)** before closing; **Restore** it next time to continue.

---

## 6. Notes

- **Offline & private.** Nothing you type leaves your machine. There are no API calls.
- **PDF export** uses `reportlab` (in `requirements.txt`). If it isn't installed, RedLoop falls
  back to a Markdown report and an HTML certificate automatically.
- **Session persistence.** Streamlit resets state on a page refresh; use *Save session* /
  *Restore* on the Report & Export page to keep your work.

## 7. Troubleshooting

- **`streamlit: command not found`** — the install didn't complete or your virtual environment
  isn't active. Re-run `pip install -r requirements.txt`, or use `python -m streamlit run app.py`.
- **Wrong Python / pip** — on some systems use `python3` / `pip3`.
- **Port already in use** — `streamlit run app.py --server.port 8502`.
- **Copy buttons** — inside a code box, use the copy icon in its top-right corner. This is most
  reliable on `localhost`.
- **No PDF** — install `reportlab` (it's in `requirements.txt`); RedLoop otherwise offers
  Markdown / HTML instead.


## 8. Credits & citation

RedLoop and the **A4SRAI (Agile 4 Secure Responsible AI)** framework are the work of
**Dr Somdip Dey**. The framework is published in IEEE Computer:
[Implementing AI Red Teaming to Develop Secure Responsible AI Models](https://ieeexplore.ieee.org/abstract/document/11220004).

If you use RedLoop in teaching or research, please cite that article.
