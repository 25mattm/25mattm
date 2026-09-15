[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=460&lines=Hi%2C+I'm+Matthew+%F0%9F%91%8B;CS+%40+Dalhousie+%7C+;I+ship+things+people+actually+use)](https://github.com/25mattm)

Computer Science student at **Dalhousie University**, from Quispamsis, NB.

I build software for problems I've actually run into, most of them from coaching competitive sprint kayak at the Kennebecasis Paddling Centre, where I've been head coach since 2022.

---

## 🚀 Shipped

### 🔦 [Highlight Bar](https://apps.apple.com/us/app/highlight-bar/id6784490882) — *live on the Mac App Store*

A reading guide that floats over every app on your Mac. Built as an accessibility tool for readers with dyslexia, ADHD, low vision, or visual stress (Irlen).

**Features:**
- **Soft reading bar** — Tracks your cursor to lock your eyes on the current line, eliminating line-jump fatigue.
- **Spotlight mode** — Dims the rest of the page so only your line is visible, cutting visual noise for readers with ADHD or sensory sensitivity.
- **Screen tint** — Applies a warm overlay that reduces eye strain without color distortion, especially helpful for Irlen syndrome.
- **Click-through overlay** — Works seamlessly over any app; interact with text behind it without closing the guide.

**Built twice, natively.** The open-source version ships the same feature set as a Swift menu-bar app on macOS *and* a C# WinForms tray app on Windows — click-through overlay, multi-monitor cursor tracking, customizable bar dimensions, keyboard shortcuts, and system-level hotkeys all work identically across platforms.

Taking the macOS build through the full App Store submission was the real education: sandbox entitlements for global hotkeys, click-through overlay windows, conditional compilation for App Store vs. direct release, and packaging native code as a relocatable bundle.

Runs entirely on-device — no account, no data collection, no special permissions. MIT licensed.

`Swift` `SwiftUI` `C#` `WinForms` `macOS system APIs` `App Sandbox` `GitHub Actions` `Accessibility`

[📱 App Store](https://apps.apple.com/us/app/highlight-bar/id6784490882) · [💻 Source](https://github.com/25mattm/Highlighter)

---

## 🛠️ Building

### 📅 Course Scheduler — *complete*

Enrollment and roster management, end to end. A `@ManyToMany` mapping generates the join table; eleven REST endpoints cover courses, students, roster generation, and enroll/unenroll. Credentials stored securely with bcrypt hashing.

`Java 21` `Spring Boot` `Spring Data JPA / Hibernate` `React` `MySQL` `Maven`

[Backend](https://github.com/25mattm/course-scheduler) · [Frontend](https://github.com/25mattm/course-scheduler-frontend)

---

## 🧰 Stack

**Languages:** Java · Swift · C# · JavaScript/TypeScript · Python · SQL
**Backend:** Spring Boot · Spring Data JPA / Hibernate · FastAPI · REST API design · MySQL
**Frontend:** React · SwiftUI · WinForms · responsive UI · accessibility-focused UX
**Build & CI:** GitHub Actions (cross-platform build/release pipelines) · Maven · Git
**Infrastructure:** self-hosted Linux server I built and maintain — deployment, networking, uptime
**Tools:** Xcode · IntelliJ IDEA · Postman
**AI tooling:** Claude Code is my daily driver for iterative development and rapid prototyping

**Certifications:** Core Cybersecurity · Databases (ShiftKey Labs Academy, 2026)

---

## 🛶 Off the keyboard

Head Coach, Kennebecasis Paddling Centre (2022–present) — 40+ athletes, U10 through U18.
Sprint kayak head coach at two Canada Games: Niagara 2022, St. John's 2025. Canada Games athlete, Winnipeg 2017.

Coaching taught me the thing no course did: a system nobody wants to use at 6am in the rain is a system that doesn't exist.

---

📫 **matthew.mullett@dal.ca**

![Matthew's GitHub Stats](https://github-readme-stats.vercel.app/api?username=25mattm&show_icons=true&theme=default&hide_border=true)
