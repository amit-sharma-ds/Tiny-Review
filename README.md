# ⚡ TinyReview — AI Code Reviewer (Tier 1)

## 🚀 Live Demo
https://tinyreview.vercel.app

![]()
---

## 💡 Idea
A **zero-cost, in-browser AI code reviewer** that works using a **Tier 1 weak model**.

No API. No backend. No data leaves your device.

---

## 🤖 Model
- gemma-2-2b-it-q4f16_1-MLC  
- Tier 1 · Absolute Garage  
- Runs via WebLLM (browser)

---

## ⚙️ How It Works
- Paste code  
- Model generates structured review (JSON)  
- Output shows:
  - Bugs  
  - Security issues  
  - Improvements  
  - Scores  

---

## 🛠️ Engineering
- Structured prompting (JSON output)
- Validation layer (fix bad outputs)
- Streaming responses
- Static fallback (works without WebGPU)

---

## 💸 Cost
$0.00 — fully local

---

## ⚠️ Limitations
- Weak model → may miss complex issues  
- Needs WebGPU for full AI mode  

---

## 🏆 Core Idea
**Weak model + smart engineering = useful output**

