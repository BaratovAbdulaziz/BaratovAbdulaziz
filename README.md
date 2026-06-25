<p align="center">
  <img src="header.svg" alt="banner" width="100%" />
</p>

Front-end to back-end, concept to deployment. Python, TypeScript, and React — with PostgreSQL on the backend.

<p align="center">
  <img src="https://img.shields.io/badge/-Samarkand,%20Uzbekistan-181818?style=flat-square" />
  <img src="https://img.shields.io/badge/-Open%20for%20work-181818?style=flat-square" />
</p>

<br>

## Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-181818?style=flat-square&logo=python&logoColor=DA291C" />
  <img src="https://img.shields.io/badge/TypeScript-181818?style=flat-square&logo=typescript&logoColor=DA291C" />
  <img src="https://img.shields.io/badge/JavaScript-181818?style=flat-square&logo=javascript&logoColor=DA291C" />
  <img src="https://img.shields.io/badge/React-181818?style=flat-square&logo=react&logoColor=DA291C" />
  <img src="https://img.shields.io/badge/Node.js-181818?style=flat-square&logo=nodedotjs&logoColor=DA291C" />
  <img src="https://img.shields.io/badge/Tailwind-181818?style=flat-square&logo=tailwindcss&logoColor=DA291C" />
  <img src="https://img.shields.io/badge/Supabase-181818?style=flat-square&logo=supabase&logoColor=DA291C" />
  <img src="https://img.shields.io/badge/PostgreSQL-181818?style=flat-square&logo=postgresql&logoColor=DA291C" />
  <img src="https://img.shields.io/badge/Docker-181818?style=flat-square&logo=docker&logoColor=DA291C" />
  <img src="https://img.shields.io/badge/Figma-181818?style=flat-square&logo=figma&logoColor=DA291C" />
  <img src="https://img.shields.io/badge/Vite-181818?style=flat-square&logo=vite&logoColor=DA291C" />
  <img src="https://img.shields.io/badge/Git-181818?style=flat-square&logo=git&logoColor=DA291C" />
</p>

<br>

