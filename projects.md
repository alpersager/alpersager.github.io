---
title: "Projects — Alper Sager"
---

# Projects

Below are selected projects with short descriptions and tech stack.

<div markdown="0" class="projects-grid" style="display:grid; grid-template-columns:repeat(auto-fit,minmax(280px,1fr)); gap:16px; margin-top:12px;">

  <!-- OTHELLO -->
  <div>
    <a href="https://github.com/alpersager/othello-cpp" style="text-decoration:none; color:inherit; display:block;">
      <div class="project-card" style="border:1px solid #e5e7eb; border-radius:14px; padding:16px;">
        <div style="font-weight:600; margin-bottom:6px;">Othello in C++ (TDD)</div>
        <div style="opacity:.8; font-size:.95rem;">
          Game logic, move validation, and unit tests (<code>test.cpp</code>).
        </div>
        <div style="margin-top:8px; font-size:.9rem; display:flex; align-items:center; gap:8px;">
          <span>⚙️ C++ • STL • Unit Testing</span>
          <img src="https://github.com/alpersager/othello-cpp/actions/workflows/cpp.yml/badge.svg" alt="Build Status" style="height:18px;">
        </div>
      </div>
    </a>
  </div>

  <!-- AVR8 ASSEMBLY LABS -->
  <div>
    <a href="https://github.com/alpersager/avr-assembly-labs" style="text-decoration:none; color:inherit; display:block;">
      <div class="project-card" style="border:1px solid #e5e7eb; border-radius:14px; padding:16px;">
        <div style="font-weight:600; margin-bottom:6px;">AVR8 Assembly Labs</div>
        <div style="opacity:.8; font-size:.95rem;">Interrupts, timers, low-level I/O — clean commented ASM.</div>
        <div style="margin-top:8px; font-size:.9rem;">🧠 AVR • Assembly • Embedded</div>
      </div>
    </a>
  </div>

  <!-- MINI DATABASE -->
  <div>
    <a href="https://github.com/alpersager/mini-db-cpp" style="text-decoration:none; color:inherit; display:block;">
      <div class="project-card" style="border:1px solid #e5e7eb; border-radius:14px; padding:16px;">
        <div style="font-weight:600; margin-bottom:6px;">Mini Database (C++)</div>
        <div style="opacity:.8; font-size:.95rem;">In-memory store, simple indexing & query engine.</div>
        <div style="margin-top:8px; font-size:.9rem;">🗃️ C++ • Data Structures</div>
      </div>
    </a>
  </div>

</div>

---

## Coursework mini-demos (optional)
- OS Scheduling demos (Round Robin etc.)
- FFT & filtering notebooks
- AVR timer & interrupt examples

---

<!-- FOOTER + STYLES -->
<hr style="margin-top:48px;">
<footer style="text-align:center; font-size:0.9rem; opacity:.8; margin:32px 0;">
  © 2025 <strong>Alper Sager</strong> · RWTH Aachen University<br>
  <a href="mailto:alper.sager@rwth-aachen.de">alper.sager@rwth-aachen.de</a> ·
  <a href="https://www.linkedin.com/in/alpersager">LinkedIn</a> ·
  <a href="https://github.com/alpersager">GitHub</a>
</footer>

<style>
  /* tipografi ufak rötuş */
  body { font-family:"Segoe UI","Helvetica Neue",sans-serif; }
  h1, h2, h3 { letter-spacing:.2px; }
  h1 { color:#003366; }
  h2 { color:#004b8d; border-bottom:2px solid #e5e7eb; padding-bottom:4px; }
  a { color:#0056b3; } a:hover { text-decoration:underline; opacity:.92; }
  code { background:#f6f8fa; padding:2px 6px; border-radius:6px; }
  hr { border:none; border-top:1px solid #e5e7eb; }

  /* kart animasyonu + erişilebilir focus */
  .project-card {
    transition: transform .14s ease, box-shadow .14s ease, border-color .14s ease;
    box-shadow: 0 0 0 rgba(0,0,0,0);
  }
  a:focus .project-card,
  a:focus-visible .project-card,
  .project-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 28px rgba(0,0,0,.08);
    border-color: #d1d5db;
  }
  /* hareket hassasiyeti olan kullanıcılar */
  @media (prefers-reduced-motion: reduce) {
    .project-card { transition: none; }
  }

  /* mobil: tek sütun */
  @media (max-width: 640px) {
    .projects-grid { grid-template-columns: 1fr !important; }
  }
</style>
