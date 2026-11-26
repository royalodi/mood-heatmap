# Mood Heatmap Journal

> Daily Emotional Wellness Tracker, Matrix Heatmap & Analytics

![Analytics](https://img.shields.io/badge/Health_Tech-Mood_Analytics-10b981?style=flat-square) ![Heatmap](https://img.shields.io/badge/Visualization-365_Day_Matrix-34d399?style=flat-square) ![Storage](https://img.shields.io/badge/Privacy-100%25_Client_Side-blue?style=flat-square) ![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

![Mood Heatmap Journal Official Banner](assets/banner.svg)

## 📌 Executive Overview
A privacy-first emotional wellness analytics journal featuring an interactive GitHub-style annual commit heatmap, multi-dimensional mood vector calculation, and rolling trend statistics.

---

## 🏛 System Architecture
The following diagram highlights the internal computation pipeline, data transformations, and rendering passes:

![Architecture Diagram](assets/diagram.svg)

---

## 📷 Live Application Interface
Below is an authentic 1080p high-resolution capture of the live running interface:

![Live Interface](assets/screenshot.png)

---

## 🔬 Technical Deep-Dive
### Core Technical Specifications
- **Calendar Heatmap Engine:** Renders full 52-week, 365-day SVG commit-style grid with 5 distinct chromatic intensity brackets.
- **Multidimensional Scoring:** Captures valence, energy, sleep duration, and activity tags to construct a unified emotional index.
- **Local Persistence:** Encodes entries locally in the client browser with full offline reliability and zero external tracking.
- **Statistical Export:** Offers JSON backup and CSV structured data export with automated date indexing.

---

## 🚀 Quick Start Guide

### Zero-Dependency Launch
This project is built as a self-contained, high-performance HTML5 application with zero runtime dependencies.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/royalodi/mood-heatmap.git
   cd mood-heatmap
   ```

2. **Launch directly in any modern browser:**
   ```bash
   # Windows (PowerShell)
   Start-Process index.html

   # macOS / Linux
   open index.html || xdg-open index.html
   ```

---

## 📄 License
This project is distributed under the **MIT License**.


---

## 👨‍💻 Author & Lead Maintainer

<table>
  <tr>
    <td align="center" width="150" valign="middle">
      <a href="https://github.com/royalodi">
        <img src="https://github.com/royalodi.png" width="105" height="105" style="border-radius: 50%;" alt="royalodi" />
      </a>
      <br /><br />
      <b>Royal Odi</b><br />
      <sub><i>Full-Stack Engineer</i></sub>
    </td>
    <td valign="top">
      <p>
        Designed, engineered, and maintained by <b>Royal Odi</b>. Full-Stack Engineer focused on building scalable web architectures, robust backend systems, and responsive, high-performance digital experiences.
      </p>
      <p>
        <a href="https://github.com/royalodi"><img src="https://img.shields.io/badge/GitHub-royalodi-181717?style=flat-square&amp;logo=github&amp;logoColor=white" alt="GitHub Profile" /></a>
        <a href="mailto:royalodi.dev@gmail.com"><img src="https://img.shields.io/badge/Email-royalodi.dev%40gmail.com-EA4335?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Contact Email" /></a>
        <a href="https://github.com/royalodi?tab=repositories"><img src="https://img.shields.io/badge/Portfolio-Featured_Repositories-10b981?style=flat-square&amp;logo=codeforces&amp;logoColor=white" alt="Portfolio" /></a>
      </p>
    </td>
  </tr>
</table>

