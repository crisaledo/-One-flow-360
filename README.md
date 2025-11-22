# CRM Light with Customizable Gemini Assistant

This is a lightweight, single-file Customer Relationship Management (CRM) system designed for small businesses and freelancers. It integrates basic lead management, scheduling, and automation features, along with a content assistant powered by the Gemini API.

## 🚀 Key Features

- **Lead Management**: Add, view, and manage potential clients with statuses (New, Contacted, Scheduled, Won, Lost).
- **Schedule Management**: Add appointments with service details and notes.
- **Simple Automations**: When scheduling a service, the system can automatically update the lead status.
- **Customizable Gemini Content Assistant**: Configure persona, tone, and assistant instructions to generate emails, posts, or follow-up messages.
- **Quick Actions**: Copy generated content or send to lead's WhatsApp.

## 🛠️ Tech Stack

- **Frontend**: HTML5, JavaScript (ES6+), Tailwind CSS (via CDN)
- **Backend/Data**: Google Firestore
- **AI**: Gemini API

## ⚙️ Quick Install & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/crisaledo/One-flow-360.git
   cd One-flow-360
   ```

2. Open the `index.html` file in a local server (recommended) or directly in your browser. For a simple server:
   - **Python 3**: `python -m http.server 8000`
   - **Node (http-server)**: `npx http-server . -p 8000`

3. Configure Firebase and Gemini API credentials:
   - Copy `.env.example` to `.env`
   - Add your Firebase and Gemini API keys
   - **Never commit private keys to the repository**

## ✅ Accessibility Checklist

Use this checklist to quickly test essential accessibility aspects before publishing:

- [ ] **Keyboard accessible clickable elements** (Tab/Enter/Space)
  - How to test: Navigate with Tab and activate menu/actions with Enter or Space
  - Expected result: Visible focus and action executed

- [ ] **Proper use of semantic elements** (buttons, headings, labels)
  - How to test: Inspect HTML and confirm buttons for actions and labels for inputs

- [ ] **Basic ARIA states for tabs/panels**
  - How to test: Verify aria-selected and aria-hidden when navigating between tabs

- [ ] **Sufficient color contrast** for text and interactive elements
  - How to test: Use https://contrast-ratio.com/ or Lighthouse/AXE extension
  - Expected result: Contrast >= 4.5:1 for normal text

- [ ] **Inputs have associated labels** (visible or sr-only)
  - How to test: Verify each input has a label or aria-label

- [ ] **Visible focus on interactive elements**
  - How to test: Navigate with keyboard and check outlines or focus styles

- [ ] **Readable content at different screen sizes** (responsiveness)
  - How to test: Resize window or use devtools

- [ ] **Screen reader navigation** (basic)
  - How to test: Open a screen reader (NVDA/VoiceOver) and verify order/semantics make sense

## 🧪 Simple Usability Tests (manual steps)

Run these tests quickly to ensure the main flow works:

- **Test 1 — Tab Navigation**
  1. Open the page
  2. Click each sidebar menu item
  3. Verify the corresponding panel is shown and menu receives active state
  4. Expected result: Content changes without errors and aria-selected/aria-hidden updated

- **Test 2 — Lead Search (example field)**
  1. Type in "Search lead..." field and observe behavior (if filter implemented)
  2. Expected result: No JS errors and field is keyboard editable

- **Test 3 — Form Accessibility**
  1. Open Settings and navigate to inputs
  2. Test filling name and email
  3. Expected result: Visible or associated labels and inputs accept entry

- **Test 4 — Quick Responsiveness**
  1. Open on a small screen (mobile) or use devtools
  2. Verify layout doesn't break and elements remain visible/actionable

## 🤝 How to Contribute

- Open an issue describing the problem or improvement
- Fork the repository, create a branch with your changes, and submit a Pull Request

## 🔒 Security

- **Never include API keys or credentials in the public repository**. Use environment variables or a configuration file that is in `.gitignore`.

## 📧 Contact

For questions, open an issue or contact: crisaledo (GitHub)