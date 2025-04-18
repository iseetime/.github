# iseetime 🕒 *[Work in Progress]*

**An open-core time tracker under active development.**  
*Help us build a privacy-focused alternative to Timeular/Clockify!*  

![WIP Banner](https://placehold.co/600x100?text=🚧+Under+Construction+🚧)  

---

## 🚧 Current Status  
We’re in **early development** – expect breaking changes and missing features.  
- **Desktop App**: Basic time tracking (MVP in progress).  
- **Browser Extension**: Proof-of-concept for Jira/Azure DevOps.  
- **Server**: Core API skeleton (AGPLv3).  

**Want to help?** Jump to [Contributing](#-contributing).  

---

## 📂 Repo Structure  

| Component               | Repository                          | Status               |  
|-------------------------|-------------------------------------|----------------------|  
| **Desktop App**         | [iseetime/desktop](link)            | `Alpha` (Rust/Tauri) |  
| **Browser Extension**   | [iseetime/browser-extension](link)  | `Proof of Concept`   |  
| **Server Core**         | [iseetime/server-core](link)        | `Skeleton` (Go/PostgreSQL) |  
| **Docs**                | [iseetime/docs](link)               | `Draft`              |  

*(Private repos: `infra`, `admin` – not yet public)*  

---

## 🛠️ Getting Started (Developers)  

### Prerequisites  
- Rust (desktop app)  
- Go (server)  
- PostgreSQL (server)  

### Clone & Build  
```bash
# Clone all repos (public only)
git clone https://github.com/iseetime/desktop.git  
git clone https://github.com/iseetime/server-core.git  
```  

---

## 🤝 Contributing  
**We need help with:**  
- 🖥️ **Desktop App**: UI/UX design, auto-tracking logic.  
- 🌐 **Browser Extension**: Jira/Azure DevOps API integration.  
- 📡 **Server**: Authentication, database schema design.  

**Steps:**  
1. Check [Good First Issues](link).  
2. Comment on an issue to claim it.  
3. Follow our [trunk-based workflow](link).  

---

## 📅 Roadmap  
| Phase       | Goal                               | ETA       |  
|-------------|------------------------------------|-----------|  
| **TBA** | Desktop MVP (basic tracking)      | TBA  |  
| **TBA** | Browser extension MVP              | TBA  |  
| **TBA** | Hosted service beta                | TBA  |  

---

## 🚨 Warning  
This project is **not production-ready**. Expect:  
- ⚠️ Breaking API changes.  
- 🐛 Unstable features.  
- 📉 Missing documentation.  

---

## 📜 License  
- Core components: [AGPLv3](LICENSE).  
- *Proprietary tools (future): Contact [team@iseetime.com](mailto:team@iseetime.com).*  