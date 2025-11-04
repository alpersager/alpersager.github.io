---
title: "Projects — Alper Sager"
---

# Projects

Below are selected projects with short descriptions and tech stack.

<div style="display:grid; grid-template-columns:repeat(auto-fit,minmax(280px,1fr)); gap:16px; margin-top:12px;">

<a href="https://github.com/alpersager/othello-cpp" style="text-decoration:none; color:inherit;">
  <div style="border:1px solid #e5e7eb; border-radius:14px; padding:16px; transition:transform .12s, box-shadow .12s;">
    <div style="font-weight:600; margin-bottom:6px;">Othello in C++ (TDD)</div>
    <div style="opacity:.8; font-size:.95rem;">
      Game logic, move validation, and unit tests (<code>test.cpp</code>).
    </div>

    <!-- tech stack + badge aynı satırda -->
    <div style="margin-top:8px; font-size:.9rem; display:flex; align-items:center; gap:8px;">
      <span>⚙️ C++ • STL • Unit Testing</span>
      <img src="https://github.com/alpersager/othello-cpp/actions/workflows/cpp.yml/badge.svg"
           alt="Build Status" style="height:18px;">
    </div>
  </div>
</a>



  <a href="https://github.com/alpersager/avr-assembly-labs" style="text-decoration:none; color:inherit;">
    <div style="border:1px solid #e5e7eb; border-radius:14px; padding:16px; transition:transform .12s, box-shadow .12s;">
      <div style="font-weight:600; margin-bottom:6px;">AVR8 Assembly Labs</div>
      <div style="opacity:.8; font-size:.95rem;">Interrupts, timers, low-level I/O — clean commented ASM.</div>
      <div style="margin-top:8px; font-size:.9rem;">🧠 AVR • Assembly • Embedded</div>
    </div>
  </a>

  <a href="https://github.com/alpersager/mini-db-cpp" style="text-decoration:none; color:inherit;">
    <div style="border:1px solid #e5e7eb; border-radius:14px; padding:16px; transition:transform .12s, box-shadow .12s;">
      <div style="font-weight:600; margin-bottom:6px;">Mini Database (C++)</div>
      <div style="opacity:.8; font-size:.95rem;">In-memory store, simple indexing & query engine.</div>
      <div style="margin-top:8px; font-size:.9rem;">🗃️ C++ • Data Structures</div>
    </div>
  </a>

</div>

<script>
  document.querySelectorAll('div[style*="border-radius:14px"]').forEach(card=>{
    card.addEventListener('mouseenter', ()=>{ card.style.transform='translateY(-2px)'; card.style.boxShadow='0 8px 24px rgba(0,0,0,.08)'; });
    card.addEventListener('mouseleave', ()=>{ card.style.transform=''; card.style.boxShadow=''; });
  });
</script>

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
  body { font-family:"Segoe UI","Helvetica Neue",sans-serif; }
  h1, h2, h3 { letter-spacing:.2px; }
  h1 { color:#003366; }
  h2 { color:#004b8d; border-bottom:2px solid #e5e7eb; padding-bottom:4px; }
  a { color:#0056b3; } a:hover { text-decoration:underline; opacity:.92; }
  code { background:#f6f8fa; padding:2px 6px; border-radius:6px; }
  hr { border:none; border-top:1px solid #e5e7eb; }
</style>

