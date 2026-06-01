# To-Do-Dashboard
A sleek, dark-themed, single-page personal dashboard designed to streamline daily workflows. Built using pure frontend technologies, it features a dynamic to-do list tracking system and local storage persistence, combined with a quick navigation panel for frequently used professional platforms.

# 🚀 Features
**Dynamic To-Do Tracker:** Easily add, edit, and delete tasks. Includes an intractive progress bar and counter (e.g., 2/6) that updated in real-time a tasks are completed.

**Local Storage Persistence:** Tasks and their completion tates are automatically saved to the browser's `localStorage`, ensuring your data survives page refreshes. 

**Centralized Navigation Hub:** A dedicated quick-links sidebar tailored for fast access to essential developer tools, platforms, and external documentation (e.g., Dashboard, Calendar, Email, and portals).

**Responsive Dark Aesthetics:** Modern UI boasting an ultra-clean, high-contrast dark modern palette with responsive layout design. 

# 🛠️ Tech Stack

**HTML5:** Semantic structure for layouts, input forms, and navigation panels.

**CSS3:** Custom styling featuring flexible layout layouts, smooth transitions, custom scrollbars , and a neon-accented dark theme. 

**Vanilla Javacript (ES6+):** Dynamic DOM manipulation, state tracking for task progress calculations, and `localStorage` integration for persistence data state. 

# 📦 Getting Started

## Prerequisites
Since this is a lightweight application, client-side application, you only need a modern web browser to run it. 

## Installation

1. Clone the repository:

2. Navigate into the project directory

3. Open `index.html` directly into your browser, or serve it using a local development server like Live Server in VS Code.

# 💾 Local Storage Architecture
The task state is managed via a JSON array stored directly under a local key. The application parses this data on initial load to render the task nodes and re-calculates the completion ratio whenever a change event (`add`, `completed`, `delete`) is triggered. 
