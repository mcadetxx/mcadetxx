<!--
FINAL README — Black + Purple Aesthetic (fully GitHub-compatible)

How to use (keep these comments at the top so future-you remembers):
1) Create an `assets/` folder in your repo and add:
   - header_gradient.gif            (animated gradient banner, 1200×260 recommended)
   - header_gradient_static.png     (fallback static banner)
   - dueto_platform_arch.svg        (mini architecture)
   - pulsepredict_arch.svg          (mini architecture)
   - finance_lab_arch.svg           (mini architecture)
   - dueTo_logo.svg                 (your logo, optional)

2) Replace repo links if yours differ.

Why this works:
- GitHub often sanitizes inline <svg>/<style>. We link images instead (SVG/PNG/GIF), so
  diagrams and animation render reliably without being turned into code blocks.
-->

<!-- ========================= HERO / ANIMATED BANNER ========================= -->
<p align="center">
  <picture>
    <!-- Prefer animated gradient GIF; fall back to static PNG -->
    <source srcset="./assets/header_gradient.gif" type="image/gif">
    <img src="./assets/header_gradient_static.png" alt="Marckenrold Cadet — Software Engineer · Data & AI Product Builder" width="100%">
  </picture>
</p>

<!-- tiny brand row (optional logo badge) -->
<p align="center">
  <img alt="DueTo Analytics" src="https://img.shields.io/badge/DueTo%20Analytics-Brand-7C3AED?style=for-the-badge&labelColor=000000&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48Y2lyY2xlIGN4PSI5IiBjeT0iMTIiIHI9IjQiIGZpbGw9IiNmZmYiLz48cmVjdCB4PSIxMyIgeT0iNyIgd2lkdGg9IjQiIGhlaWdodD0iMTAiIGZpbGw9IiNmZmYiIHJ4PSIyIi8+PC9zdmc+&color=7C3AED">
</p>

<!-- ================================ INTRO ================================== -->
<h1 align="center" style="margin-top:-8px;color:#ffffff;">Marckenrold “Marck” Cadet</h1>
<h3 align="center" style="color:#A78BFA;">Software Engineer · Data & AI Product Builder</h3>

<div align="center">
  <a href="https://duetoanalytics.com"><img alt="Website" src="https://img.shields.io/badge/Website-duetoanalytics.com-7C3AED?style=flat&labelColor=000000"></a>
  <a href="https://linkedin.com/in/marckenrold"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-marckenrold-7C3AED?style=flat&labelColor=000000&logo=linkedin&logoColor=white"></a>
  <a href="mailto:info@duetoanalytics.com"><img alt="Email" src="https://img.shields.io/badge/Email-info@duetoanalytics.com-7C3AED?style=flat&labelColor=000000&logo=gmail&logoColor=white"></a>
</div>

<p align="center" style="color:#cfcfe7;">
  I turn data into direction — clean APIs, useful dashboards, and clear decisions.<br/>
  Finance + ops fluency, strong documentation, and product polish.
</p>

---

<!-- ================================ SKILLS ================================= -->
### Skills
<p>
  <img src="https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white&color=7C3AED"/>
  <img src="https://img.shields.io/badge/SQL-000000?style=for-the-badge&logo=postgresql&logoColor=white&color=7C3AED"/>
  <img src="https://img.shields.io/badge/FastAPI-000000?style=for-the-badge&logo=fastapi&logoColor=white&color=7C3AED"/>
  <img src="https://img.shields.io/badge/React-000000?style=for-the-badge&logo=react&logoColor=white&color=7C3AED"/>
  <img src="https://img.shields.io/badge/Power%20BI-000000?style=for-the-badge&logo=powerbi&logoColor=white&color=7C3AED"/>
  <img src="https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=white&color=7C3AED"/>
  <img src="https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=white&color=7C3AED"/>
</p>

---

<!-- ============================== FEATURED GRID ============================ -->
## Featured

