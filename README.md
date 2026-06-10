# Hi 👋, I'm Aseel Herzallah

- 🎓 B.Sc. in Computer Science — Ben-Gurion University
- 💻 Full-Stack & Systems Developer | MERN, OS Internals & Security
- 🌍 Based in Israel

I build production-style full-stack applications and low-level systems projects. My strongest work is a **Twitter clone** with real auth, feeds, DMs, and an in-app AI assistant — deployed live on Vercel and Render.

I also work close to the machine through **xv6 kernel extensions**, **network security labs**, and **SPL coursework** in C, C++, and Java.

Currently looking for my first full-time role in **full-stack development**, **systems software**, or **security engineering**.

---

## 🔥 Featured Projects

### 🐦 Twitter Clone — Full-Stack Social Platform

Classic Twitter rebuilt from scratch — the timeline, reposts, bookmarks, DMs, and an in-app AI assistant called **Nest**.

- Full MERN stack with JWT auth (`httpOnly` cookies), bcrypt, and protected routes
- For You / Following feeds, infinite scroll, reposts, quote tweets, likes, comments, bookmarks, pin
- Real-time DMs, notifications, live search, trending hashtags, suggested users
- Profile editing — bio, website, birthday, cover/avatar crop via Cloudinary
- **Nest AI** — in-app OpenAI assistant for search, trends, and thread summaries
- Mobile-first UI, light/dark/system theme, optimistic cache updates (TanStack Query)
- Split production deploy: **Vercel** (frontend) + **Render** (API)

🔗 **Live demo:** [twitter-clone-mu-gilt.vercel.app](https://twitter-clone-mu-gilt.vercel.app) · **Repo:** [twitter-clone](https://github.com/AseelHerzallah1/twitter-clone)

---

### ⚙️ xv6 Kernel Enhancements — Operating Systems (BGU)

Three independent kernel-level extensions on the **xv6-riscv** teaching OS:

- **System calls:** `memsize`, `forkn`, `waitall`, exit messages — full user→kernel data transfer and argument validation
- **Shared memory:** Cross-process shared mappings via page-table manipulation and reference counting; multi-process logging with atomic operations
- **Synchronization:** Peterson locks, tournament tree (up to 16 processes), sleep/wakeup primitives — debugged under QEMU/GDB

**Repo:** [Operating-Systems---BGU](https://github.com/AseelHerzallah1/Operating-Systems---BGU)

---

### 🔐 Memory Game RAT — Network Security Lab

Educational Remote Access Trojan disguised as a harmless **Pygame memory card game**.

- Covert TCP C2 connection on port 9999 while the game runs in the foreground
- XOR-encrypted command channel; remote shell execution via `subprocess`
- Webcam snapshot capture (`cam snap`) with OpenCV
- PyInstaller packaging + fake Instagram promotion simulating social-engineering distribution

**Repo:** [memory-game-security-project](https://github.com/AseelHerzallah1/memory-game-security-project)

---

### 🔦 SPL — System Programming Projects

Three systems-focused projects in **Java** and **C++**:

- **TFTP Server/Client:** Binary protocol over TCP, thread-per-client architecture, concurrent file upload/download with server-wide notifications
- **Set Card Game:** Multithreaded game engine with thread-safe state management and synchronization primitives
- **Warehouse Management System:** OOP design in C++ with strict Rule-of-5 memory management and zero leaks

---

### 🤖 AI & Automation

- **[MatchFlow](https://github.com/AseelHerzallah1/MatchFlow)** — Personal job-search pipeline: RSS + Telegram intake, AI scoring vs CV, Notion CRM, cover letters at strong matches (n8n, FastAPI, OpenAI)
- **[streamlit-genai-chatbot](https://github.com/AseelHerzallah1/streamlit-genai-chatbot)** — Browser chatbot with conversation memory (Streamlit, LangChain, Groq / Llama 3.3)
- **[Camera-Pose-Estimation-Project](https://github.com/AseelHerzallah1/Camera-Pose-Estimation-Project)** — CNN trained on synthetic 3D-rendered data for camera orientation; 97% validation accuracy

---

## 🧠 Technical Skills

**Languages**
- C, C++, Java
- Python, JavaScript / TypeScript

**Systems & Low-Level**
- xv6 kernel — system calls, process management, scheduling, `fork`/`wait` extensions
- Virtual memory — shared mappings, page tables, reference counting
- Synchronization — Peterson locks, tournament tree, sleep/wakeup, race-condition debugging
- Processes, threads, preemption, inter-process communication
- Memory management — heap layout, allocators, Rule-of-5 / RAII (C++)
- Client–server architecture, TCP sockets, binary protocols
- Debugging: GDB, QEMU

**Backend & Infrastructure**
- Node.js, Express, MongoDB / Mongoose
- REST APIs, JWT auth, bcrypt, middleware
- TCP/IP, socket programming, encrypted C2 channels
- Cloudinary media upload, OpenAI API integration
- Production deploy: Vercel, Render
- Java multithreading, thread-per-client server models

**Tools**
- Linux, Git, Make
- QEMU / GDB
- Vite, TanStack Query, Tailwind CSS
- Postman, PyInstaller

---

## 🎯 What I'm Looking For

A role where I can build real software end-to-end — **full-stack product development**, **systems programming**, or **security-focused engineering**. Ideally somewhere that values both shipping polished applications and understanding how things work under the hood.

---

## 🤝 Let's Connect

- 📧 **Email:** herzalla001@gmail.com
- 🐙 **GitHub:** [AseelHerzallah1](https://github.com/AseelHerzallah1)
- 🐦 **Live project:** [twitter-clone-mu-gilt.vercel.app](https://twitter-clone-mu-gilt.vercel.app)
