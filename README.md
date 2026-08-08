[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=460&lines=Hi%2C+I'm+Matthew+%F0%9F%91%8B;CS+%40+Dalhousie+%7C+Class+of+2027;I+ship+things+people+actually+use)](https://git.io/typing-svg)

Computer Science student at **Dalhousie University** (expected May 2027), from Quispamsis, NB.

I build software for problems I've actually run into — most of them from coaching competitive sprint kayak at the Kennebecasis Paddling Centre, where I've been head coach since 2022.

---

## 🚀 Shipped

### 🔦 [Highlight Bar](https://apps.apple.com/us/app/highlight-bar/id6784490882) — *live on the Mac App Store*

A reading guide that floats over every app on your Mac. A soft bar follows your cursor so your eyes never lose the line; spotlight mode dims the rest of the page; screen tint washes the display in a calming colour for visual-stress relief. Clicks pass straight through, so it never gets in your way.

Built as an accessibility tool for readers with dyslexia, ADHD, low vision, or visual stress (Irlen).

**Built twice, natively.** The open-source version ships the same feature set as a Swift menu-bar app on macOS *and* a C# WinForms tray app on Windows — click-through overlay, multi-monitor cursor tracking, and a global `Ctrl/⌘ + Shift + H` toggle on both. GitHub Actions builds macOS on `macos-latest` and Windows on `windows-latest`, so pushing a version tag produces both release artifacts without either toolchain locally.

Taking the macOS build through the full App Store submission was the real education: sandbox entitlements for global hotkeys, click-through overlay windows, conditional compilation for App Store vs. direct builds, privacy documentation, screenshot sets. Shipped v1.0 on July 1 and v1.0.1 on July 7 with native Intel Mac support, better VoiceOver in the colour picker, and lower background CPU.

Runs entirely on-device — no account, no data collection, no special permissions. MIT licensed.

`Swift` `SwiftUI` `C#` `WinForms` `macOS system APIs` `App Sandbox` `GitHub Actions` `Accessibility`

[📱 App Store](https://apps.apple.com/us/app/highlight-bar/id6784490882) · [💻 Source](https://github.com/25mattm/Highlighter)

---

## 🛠️ Building

### 🛶 CoachSync — *in active use*

Native iOS app for competitive sprint canoe/kayak club management, backed by a Spring Boot API. Coaches running five age categories at once track attendance, interval times, athlete notes, and cross-category crew boats — normally on paper clipboards that fall apart the moment they get wet.

**I run the infrastructure too.** The backend runs on a physical server I built and maintain myself, so I own the deployment, the networking, and the uptime. When it breaks at 6am before practice, I'm the one fixing it.

- Structured session logging designed to be completed one-handed on a dock
- Athletes auto-assigned to age categories from date of birth, then assembled into flexible cross-category crews
- Data model mapped to the Canadian Kayak Centre yearly training plan, with per-session training zone breakdowns
- ~300 automated tests across the API and the app, an OpenAPI/Swagger contract, and a wire-contract test keeping both sides honest
- Production JWT secret guard and active-coach request filter, added while working through a structured code review

`Swift` `SwiftUI` `Spring Boot (Java 21)` `Spring Data JPA` `MySQL` `REST / OpenAPI` `JWT` `Self-hosted Linux`

### 📅 Course Scheduler — *complete*

Enrollment and roster management, end to end. A `@ManyToMany` mapping generates the join table; eleven REST endpoints cover courses, students, roster generation, and enroll/unenroll. Credentials stay out of source control via environment variables.

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

**Certifications:** Core Cybersecurity · Databases After Graduation — *ShiftKey Labs Academy UP, 2026*

---

## 🛶 Off the keyboard

Head Coach, Kennebecasis Paddling Centre (2022–present) — 40+ athletes, U10 through U18.
Sprint kayak head coach at two Canada Games: Niagara 2022, St. John's 2025. Canada Games athlete, Winnipeg 2017.

Coaching taught me the thing no course did: a system nobody wants to use at 6am in the rain is a system that doesn't exist.

---

📫 **matthew.mullett@dal.ca**

![Matthew's GitHub Stats](https://github-readme-stats.vercel.app/api?username=25mattm&show_icons=true&theme=default&hide_border=true)