<style>
.project-stack {
  display: grid;
  grid-template-areas: "stack";
  max-width: 680px;
  margin: 2rem auto;
  perspective: 1200px;
}
.project-stack > div {
  grid-area: stack;
  border: 1px solid #252525;
  border-radius: 16px;
  padding: 24px 28px;
  background: #0d1117;
  transition: all 0.5s cubic-bezier(0.23, 1, 0.32, 1);
  position: relative;
  backface-visibility: hidden;
  box-shadow: 0 0 0 0 transparent;
}
.project-stack:hover > div {
  opacity: 0.25;
  filter: grayscale(0.8);
  transition: all 0.5s cubic-bezier(0.23, 1, 0.32, 1);
}
.project-stack:hover > div:hover {
  opacity: 1;
  filter: grayscale(0);
}
.project-stack > div::after {
  content: '';
  position: absolute;
  inset: -1px;
  border-radius: 16px;
  opacity: 0;
  transition: opacity 0.5s ease;
  pointer-events: none;
  z-index: -1;
}
.project-stack > div:hover {
  box-shadow: 0 0 32px -8px var(--glow), inset 0 0 40px -20px var(--glow);
}
.project-stack > div:hover::after {
  opacity: 1;
}
.project-stack h3 {
  margin: 0 0 4px;
  color: #e6edf3;
  font-size: 20px;
  transition: color 0.3s ease;
}
.project-stack > div:hover h3 {
  color: var(--accent);
}
.project-stack .tag {
  color: #555;
  font-size: 11px;
  letter-spacing: 2px;
  text-transform: uppercase;
  margin-bottom: 10px;
}
.project-stack p {
  margin: 0 0 14px;
  color: #8b949e;
  font-size: 14px;
  line-height: 1.6;
}
.project-stack .links {
  margin: 0;
}
.project-stack .links img {
  margin-right: 4px;
}
.project-stack .card-red {
  --accent: #DA291C;
  --glow: rgba(218, 41, 28, 0.3);
  border-color: rgba(218, 41, 28, 0.15);
}
.project-stack .card-red:hover { border-color: #DA291C; }
.project-stack .card-red::after {
  background: linear-gradient(135deg, transparent 30%, rgba(218, 41, 28, 0.12), transparent 70%);
}
.project-stack .card-purple {
  --accent: #A855F7;
  --glow: rgba(168, 85, 247, 0.3);
  border-color: rgba(168, 85, 247, 0.15);
}
.project-stack .card-purple:hover { border-color: #A855F7; }
.project-stack .card-purple::after {
  background: linear-gradient(135deg, transparent 30%, rgba(168, 85, 247, 0.12), transparent 70%);
}
.project-stack .card-blue {
  --accent: #3B82F6;
  --glow: rgba(59, 130, 246, 0.3);
  border-color: rgba(59, 130, 246, 0.15);
}
.project-stack .card-blue:hover { border-color: #3B82F6; }
.project-stack .card-blue::after {
  background: linear-gradient(135deg, transparent 30%, rgba(59, 130, 246, 0.12), transparent 70%);
}
.project-stack .card-teal {
  --accent: #14B8A6;
  --glow: rgba(20, 184, 166, 0.3);
  border-color: rgba(20, 184, 166, 0.15);
}
.project-stack .card-teal:hover { border-color: #14B8A6; }
.project-stack .card-teal::after {
  background: linear-gradient(135deg, transparent 30%, rgba(20, 184, 166, 0.12), transparent 70%);
}

.social-buttons {
  display: flex;
  justify-content: center;
  gap: 24px;
  margin: 1.5rem 0;
}
.social-btn {
  display: inline-flex;
  align-items: center;
  gap: 12px;
  padding: 14px 32px 14px 24px;
  border-radius: 40px;
  border: 1.5px solid #2a2a2a;
  background: #0d1117;
  color: #e6edf3;
  font-size: 14px;
  font-family: inherit;
  text-decoration: none;
  transition: all 0.35s cubic-bezier(0.23, 1, 0.32, 1);
  cursor: pointer;
  position: relative;
  box-shadow: inset 0 1px 0 rgba(255,255,255,0.04);
}
.social-btn .icon-wrap {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 36px;
  height: 36px;
  border-radius: 50%;
  flex-shrink: 0;
  transition: all 0.35s ease;
}
.social-btn svg {
  width: 18px;
  height: 18px;
  transition: transform 0.35s ease;
}
.social-btn:hover svg {
  transform: scale(1.15);
}
.social-btn:hover {
  transform: translateY(-2px);
}
.social-btn.gmail {
  border-color: rgba(218, 41, 28, 0.25);
}
.social-btn.gmail .icon-wrap {
  background: rgba(218, 41, 28, 0.1);
}
.social-btn.gmail:hover {
  border-color: #DA291C;
  background: linear-gradient(135deg, #0d1117, #1a0c0a);
  box-shadow: 0 8px 28px -8px rgba(218, 41, 28, 0.35), inset 0 1px 0 rgba(218, 41, 28, 0.1);
  color: #ea4335;
}
.social-btn.gmail:hover .icon-wrap {
  background: rgba(218, 41, 28, 0.2);
}
.social-btn.telegram {
  border-color: rgba(0, 136, 204, 0.25);
}
.social-btn.telegram .icon-wrap {
  background: rgba(0, 136, 204, 0.1);
}
.social-btn.telegram:hover {
  border-color: #0088cc;
  background: linear-gradient(135deg, #0d1117, #0a121c);
  box-shadow: 0 8px 28px -8px rgba(0, 136, 204, 0.35), inset 0 1px 0 rgba(0, 136, 204, 0.1);
  color: #38bdf8;
}
.social-btn.telegram:hover .icon-wrap {
  background: rgba(0, 136, 204, 0.2);
}
</style>

## Projects

<div class="project-stack">

<div class="card-red" style="transform: perspective(1000px) rotateX(3deg) rotateY(-2deg) translate(0px, 0px); z-index: 4;">
  <h3>split-evenly</h3>
  <div class="tag">Full-stack · Finance</div>
  <p>Full-stack expense splitting app — React + TypeScript front-end with Supabase backend and Tailwind CSS.</p>
  <p class="links">
    <img src="https://img.shields.io/badge/React-181818?style=flat-square&logo=react&logoColor=DA291C" />
    <img src="https://img.shields.io/badge/TypeScript-181818?style=flat-square&logo=typescript&logoColor=DA291C" />
    <img src="https://img.shields.io/badge/Supabase-181818?style=flat-square&logo=supabase&logoColor=DA291C" />
    <img src="https://img.shields.io/badge/Tailwind-181818?style=flat-square&logo=tailwindcss&logoColor=DA291C" />
    <a href="https://github.com/BaratovAbdulaziz/split-evenly"><img src="https://img.shields.io/badge/View-181818?style=flat-square&logo=github&logoColor=DA291C" /></a>
  </p>
</div>

<div class="card-purple" style="transform: perspective(1000px) rotateX(6deg) rotateY(2deg) translate(10px, 12px); z-index: 3;">
  <h3>ridges</h3>
  <div class="tag">AI · Developer Tools</div>
  <p>AI coding agent powered by OpenRouter. Bug localization, patch generation, and git-aware code repair using LLM model cascading.</p>
  <p class="links">
    <img src="https://img.shields.io/badge/Python-181818?style=flat-square&logo=python&logoColor=DA291C" />
    <img src="https://img.shields.io/badge/OpenRouter-181818?style=flat-square&logo=openai&logoColor=DA291C" />
    <a href="https://github.com/BaratovAbdulaziz/ridges"><img src="https://img.shields.io/badge/View-181818?style=flat-square&logo=github&logoColor=DA291C" /></a>
  </p>
</div>

<div class="card-blue" style="transform: perspective(1000px) rotateX(9deg) rotateY(-3deg) translate(20px, 24px); z-index: 2;">
  <h3>no-borders</h3>
  <div class="tag">Networking · KVM</div>
  <p>Cross-platform KVM switch — control multiple computers with one keyboard and mouse over TCP/UDP with auto-discovery.</p>
  <p class="links">
    <img src="https://img.shields.io/badge/Python-181818?style=flat-square&logo=python&logoColor=DA291C" />
    <a href="https://github.com/BaratovAbdulaziz/no-borders"><img src="https://img.shields.io/badge/View-181818?style=flat-square&logo=github&logoColor=DA291C" /></a>
  </p>
</div>

<div class="card-teal" style="transform: perspective(1000px) rotateX(12deg) rotateY(3deg) translate(30px, 36px); z-index: 1;">
  <h3>emotion-link-signaling</h3>
  <div class="tag">WebRTC · Signaling</div>
  <p>WebSocket signaling server for WebRTC peer connections with room management and real-time message relay.</p>
  <p class="links">
    <img src="https://img.shields.io/badge/Node.js-181818?style=flat-square&logo=nodedotjs&logoColor=DA291C" />
    <img src="https://img.shields.io/badge/WebSocket-181818?style=flat-square&logo=socketdotio&logoColor=DA291C" />
    <a href="https://github.com/BaratovAbdulaziz/emotion-link-signaling"><img src="https://img.shields.io/badge/View-181818?style=flat-square&logo=github&logoColor=DA291C" /></a>
  </p>
</div>

</div>

<br>

## Contact

<p align="center">
  <a href="mailto:abdulazizbaratov12@gmail.com" style="display:inline-flex;align-items:center;gap:10px;padding:12px 28px 12px 20px;border-radius:40px;border:1.5px solid rgba(218,41,28,0.3);background:#0d1117;color:#ea4335;font-size:14px;font-family:inherit;text-decoration:none;transition:all .3s ease;box-shadow:inset 0 1px 0 rgba(255,255,255,0.04)">
    <span style="display:flex;align-items:center;justify-content:center;width:36px;height:36px;border-radius:50%;background:rgba(218,41,28,0.1);flex-shrink:0">
      <svg viewBox="0 0 24 24" width="18" height="18" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
        <rect x="2" y="4" width="20" height="16" rx="2"/>
        <path d="M22 4L12 13L2 4"/>
      </svg>
    </span>
    abdulazizbaratov12@gmail.com
  </a>
  <a href="https://t.me/Pathfi1nder" style="display:inline-flex;align-items:center;gap:10px;padding:12px 28px 12px 20px;border-radius:40px;border:1.5px solid rgba(0,136,204,0.25);background:#0d1117;color:#38bdf8;font-size:14px;font-family:inherit;text-decoration:none;transition:all .3s ease;box-shadow:inset 0 1px 0 rgba(255,255,255,0.04)">
    <span style="display:flex;align-items:center;justify-content:center;width:36px;height:36px;border-radius:50%;background:rgba(0,136,204,0.1);flex-shrink:0">
      <svg viewBox="0 0 24 24" width="18" height="18" fill="currentColor">
        <path d="M11.944 0A12 12 0 000 12a12 12 0 0012 12 12 12 0 0012-12A12 12 0 0012 0a12 12 0 00-.056 0zm4.962 7.224c.1-.002.321.023.465.14a.506.506 0 01.171.325c.016.093.036.306.02.472-.18 1.898-.962 6.502-1.36 8.627-.168.9-.499 1.201-.82 1.23-.696.065-1.225-.46-1.9-.902-1.056-.693-1.653-1.124-2.678-1.8-1.185-.78-.417-1.21.258-1.91.177-.184 3.247-2.977 3.307-3.23.007-.032.014-.15-.056-.212s-.174-.041-.249-.024c-.106.024-1.793 1.14-5.061 3.345-.48.33-.913.49-1.302.48-.428-.008-1.252-.241-1.865-.44-.752-.245-1.349-.374-1.297-.789.027-.216.325-.437.893-.663 3.498-1.524 5.83-2.529 6.998-3.014 3.332-1.386 4.025-1.627 4.476-1.635z"/>
      </svg>
    </span>
    @Pathfi1nder
  </a>
</p>

<p align="center">
  <sub>React + TypeScript on the front. Python + Node.js on the back.</sub>
</p>
