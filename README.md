# 🚀 Tech Career & Certification Roadmaps

This project is a single-page, interactive learning tool designed to help users visualize and track progress across various tech career paths and professional certifications.

It is built entirely using **Vanilla JavaScript**, **HTML**, and **Tailwind CSS** (via CDN), meaning it requires absolutely no compilation, build steps, or backend infrastructure.

---

## ✨ Features

* **Dual Roadmaps:** Organized tabs for professional **Career Paths** (e.g., Software Engineer, AI Engineer) and **Certification Paths** (e.g., AWS Solutions Architect).
* **Interactive Progress Tracker:** Users can click to mark sub-goals as complete, which automatically updates a dynamic **progress bar** and roadmap visualization in real-time.
* **Modular Learning:** Each path is broken down into themed modules, providing detailed milestones and links to external learning **resources**.
* **Client-Side State:** All application logic and progress tracking are handled directly in the browser using a simple JavaScript state object, making it fast and lightweight.
* **Search and Filter:** Easily find a specific roadmap using the built-in search functionality.

---

## 🛠️ How to Run Locally

Since this is a single, self-contained file, getting started is immediate:

1.  **Save the Code:** Save the entire provided code block into a file named `index.html`.
2.  **Open in Browser:** Double-click the `index.html` file.

The application will open and run locally in any modern web browser.

---

## ⚙️ Customization

All the content—from career paths and salary ranges to the learning modules and external links—is stored in a single JavaScript object.

To customize or expand the roadmaps:

1.  Open the `index.html` file and scroll down to the main `<script>` block.
2.  Locate the `ROADMAP_DATA` JavaScript constant.
3.  Add, remove, or edit objects within the `careerPaths` or `certificationPaths` arrays. The application will automatically parse and render the new data structure.
