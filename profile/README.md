# iseetime 🕒

**Open-core time tracking for individuals and teams**  
*Track time effortlessly, integrate with Jira/Azure DevOps, and own your data.*  

![Demo](https://placehold.co/600x400?text=Demo+GIF+Here)  
*(Replace with a screenshot or demo GIF later)*  

---

## 🚀 Philosophy  
**Open by default, practical for everyone.**  
- **Core components** (desktop app, server, browser extension) are **100% open-source** (AGPLv3/GPLv3).  
- **Proprietary tools** (hosting setup, enterprise plugins) fund development and support.  
- No artificial limits – self-host freely or [use our hosted service](https://iseetime.com).  

---

## 📦 Components  

| Component               | Repository                          | License     | Purpose                              |  
|-------------------------|-------------------------------------|-------------|--------------------------------------|  
| **Desktop App**         | [iseetime/desktop](link)            | `GPLv3`     | Cross-platform time tracking (Win/macOS/Linux). |  
| **Browser Extension**   | [iseetime/browser-extension](link)  | `MIT`       | Integrate with Jira/Azure DevOps.    |  
| **Server Core**         | [iseetime/server-core](link)        | `AGPLv3`    | Self-hostable backend API + database.|  
| **Plugins**             | [iseetime/plugins](link)            | `Apache 2.0`| SSO, advanced exports, and more.     |  
| *Infrastructure*        | *Private*                           | Proprietary | Scalable cloud setup (Terraform/K8s).|  
| *Admin Tools*           | *Private*                           | Proprietary | License management and billing.      |  

---

## 🛠️ Getting Started  

### For Users  
1. **Download the desktop app**: [iseetime/desktop](link)  
2. **Install the browser extension**: [Chrome Web Store](link) / [Firefox Add-ons](link)  
3. **Self-host the server**: [iseetime/server-core](link) or [sign up for hosted service](https://iseetime.com).  

### For Developers  
```bash
# Clone the core components
git clone https://github.com/iseetime/desktop.git
git clone https://github.com/iseetime/server-core.git
```

---

## 🤝 Contributing  
We welcome contributions to all **open-source components**!  
- 🐛 **Bug reports**: Open an issue in the relevant repo.  
- 🌟 **Feature requests**: Discuss in [Discussions](link).  
- 💻 **Code**: Submit PRs to `main` (see [Contribution Guidelines](link)).  

**Monetization Note**:  
- Core features stay open forever.  
- We fund development via [hosted services](https://iseetime.com) and enterprise plugins.  

---

## ❓ FAQ  

### Q: Can I self-host the server for my company?  
**A:** Yes! The [AGPLv3 server-core](link) has no user limits. Need help? [Contact us](mailto:support@iseetime.com) for enterprise support.  

### Q: Why are some components closed-source?  
**A:** Proprietary tools (infra/admin) fund development. We’ll never retroactively close open-source code.  

### Q: Can I build a plugin?  
**A:** Absolutely! Check out [iseetime/plugins](link) for examples.  

---

## 📜 License  
- **Core code**: [AGPLv3](LICENSE) (server) / [GPLv3](link) (desktop).  
- **Third-party plugins**: Check individual repo licenses.  
- **Proprietary components**: Contact [sales@iseetime.com](mailto:sales@iseetime.com).  

---

## 🙌 Acknowledgements  
Inspired by the ethos of [Nextcloud](https://nextcloud.com) and [GitLab](https://gitlab.com).  