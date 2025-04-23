# **Day 1 of My Bug Bounty Journey**
---

**السلام عليكم ورحمة الله وبركاته**

Today, I didn’t attend classes, so I started the day with an easy-mode **TryHackMe** CTF and completed it in an hour 🚀.

Although I already know Linux (enough to get around comfortably 😄), I still began the **Linux Fundamentals** module on **HackTheBox**, since Linux is part of my semester syllabus.

I use **WSL with Kali Linux** — after experimenting with VirtualBox, I moved to WSL. Initially, I faced some issues with the Windows Terminal, but thankfully, ChatGPT helped me fix it (GPT >>> Copilot 😎).

I also have a **Digital Cloud VPS** (valid for 1 year; only a few months left now). I hadn’t utilized it much before, but now I use it daily for different tasks. Today, I worked on setting up automation with this amazing tool:

🔗 [Notify by ProjectDiscovery](https://github.com/projectdiscovery/notify)  
This lets you set up notifications via Discord, Telegram, Slack, email, etc.

### ✅ Tasks I Did Today:
- Installed a few more tools on the VPS 🛠️
- Though I started learning bug bounty 2–3 months ago, I’m officially restarting from scratch today.

> I’ll begin by mastering **Recon**, and alongside, I’ll pick one vulnerability to dive deep into.

---

## 🎯 Target & Recon

I selected a target with a **wildcard scope** and will stick with it throughout this journey.  
Started with **basic recon** using both manual and automated methods:

### 🧭 Manual Recon:
- Used [Subdomain Finder](https://subdomainfinder.c99.nl/)
- Queried [crt.sh](https://crt.sh/) to discover new subdomains
- Stored all findings in `.txt` files for reference

### ⚙️ Automated Recon:
- Tools used: `Subfinder`, `Amass`, `subrute.py`, `FFUF` (with a 2 million wordlist)
- Ran everything on VPS — it took around **2 hours** to collect and sort all subdomains
- Performed reverse IP and reverse DNS lookups using various online tools

---

## 📺 Learning Resources
Watched this amazing talk by **NahamSec** on **SSRF**  
🎥 [Watch here (41 mins)](https://youtu.be/6EyhhmIxPwg?si=B095x-KCIwOU_eAW) *(Tip: Use 2x speed)*

While doing recon, I kept discovering new terms and explored them with the help of the OG — **ChatGPT** 🙌. Took notes as well.

---

## 📚 Other Learning

- Continued learning **JavaScript** for better understanding of web apps
- Watched 2–3 lectures and practiced some basic code around **Promises in JS**

---

## 🎓 College Update

Didn’t study anything for my college syllabus today 😅  
From tomorrow, I’ll also start reading **HackerOne reports** and writeups focused on specific vulnerabilities.

I think I’ll begin with **SQL Injection**, since my current target seems to be using **MySQL** as the backend database.

---

> I’m not perfect — just trying to get better day by day.  
> I’m a **beginner**, not a pro — just a student learning from everyone 🤝

If you have any suggestions or tips, please reach out to me on [My X](https://x.com/n4itr0_07) and guide me. I’d truly appreciate it 🙏

---

**فِي أَمَانِ اللَّهِ**