<!-- Row 1 -->
<table width="100%">
  <tr>
    <td width="45%" valign="top">

      <!-- Card: dueTo (logo + blurb) -->
      <div style="background:#0b0b12;border:1px solid #2a2340;border-radius:14px;padding:18px;">
        <h3 style="color:#A78BFA;margin:0 0 8px 0;">due<span style="color:#FFFFFF;">To</span></h3>
        <p style="color:#c8c8d8;margin:8px 0 14px 0;">Task & data management system utilizing modular services.</p>
        <img src="./assets/dueto_platform_arch.svg" alt="DueTo Platform Architecture">
        <p style="margin:10px 0 0 0;">
          <a href="https://github.com/xmcadetxx/dueto-platform" style="color:#A78BFA;">Repo →</a>
        </p>
      </div>
    </td>

    <td width="55%" valign="top">

      <!-- Card: DueTo Platform details -->
      <div style="background:#0b0b12;border:1px solid #2a2340;border-radius:14px;padding:18px;">
        <h3 style="color:#ffffff;margin:0 0 8px 0;">DueTo Platform</h3>
        <p style="color:#c8c8d8;margin:0 0 8px 0;">A task/analytics platform with microservices & real-time pipelines.</p>
        <ul style="color:#c8c8d8;margin:0 0 8px 18px;">
          <li>Frontend (React) → API (FastAPI) → <strong>Kafka</strong> → <strong>Airflow</strong> → Postgres</li>
          <li>Endpoints: <code>/sources</code> · <code>/models</code> · <code>/simulate</code> · <code>/experiments</code></li>
        </ul>
        <a href="https://github.com/xmcadetxx/dueto-platform" style="color:#A78BFA;">Open repo →</a>
      </div>
    </td>
  </tr>
</table>

<br/>

<!-- Row 2 -->
<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <!-- Card: PulsePredict -->
      <div style="background:#0b0b12;border:1px solid #2a2340;border-radius:14px;padding:18px;">
        <h3 style="color:#A78BFA;margin:0 0 8px 0;">PulsePredict</h3>
        <p style="color:#c8c8d8;margin:0 0 12px 0;">Churn & revenue risk signals with next-best-action.</p>
        <img src="./assets/pulsepredict_arch.svg" alt="PulsePredict Architecture">
        <p style="margin:10px 0 0 0;">
          <a href="https://github.com/xmcadetxx/pulsepredict" style="color:#A78BFA;">Repo →</a>
        </p>
      </div>
    </td>

    <td width="50%" valign="top">
      <!-- Card: Finance Lab -->
      <div style="background:#0b0b12;border:1px solid #2a2340;border-radius:14px;padding:18px;">
        <h3 style="color:#ffffff;margin:0 0 8px 0;">Finance Lab</h3>
        <p style="color:#c8c8d8;margin:0 0 12px 0;">Reusable notebooks: Black-Scholes, Greeks, IRR/NPV, Duration/Convexity.</p>
        <img src="./assets/finance_lab_arch.svg" alt="Finance Lab Architecture">
        <p style="margin:10px 0 0 0;">
          <a href="https://github.com/xmcadetxx/finance-lab" style="color:#A78BFA;">Repo →</a>
        </p>
      </div>
    </td>
  </tr>
</table>

---

<!-- ============================== STATS & LINKS ============================ -->
### Stats & Links
<p>
  <img src="https://github-readme-stats.vercel.app/api?username=xmcadetxx&show_icons=true&hide_border=true&title_color=A78BFA&text_color=E5E7EB&icon_color=7C3AED&bg_color=000000" height="145" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=xmcadetxx&hide_border=true&ring=7C3AED&fire=A78BFA&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=A78BFA&sideLabels=9CA3AF&dates=6B7280&background=000000" height="145" />
</p>

<p>
  <a href="https://duetoanalytics.com">
    <img alt="Website" src="https://img.shields.io/badge/Website-duetoanalytics.com-7C3AED?style=for-the-badge&labelColor=000000&logo=google-chrome&logoColor=white">
  </a>
  <a href="https://linkedin.com/in/marckenrold">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-marckenrold-7C3AED?style=for-the-badge&labelColor=000000&logo=linkedin&logoColor=white">
  </a>
  <a href="mailto:info@duetoanalytics.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-info@duetoanalytics.com-7C3AED?style=for-the-badge&labelColor=000000&logo=gmail&logoColor=white">
  </a>
</p>

<p align="center" style="color:#9aa0b6;"><em>“Make it measurable. Make it usable. Make it ship.”</em></p>
