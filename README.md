# 🧭 IPC Lab Project – Digital Navigation Tool

This project aims to develop a JavaFX-based desktop application to simulate a digital nautical chart for recreational boat skipper exam training.

---

## 📌 Features

- User registration, authentication, and profile management
- Solve navigation problems (MCQs) with performance tracking
- Interactive digital chart with drawing tools (points, lines, arcs, text, etc.)
- Measurement tools: ruler and protractor
- Data persistence via SQLite using the provided `IPC2025.jar`

---

## 🚧 Development Roadmap

### ✅ Phase 0: Setup

- ✅ Clone or create your NetBeans JavaFX project
- [ ] Import the `IPC2025.jar` into the project
- [ ] Place provided resources in `/resources/`
  - `carta_nautica.jpg`
  - `transportador.jpg`
  - `regla.jpg`
- [ ] Set up the base GUI using JavaFX (`Scene`, `ScrollPane`, `ImageView`, etc.)

---

### 🧑‍💻 Phase 1: User Management

- [ ] Implement registration form with validation:
  - Username (6–15 chars, no spaces)
  - Password (8–20 chars, one uppercase, one lowercase, one digit, one special char)
  - Email, birthdate, avatar
- [ ] Add login & logout functionality
- [ ] Profile modification (except username)

---

### 🧪 Phase 2: Session & Problem Solving

- [ ] Load problems from database (via IPC2025.jar)
- [ ] Implement random or manual problem selection
- [ ] Display 4 shuffled MCQ answers
- [ ] Store user's correct/incorrect answers per session
- [ ] Display user progress with filtering options

---

### 📊 Phase 3: Chart Interaction Tools

- [ ] Implement zoom in/out on `ImageView`
- [ ] Drawing tools:
  - [ ] Plot point
  - [ ] Draw line (2 points)
  - [ ] Draw arc (center + radius)
  - [ ] Annotate text
- [ ] Modify tools:
  - [ ] Change color/thickness
  - [ ] Delete marks
  - [ ] Clear entire chart
- [ ] Measurement tools:
  - [ ] Move protractor, measure/draw angles
  - [ ] Use ruler to measure distance between 2 points
  - [ ] Display lat/long by extending lines to chart edges

---

### 💾 Phase 4: Persistence

- [ ] Ensure all user actions (registration, sessions, answers) are persisted using `IPC2025.jar`
- [ ] Test the automatic database file (`database.db`) creation
- [ ] Use DB Browser for SQLite to inspect the DB content

---

## 🧪 Testing & Delivery

- [ ] Review and validate user flows
- [ ] Test drawing tool responsiveness and accuracy
- [ ] Verify data saving and retrieval
- [ ] Prepare low-fidelity design prototypes for review
- [ ] Submit as a group of 3, following the delivery instructions

---

## 📂 Resources

- Base Project: `Poi_UPV`
- SQLite Viewer: [DB Browser](https://sqlitebrowser.org/)
- Provided JAR: `IPC2025.jar` (includes model + DB handling)

---

## 📞 Contacts

- For any library-related errors, wait for the upcoming documentation PDF.
