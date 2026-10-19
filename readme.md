# DataCraft 

A mobile-first data visualization and charting application designed with Google's Material 3 design principles. **DataCraft** allows users to explore preloaded datasets, edit data directly via a spreadsheet interface, parse raw CSV inputs, dynamically map X/Y axes, and generate interactive charts with instant export capabilities.

Built as an offline-first **Progressive Web App (PWA)** that can be installed on Android devices directly from the browser or packaged into a native Android APK using **Capacitor**.

---

## ✨ Features

- **Material 3 Mobile Shell**: Native Android look-and-feel featuring a simulated status bar, pill bottom navigation, and fluid card layouts.
- **Multiple Visualizations**: Real-time rendering of Bar, Line, Doughnut, Pie, Radar, and Polar Area charts powered by Chart.js.
- **Dynamic Data Grid**:
  - Live row editing, creation, and deletion.
  - Custom column additions for multi-series datasets.
  - Raw CSV paste and instant parsing.
  - Flexible X (label) and Y (metric) axis binding.
- **Preloaded Datasets**: Ready-to-explore datasets for monthly revenue, fitness commutes, project milestones, and surveys.
- **Smart Analytics**: Automated calculation of metrics including Sum, Mean, Peak Category, and dynamic textual summaries.
- **Export Ready**: One-tap high-resolution PNG chart image export and CSV copy.
- **PWA & Offline Ready**: Service worker caching for fast offline usage and standalone Android installation.

---

##  Tech Stack

- **Core**: Vanilla HTML5, Modern CSS, JavaScript (ES6+)
- **Charting**: [Chart.js](https://www.chartjs.org/)
- **Mobile Packaging**: Progressive Web App (PWA) / [@capacitor/android](https://capacitorjs.com/)

---

##  Getting Started

### 1. Run Locally

Clone the repository and serve the files using any lightweight static server:

```bash
# Clone the repository
git clone [https://github.com/](https://github.com/)BhumikaB1/datacraft.git
cd datacraft

# Serve using npx (no install required)
npx serve .