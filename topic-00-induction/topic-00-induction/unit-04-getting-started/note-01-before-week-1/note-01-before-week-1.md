---
order: 1
icon:
  type: fluent:settings-24-filled
  color: "#2D7FF9"
---

# Before Week 1

The Week 1 lab spends its first thirty minutes on orientation and the rest on getting your tools
working. You will get much more out of it if the downloads have already happened.

## The checklist

| | What | Why |
|---|---|---|
| ☐ | **Python 3.11 or later** | Everything else sits on top of it |
| ☐ | **A virtual environment** you know how to activate | You will install a lot of packages this semester |
| ☐ | **Git**, with a GitHub account and working authentication | Labs and the final project are distributed and submitted through it |
| ☐ | **Google Colab** — sign in once and open a notebook | The fallback when a laptop cannot carry the heavy weeks |
| ☐ | **A Hugging Face account** and an access token | Weeks 7 to 9 pull models constantly |
| ☐ | **Ollama** installed and one small model pulled | Week 7 onwards runs models locally |

PyTorch, transformers and the rest of the heavy stack are **not** needed until Week 3. The Week 1
lab installs a small, fast core first and offers a `--full` option for the heavy stack when you have
the time and the disk space.

## What the Week 1 lab gives you

The Week 1 lab archive contains a `setup.sh` (and `setup.ps1` for Windows) that creates the virtual
environment, installs the core packages and runs an environment check. It also contains
`setup_check.py`, which reports on Python, the scientific stack, PyTorch and any accelerator,
Hugging Face, Ollama, your git identity and whether you are running in Colab.

`setup_check.py` never crashes — it tells you what is missing. **Run it before the lab and bring its
output to the lab if something is wrong.** `INSTALL.md` in the same archive is the full guide,
including a troubleshooting table for the errors that actually come up.

## If you are short on hardware

Nothing in this module requires a GPU. The weeks that would benefit from one — 5, 8 and 9 — are built
around small models and short runs, and Colab covers the rest. If your machine is genuinely
constrained, say so in Week 1 rather than in Week 8.
