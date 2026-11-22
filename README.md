# Anuraag Mahapatra — Personal Portfolio Website

A dark, cyber-inspired, single-file personal portfolio website showcasing my work in **Offensive Cybersecurity**, **CTF Development**, and **Full-Stack Web Development**. Built with zero build-step overhead so it can be previewed locally or deployed straight to GitHub Pages in seconds.

## ✨ Key Features

* **Interactive Hero Terminal Card:** Features a styled Bash profile card (`anuraag@outr:~`) with clickable quick commands (`./whoami`, `./ctf_stats`, `./contact`) and a live internship availability status badge.

* **Filterable Project Showcase:** Interactive category tabs (**All**, **Cybersecurity**, **Web Dev**) that dynamically filter projects with smooth card transitions and direct GitHub links.

* **Experience & Leadership Timeline:** Highlights my roles across **HackCTF (HackFest 2026)**, **Energy Club (OUTR)**, **UptoSkills**, and **InAmigos Foundation**, along with offensive security lab milestones.

* **Technical Arsenal:** Organized breakdown of Offensive Security & Pentesting tools, Full-Stack Web & Scripting technologies, and Design/Hardware skills.

* **Contact & Social Hub:** Includes a one-click **Copy Email** button with toast notification feedback, direct GitHub/LinkedIn cards, and a client-side validated contact form that opens a pre-filled `mailto:` draft.

* **Responsive & Lightweight:** Mobile-friendly navigation drawer, scroll-spy active section highlighting via `IntersectionObserver`, and a glassmorphic dark UI styled with Tailwind CSS.

## 🛠️ Tech Stack

* **Markup & Structure:** Semantic HTML5

* **Styling:** Tailwind CSS (CDN), Custom CSS3 (glassmorphism, cyber grid texture, ambient glows)

* **Interactivity:** Vanilla JavaScript (ES6+)

* **Typography:** [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [Inter](https://fonts.google.com/specimen/Inter), and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)

## 📂 Featured Projects Included

| Project | Domain | Highlights | 
| ----- | ----- | ----- | 
| **HackCTF Platform & 60 Challenges** | Cybersecurity · Web Dev | Offline Jeopardy-style CTF arena with a browser-based Linux sandbox, live scoreboard, and 60 challenges (7,100 pts) | 
| **SQL-heist / Project-NEON** | Cybersecurity · Web Dev | Multi-stage SQL injection reactor control sandbox bridged with an Arduino UNO | 
| **NEXUS.SEC** | Web Dev · Cybersecurity | Full-stack MERN application simulating vulnerability assessment and pentesting workflows | 
| **DIY_Dirbuster** | Cybersecurity | Custom Python CLI directory brute-forcing and web enumeration tool | 
| **OWASP Juice Shop Pentest Report** | Cybersecurity | Structured web application pentest report with exploitation paths and remediations | 
| **InAmigos Foundation Web & UX Audit** | Web Dev | Responsive NGO awareness webpages, AI web prototype, and Figma UX improvement audit | 

## 🚀 Getting Started

### Run Locally

Since the portfolio is self-contained in a single HTML file, no package installation or build tools are required:

1. Clone this repository:

   ```bash
   git clone https://github.com/Anuraag-Mahapatra/<your-repo-name>.git
   cd <your-repo-name>
   ```

2. Open `index.html` (or `anuraag_portfolio.html`) directly in your browser, or run a lightweight local server:

   ```bash
   python3 -m http.server 8000
   ```

   Then visit `http://localhost:8000`.

### Deploy to GitHub Pages

1. Rename `anuraag_portfolio.html` to `index.html` in the root of your repository.

2. Push your files (`index.html` and `README.md`) to your GitHub repository.

3. Go to **Settings → Pages** in your repository.

4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.

5. Your live portfolio will be available at `https://anuraag-mahapatra.github.io/<your-repo-name>/`.

## 🔧 Customization

* **Update Projects:** Edit the `PROJECTS` array inside the `<script>` tag to add new projects, adjust tech stack tags, or link specific GitHub repositories.

* **Update Terminal Commands:** Modify the `termCmdResponses` object to customize the outputs of `./whoami`, `./ctf_stats`, and `./contact`.

* **Update Theme Colors:** Adjust the Tailwind color tokens (`obsidian`, `navy`, `cyberCyan`, `cyberEmerald`) in the inline `tailwind.config` block inside `<head>`.

## 📬 Connect With Me

* **Email:** [a.mahapatra3000@gmail.com](mailto:a.mahapatra3000@gmail.com)

* **GitHub:** [github.com/Anuraag-Mahapatra](https://github.com/Anuraag-Mahapatra)

* **LinkedIn:** [linkedin.com/in/anuraag-mahapatra-1033b933b](https://www.linkedin.com/in/anuraag-mahapatra-1033b933b)

* **Location:** Bhubaneswar, Odisha, India

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).