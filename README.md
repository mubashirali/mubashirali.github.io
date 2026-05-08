### Overview

This repository hosts my single-page interactive profile, which serves as a dynamic alternative to a traditional resume. It was designed to enhance user experience (UX) and clarity by transforming a linear document into an explorable, thematic application.

**Goal:** To allow recruiters and hiring managers to easily explore and synthesize my 11+ years of experience—focusing on career progression, quantifiable impact, and technical depth—in a single, intuitive interface.


### Technical Stack & Architecture

This application is built as a complete, self-contained Single-Page Application (SPA) to ensure speed and reliability.

| Category | Technology / Tool | Rationale |
| :--- | :--- | :--- |
| **Backend / Core** | Vanilla JavaScript | Implements core logic, state management, and DOM manipulation for maximum performance and a low footprint. |
| **Data Structure** | JSON/JavaScript Objects | Stores career data, skills, and metrics in structured JSON for easy parsing and dynamic filtering. |
| **Styling / Frontend** | Tailwind CSS (CDN) | Used for building a fully responsive, modern UI/UX with utility-first classes, ensuring fast load times and cross-device consistency. |
| **Data Visualization** | Chart.js (Canvas) | Used for dynamic, interactive charts (Bar and Radar) to visualize proficiency levels and key metrics effectively. |
| **Deployment** | GitHub Pages | Zero-cost, high-availability hosting with seamless integration. |

### Key Design & Information Architecture

The design structure intentionally deviates from a linear resume to prioritize **user efficiency** and **data consumption**:

* **Thematic Navigation:** Content is segmented into **Overview**, **Timeline**, and **Skills** tabs, allowing a user to jump directly to their area of interest (e.g., a recruiter can immediately view my core technology list).
* **Data Transformation:** The traditional job listing (Timeline tab) is converted into a vertical, interactive list where key achievements and metrics are **revealed on click**.
* **Interactive Dashboard:** The Skills tab utilizes **Chart.js Radar** and **dynamic filtering** to turn a dense list of over 20 technologies into a digestible, explorable dataset, showcasing proficiency levels at a glance.
