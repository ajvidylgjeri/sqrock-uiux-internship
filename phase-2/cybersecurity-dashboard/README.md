# AegisOps – Cybersecurity Dashboard (UI/UX)

Sqrock IT Solutions · UI/UX Internship · Phase 2 · Task 1

A dark-mode-first security operations dashboard for analysts and administrators, delivered as a **clickable HTML/CSS/JS prototype** (single file, no build step) with exported screens.
Open `index.html` in a browser. Start at the login screen; any credentials work.

## Screens (all linked from the sidebar)
1. **Login** – logo, welcome message, email/username, password, remember me, forgot password, login, optional **two-factor step** (code entry)
2. **Dashboard** – total alerts, active threats, risk score, system health, threat detection chart, security score donut, network activity, firewall status, device status, recent incidents, activity heatmap
3. **Threat monitoring** – severity counters, search, severity chips, category filter, active-threat table, detection timeline, threat categories
4. **Incident details** – title, description, date/time, severity, assigned analyst, resolution status, activity timeline, action buttons (isolate, escalate, contain, close)
5. **Devices & network** – connected devices, health bars, online/offline, vulnerabilities, traffic chart, protocols, firewall status
6. **Reports & analytics** – threat trend line chart with range switch (3/6/12 months), attack statistics donut, monthly bar chart, download-report buttons (UI)
7. **User management (optional)** – user list, roles, permission toggles, activity log, add/edit actions
8. **Settings** – profile, notification preferences, theme (light/dark), security settings, logout
9. **Design system** – palette with contrast notes, typography, buttons, badges, chips, toggles, icons, spacing

Bonus features included: light & dark mode, glassmorphism top bar and notification panel, interactive charts (hover tooltips, range switching), live-alert pulse, security heatmap, command-centre style overview, responsive desktop / tablet / narrow layouts.

## Design decisions
- **Information hierarchy:** the four numbers an analyst needs first (alerts, active threats, risk, health) sit in the top row; detail lives below and one click away.
- **Severity is never colour-only:** every badge carries its label (Critical / High / Medium / Low) and uses a distinct hue plus outline.
- **Contrast:** body text on panels is above 14:1 in dark mode; accent colours are used for large text, borders and badges. Light theme uses darker variants of the same hues.
- **Responsive:** sidebar becomes an icon rail on tablet (<1100px) and a tab strip on narrow screens; cards re-flow from 4 → 2 → 1 columns.
- **Accessibility:** visible focus rings, labelled icon buttons, `prefers-reduced-motion` respected, charts have `aria-label`s and tooltips.

## Exports
`screens/` has desktop (1440 px) and tablet (820 px) PNGs of every screen, plus notification panel, light mode and narrow-mobile views.

## Honest status
- This is a code-built prototype, **not a Figma/Adobe XD file**: no design-tool account or file link could be created from the environment where it was made. The screens and design system are structured so they can be rebuilt as Figma frames/components one-to-one.
- All data is fictional.
