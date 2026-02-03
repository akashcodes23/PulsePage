# PulsePage — Interactive UI Behavior Engine

**PulsePage** is a client-side, interaction-driven web application engineered to demonstrate **event-based DOM manipulation**, **real-time UI state changes**, and **responsive layout control** using **vanilla web technologies**.

The project emphasizes **behavioral UI logic over static presentation**, showcasing how lightweight JavaScript can drive engaging, dynamic user experiences without frameworks or external dependencies.

---

## Live Deployment
▶ https://akashcodes23.github.io/PulsePage/

---

##  Core Engineering Highlights
- **Event-driven UI architecture** using native JavaScript
- **Dynamic element positioning** via real-time coordinate computation
- **State transition rendering** without page reloads
- **Responsive container-bound motion logic**
- **Strict UTF-8 compliance** for cross-platform compatibility

---

## Technical Stack
| Layer | Technology |
|------|-----------|
| Markup | HTML5 (Semantic Structure) |
| Styling | CSS3 (Flexbox, Gradients, Visual Hierarchy) |
| Logic | JavaScript ES6 (DOM APIs, Timers, Events) |
| Deployment | GitHub Pages (Static Hosting) |

---

## System Design Overview

PulsePage/
├── index.html        # Unified entry point (markup, style, logic)
└── README.md         # Technical documentation

---

## Interaction Logic Breakdown
- **Dynamic Avoidance Algorithm**  
  The "No" button calculates available movement space based on parent container dimensions and repositions itself using randomized vectors at fixed intervals.

- **Event Handling & State Mutation**  
  User confirmation triggers a full DOM state replacement, rendering a success view without navigation or reload.

- **Performance Considerations**  
  All logic executes client-side with minimal reflow impact and zero external assets except media.

---

## Design & UX Principles
- **Immediate feedback loops**
- **Motion-driven persuasion mechanics**
- **Minimal cognitive load**
- **Mobile-first responsiveness**

---

## Use Cases & Applicability
- Frontend engineering demonstrations
- UI/UX behavior prototyping
- DOM manipulation learning reference
- Interactive landing page concepts
- Creative technical showcases

---

## Roadmap Enhancements
- CSS-based animation pipeline (keyframes / transitions)
- Modular JavaScript separation
- Accessibility (ARIA roles, keyboard support)
- Performance throttling using `requestAnimationFrame`
- Theming via CSS variables

---

## Author
**Akash G Patil**  
GitHub: https://github.com/akashcodes23

---

## Licensing
Released under the **MIT License** — free for modification, reuse, and distribution.
