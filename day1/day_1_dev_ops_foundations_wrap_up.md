# Day‑1 Wrap‑Up — DevOps Foundations (Ubuntu 22.04)

## 🎯 Objective
Establish a **clean, trustworthy local DevOps foundation** on a fresh Ubuntu 22.04 system—without cloud cost risk or tool sprawl.

**Status:** ✅ Achieved

---

## 🧱 What Was Set Up

### 🖥️ System Baseline
- Fresh Ubuntu 22.04 LTS
- System updated (`apt update && apt upgrade`)
- Known‑good starting state

### 🐳 Containers (Docker)
- Docker installed via official method
- Non‑root Docker usage enabled
- Core concepts validated:
  - Image vs container
  - Running vs stopped containers
  - Clean start/stop/remove workflow

### 📦 First Container Project
- Created a minimal app and **Dockerfile**
- Built a custom image
- Ran the container locally and exposed a port
- Practiced safe cleanup

### 🔍 Runtime Observability
- Used `docker stats` for live monitoring
- Interpreted:
  - CPU usage
  - Memory usage vs limits
  - Network I/O
  - Disk (block) I/O
  - PID counts

> Key insight: **Monitoring starts locally.** Runtime behavior tells the real story.

---

## 🗃️ Version Control (Modern & Secure)
- Initialized a local Git repository
- Connected to GitHub using **Personal Access Token (PAT)**
- Pushed initial commits successfully
- Added `.gitignore` to protect artifacts and secrets

**Result:** A clean, secure, reproducible repo.

---

## 🧠 Concepts Internalized
- Containers are **isolated processes**, not magic VMs
- Resource limits matter (even locally)
- Hygiene prevents future cloud mistakes
- Observability precedes security
- Version control is part of infrastructure, not an afterthought

These are **foundational engineering instincts**.

---

## 🧹 Hygiene & Discipline
- Cloud resources previously cleaned (no background billing risk)
- Local containers pruned at end of session
- Day ended with a **known, stable state**

---

## ✅ End‑of‑Day Health Check
- Local environment: clean & stable
- Docker: functional and understood
- Git/GitHub: connected and secure
- No running cloud costs
- No cognitive overload

---

## 🌙 Recommendation
Stop here for today. Let concepts settle.

Optional reflection (non‑technical):
- What clicked today?
- What was confusing?
- What am I curious about next?

---

## 🔜 Tomorrow (Preview)
Choose **one** next step:
- docker‑compose (multi‑container thinking)
- Service dependencies
- CI/CD preparation
- Kubernetes (only after the above)

> Build depth, not speed.

