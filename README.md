# Vibe Check 🌸

A high-fidelity, interactive single-page micro-frontend designed to engineer high-stakes user conversion funnels (securing a "Yes") with automated rejection-handling protocols. Built entirely using vanilla web technologies, this lightweight application explores programmatic particle simulations, asynchronous multi-stage UI states, and responsive layout constraints.

## 🚀 Live Demo
See the app in action [here](https://vibe-chck.netlify.app/)

---

## 🛠️ Technical Highlights

### 1. Programmatic Particle Simulation Engine
Instead of relying on bloated third-party graphics libraries, the app utilizes a pure Vanilla JavaScript engine to dynamically instantiate and manage falling canvas elements.
* **Memory Management:** Automatically cleans up the DOM by garbage-collecting heart nodes (`h.remove()`) exactly 9 seconds after instantiation to prevent memory leaks during extended user sessions.
* **Mathematical Randomization:** Generates unique sizing, falling velocities, and horizontal positioning offsets in real-time using `Math.random()`.

### 2. Multi-Stage Asynchronous State Machine
The user journey transitions seamlessly through a sequential series of structural application views handled entirely via JavaScript event timing and CSS layout states:
* `Intro Messages` (Sequential fading array loops) → `The Conversion Offer` (Interactive buttons) → `Success Confirmation` → `Final Media Payload` (The GIF finish).

### 3. Rejection-Handling UI Protocol (The "No" Interaction)
To guarantee a high-converting user experience, the "No" button implements an intentional state lock. Clicking the button safely triggers a brief asynchronous visual reset, momentarily disabling user input before restoring its original state with playful feedback—preserving user delight while strongly guiding them toward the primary conversion path.

### 4. Hybrid Responsive Architecture
Engineered using modern fluid styling guidelines to bridge diverse viewports flawlessly:
* Utilizes localized CSS custom properties (`:root` design tokens) for fast global theme changes.
* Implements a desktop-first immersive canvas overlay (`--bg-dark`) that naturally shifts into a focused, content-first mobile layout using CSS media breakpoints (`@media (max-width: 768px)`).

---

## 🏗️ Architecture & Stack
* **Frontend Structure:** Semantically organized HTML5 layout.
* **Styling Engine:** Custom CSS3 layout leveraging Flexbox alignment, absolute coordinate systems, and performant GPU-accelerated keyframe animations (`@keyframes`).
* **Logic Layer:** Asynchronous Vanilla JS (ES6+) utilizing explicit DOM manipulation and standard event listener mappings.

---

## 💻 Local Setup & Deployment

Because this project is built entirely on native web standards, it has zero dependencies and requires no compilation step.

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. **Launch the app:**
   Simply double-click the `index.html` file to open it in any modern browser, or spin up a local server using the VS Code Live Server extension.

3. **Deploy:**
   Drag and drop the `index.html` file directly into [Vercel](https://vercel.com) or [Netlify](https://netlify.com) for immediate production deployment.

---

*Developed as a high-vibes, low-commitment engineering experiment.* 😉
