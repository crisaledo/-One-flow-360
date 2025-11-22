# CRM Light with Customizable Gemini Assistant

This is a lightweight, single-file Customer Relationship Management (CRM) system designed for small businesses and freelancers. It integrates basic lead management, scheduling, and automation features, plus a content assistant powered by the Gemini API.

## 🚀 Main Features

- Lead Management: Add, view, and manage potential customers with status tracking (New, Contacted, Scheduled, Won, Lost).
- Schedule Management: Add appointments with service details and notes.
- Simple Automations: When scheduling a service, the system can automatically update the lead status.
- Customizable Gemini Content Assistant: Configure persona, tone, and assistant instructions to generate emails, posts, or follow-up messages.
- Quick Actions: Copy generated content or send to lead's WhatsApp.

## 🛠️ Technologies

- Frontend: HTML5, JavaScript (ES6+), Tailwind CSS (via CDN)
- Backend/Data: Google Firestore
- Artificial Intelligence: Gemini API

## ⚙️ Installation and Quick Start

1. Clone the repository:
   git clone https://github.com/crisaledo/-One-flow-360.git
2. Open the index.html file in a local server (recommended) or directly in the browser. For a simple server:
   - Python 3: python -m http.server 8000
   - Node (http-server): npx http-server . -p 8000
3. Configure Firebase and Gemini API credentials according to your environment (variables or configuration file). Do not upload private keys to the repo.

## ✅ Accessibility Checklist (simple)
Use this checklist to quickly test essential accessibility aspects before publishing.

- [ ] Clickable elements are keyboard accessible (Tab/Enter/Space).
  - How to test: navigate with Tab and activate menu/actions with Enter or Space.
  - Expected result: visible focus and action executed.
- [ ] Correct use of semantic elements (buttons, headings, labels).
  - How to test: inspect the HTML and confirm buttons for actions and labels for inputs.
- [ ] Basic ARIA states for tabs/panels.
  - How to test: check aria-selected and aria-hidden when navigating between tabs.
- [ ] Sufficient color contrast for text and interactive elements.
  - How to test: use https://contrast-ratio.com/ or the Lighthouse/AXE extension.
  - Expected result: contrast >= 4.5:1 for normal text.
- [ ] Inputs have associated labels (visible or sr-only).
  - How to test: verify that each input has a label or aria-label.
- [ ] Visible focus on interactive elements.
  - How to test: navigate with keyboard and check outlines or focus styles.
- [ ] Readable content at different screen sizes (responsiveness).
  - How to test: resize the window or use devtools.
- [ ] Screen reader navigation (basic).
  - How to test: open a screen reader (NVDA/VoiceOver) and verify that the order/semantics make sense.

## 🧪 Simple Usability Tests (manual steps)
Execute these tests quickly to ensure the main flow works.

- Test 1 — Tab Navigation
  1. Open the page.
  2. Click on each item in the side menu.
  3. Verify that the corresponding panel is shown and the menu receives the active state.
  4. Expected result: content changes without errors and aria-selected/aria-hidden updated.

- Test 2 — Lead Search (example field)
  1. Type in the "Search lead..." field and observe behavior (if filter is implemented).
  2. Expected result: no JS errors and field is editable with keyboard.

- Test 3 — Form Accessibility
  1. Open Settings and navigate to inputs.
  2. Test filling in name and email.
  3. Expected result: labels visible or associated and inputs accept entry.

- Test 4 — Quick Responsiveness
  1. Open on a small screen (mobile) or use devtools.
  2. Verify that layout doesn't break and elements remain visible/actionable.

## How to Contribute
- Open an issue describing the problem or improvement.
- Fork the repository, create a branch with your changes, and submit a Pull Request.

## Security
- Never include API keys or credentials in the public repository. Use environment variables or a configuration file that is in .gitignore.

## Contact
For questions, open an issue or contact: crisaledo (GitHub)

----

(Added accessibility checklist and simple usability test instructions.)