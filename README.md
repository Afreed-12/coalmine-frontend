# Coal Mine Worker Safety & Health Monitoring System

A modern React and Vite-based web application designed for coal mine operations to monitor worker attendance, manage worker health records, track occupational health vitals, handle real-time safety alerts, and generate compliance reports.

---

## 🌟 Key Features

- **🔐 Authentication & Role Management:**
  - Admin registration and secure login portal.
- **📊 Real-time Dashboard:**
  - Overview of active workers, safety metrics, environmental alerts, and shift summaries.
- **👷 Worker Management:**
  - Worker profile registration with personal, contact, and medical details.
  - Searchable and filterable worker records.
- **⏱️ Shift & Attendance Tracking:**
  - Worker check-in and check-out management.
  - Daily and shift-wise attendance logging.
- **🚨 Health & Safety Alerts:**
  - Real-time alerts for abnormal vitals (heart rate, SpO2, body temperature) and hazardous environmental conditions.
- **📈 Health Analytics:**
  - Graphical visual trends and health analytics for early detection of occupational risks.
- **📑 Reports & Audits:**
  - Exportable safety compliance, shift logs, and worker health reports.
- **⚙️ Settings:**
  - System configuration, alert threshold settings, and administrative controls.

---

## 🛠️ Tech Stack

- **Frontend Framework:** [React 19](https://react.dev/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Routing:** [React Router DOM v7](https://reactrouter.com/)
- **Styling:** Modular CSS & Responsive Design

---

## 🚀 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) (version 18+ recommended) installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Afreed-12/coalmine-frontend.git
   cd coalmine-frontend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`.

---

## 📦 Available Scripts

- `npm run dev` - Starts the development server with Hot Module Replacement (HMR).
- `npm run build` - Builds the application for production in the `dist` directory.
- `npm run preview` - Locally previews the production build.

---

## 📂 Project Structure

```text
coalmine-frontend/
├── index.html
├── package.json
├── vite.config.js
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── components/
    │   ├── layout/       # Navbar, Sidebar, MainLayout
    │   └── ui/           # Reusable UI components & cards
    ├── pages/            # Dashboard, Login, Worker Records, Alerts, Analytics, Reports
    ├── data/             # Dummy data & mock schemas
    └── styles/           # Global styles and themes
```

---

## 📄 License

This project is licensed under the ISC License.
