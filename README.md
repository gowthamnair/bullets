# Bullets: Professional Productivity Suite

**Bullets** is a minimalist, high-performance web-based productivity application designed for rapid note-taking, structured documentation, and task management. It utilizes a glassmorphic interface with a focus on clinical efficiency and zero-distraction workflows.

---

## Core Features

### 1. Multi-Mode Workspace
The application operates in three distinct modes tailored to specific cognitive tasks:
* **Quick Mode:** A dedicated scratchpad for ephemeral thoughts. It features a persistent "Clear" trigger for rapid data purging.
* **Standard Mode:** A full-featured document editor with folder-based organization for long-term records.
* **To-Do Mode:** A calendar-centric task manager with automated progress tracking and statistical visualization.

### 2. Advanced Editor Capabilities
* **Dynamic List Management:** Specialized handling for nested bullet points with intelligent `Tab` and `Backspace` indentation logic.
* **Contextual Commenting System:** Highlight any text to attach meta-notes or annotations without cluttering the primary document body.
* **Rich Text Support:** Native browser execution of formatting commands (Lists, Indentation) via a floating glass toolbar.

### 3. Comprehensive Task Engine
* **Interactive Calendar:** Visual grid mapping of daily agendas with "All-Done" status indicators for completed days.
* **Performance Metrics:** Real-time calculation of completion percentages and task ratios (Done vs. To-Do) across Daily, Monthly, and Yearly views.
* **Agenda Portability:** Tools to copy agendas to the clipboard or export them as plain text/image files.

### 4. System & Aesthetics
* **Theme Engine:** Four distinct visual profiles:
    * **Midnight:** High-contrast dark mode.
    * **Snow:** Clean, professional light mode.
    * **Forest & Ocean:** Specialized low-strain tinted environments.
* **Responsive Architecture:** Fully adaptive UI that transitions between a sidebar-driven desktop experience and a bottom-bar-centric mobile interface.
* **Local-First Storage:** All data is persisted in `localStorage`, ensuring privacy and offline availability without external database dependencies.

### 5. Export & Integration
* **Visual Export:** High-resolution PNG generation of documents and calendars via `html2canvas`.
* **Outlook Integration:** Native `.eml` file generation for direct injection of notes into corporate email clients.
* **Clipboard Sync:** One-click formatting for clean text transfers to other platforms.

---

## Technical Specifications

| Component | Implementation |
| :--- | :--- |
| **Language** | HTML5, CSS3, JavaScript (ES6+) |
| **Styling** | CSS Variables, Flexbox, CSS Grid, Backdrop Filters |
| **Dependencies** | Google Fonts (Inter, Roboto, Fira Code), html2canvas |
| **Data Persistence** | JSON-serialized `localStorage` |
| **Security** | Local client-side execution; no external data transmission |

---

## Installation
The provided Python script generates the `index.html` file locally.
1. Run `python generate_site.py`.
2. Open `index.html` in any modern web browser (Chrome, Safari, Edge).
