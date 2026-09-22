<div align="center">
  <a href="https://youtu.be/HJs2wcEHYQk">
    <img src="https://img.youtube.com/vi/HJs2wcEHYQk/0.jpg" alt="Cloudflare’s AI Hacker: The Security Audit Agent That Disproves Your Code!">
  </a>
  <h3>📺 <a href="https://youtu.be/HJs2wcEHYQk">Watch the full tutorial on YouTube</a></h3>
</div>

# 🛡️ Cloudflare Security Audit Skill

Automate deep security audits on your codebase using the **Cloudflare Security Audit Skill** inside the **Antigravity Agent**.

> 💡 **Note for Viewers**: Place your own source code files directly inside the `src/` subfolder. The agent will audit whatever codebase you keep in `src/`.

---

## 📂 Project Structure

```text
security-audit-skill/
├── src/                    # Place your source code files here to be audited
├── outputs/                # Destination directory where all audit reports are saved
└── README.md               # Step-by-step instructions & short agent prompts
```

---

## 🚀 Prompts 

Copy and paste these **3 short prompts** in order into **Antigravity Agent** chat window.

---

### 📌 Prompt 1: Install & Verify Skill

```text
Install and verify the Cloudflare Security Audit skill in your global environment:
npx skills add https://github.com/cloudflare/security-audit-skill --skill security-audit --global
Confirm once the security-audit skill is active.
```

---

### 📌 Prompt 2: Analyze `./src` Codebase

```text
Perform a full security audit on the codebase inside `./src`.
Run reconnaissance, coverage-led hunting, and adversarial validation across all files in `./src` to find all security vulnerabilities.
```

---

### 📌 Prompt 3: Save Audit Reports to `./outputs`

```text
Save all final security audit findings and report artifacts into the `./outputs` folder.
Generate `./outputs/outputs.md`, `./outputs/findings.json`, and `./outputs/coverage-ledger.json`.
```

---

## 📊 Expected Outputs in `outputs/`

After running Prompt 3, your audit results will be saved in `outputs/`:

- 📄 **`outputs/outputs.md`**: Executive summary and detailed vulnerability findings.
- 📋 **`outputs/findings.json`**: Structured JSON schema output of confirmed findings.
- 🗺️ **`outputs/coverage-ledger.json`**: Verification ledger mapping scanned code.

---
**Keywords**: Cloudflare, AI Hacker, Security Audit, Agent, Automated Testing, Vulnerability Scanner, Antigravity Agent, DevSecOps, Code Analysis, AI Security
