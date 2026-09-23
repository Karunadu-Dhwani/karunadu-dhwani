# Karunadu Dhwani (ಕರುನಾಡು ಧ್ವನಿ)

### A Smart Citizen Grievance Reporting and Resolution Platform

> ನಿಮ್ಮ ಧ್ವನಿ, ನಮ್ಮ ಪರಿಹಾರ: *Your voice, our solution.*

Karunadu Dhwani is a web platform that enables citizens to report civic issues such as potholes, garbage, broken streetlights, water problems, drainage issues, and other public concerns. Citizens can submit grievances with relevant details, photos, and locations, track their status, and follow the progress until resolution.

Authorities get a centralized dashboard to receive, review, prioritize, update, and resolve grievances, helping improve transparency, communication, and civic issue management.

---

## 📌 Project Status

> 🚧 **Under Development**

Karunadu Dhwani is currently being developed as a college academic project. Core features, user interfaces, authentication, grievance management, database integration, and other modules are being implemented and tested.

The project is also being developed with the possibility of using it as the foundation for a future research paper.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Academic Project](#academic-project)
- [Team](#team)
- [License](#license)

---

## Features

### For Citizens

- Report an issue with a title, description, category, photo, and location
- Track the status of each complaint:
  **Submitted → In Review → In Progress → Resolved**
- View issues reported in the user's area
- Secure sign-in and account management
- View personal complaint history

### For Authorities / Admins

- Dashboard to view, filter, and sort grievances
- Review submitted complaints
- Update grievance status
- Add remarks and resolution information
- Category-wise and area-wise overview of grievances
- Manage open and resolved issues

### Platform

- Responsive design for desktop and mobile
- Secure authentication
- Role-based access
- Supabase-powered data storage and authentication
- File/image storage for grievance evidence

> Features will be updated as development progresses.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React, Vite |
| Backend / Database | Supabase |
| Database | PostgreSQL |
| Authentication | Supabase Auth |
| Storage | Supabase Storage |
| Styling | To be finalized |
| Hosting | To be finalized |

---

## Getting Started

### Prerequisites

- Node.js 18 or later
- npm
- A Supabase project

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/karunadu-dhwani.git

# 2. Enter the project directory
cd karunadu-dhwani

# 3. Install dependencies
npm install

# 4. Create your environment file
cp .env.example .env

# 5. Add your Supabase configuration

# 6. Start the development server
npm run dev
```

The application will normally be available at:

```text
http://localhost:5173
```

### Build for Production

```bash
npm run build
npm run preview
```

---

## Environment Variables

Create a `.env` file in the project root:

```env
VITE_SUPABASE_URL=your-supabase-project-url
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
```

These values can be obtained from the Supabase project settings.

> **Important:** Never commit `.env` or private credentials to GitHub. Keep service-role keys and other secrets private.

---

## Project Structure

```text
karunadu-dhwani/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── lib/
│   ├── App.jsx
│   └── main.jsx
├── .env.example
├── package.json
└── README.md
```

> The structure will be updated to match the actual project as development progresses.

---

## Usage

### Citizen

1. Register or log in.
2. Select **Report an Issue**.
3. Choose the appropriate category.
4. Enter the issue details.
5. Add a photo and location where applicable.
6. Submit the grievance.
7. Track the grievance status from the user's dashboard.

### Authority / Admin

1. Log in to the authority/admin dashboard.
2. Review submitted grievances.
3. Filter or search for relevant issues.
4. Update the grievance status.
5. Add remarks or resolution information.
6. Mark the grievance as resolved when the issue is completed.

---

## 🔄 Grievance Workflow

```text
Citizen
   │
   ▼
Register / Login
   │
   ▼
Report Civic Issue
   │
   ▼
Grievance Submitted
   │
   ▼
Authority Review
   │
   ▼
In Progress
   │
   ▼
Resolution
   │
   ▼
Resolved
```

---

## Roadmap

- [ ] Kannada and English language support
- [ ] Interactive map for reported issues
- [ ] Email / SMS notifications
- [ ] Advanced grievance analytics
- [ ] Department-based grievance assignment
- [ ] Priority-based issue handling
- [ ] Automatic issue categorization
- [ ] Mobile application
- [ ] Public transparency dashboard
- [ ] Research-based evaluation and analysis

---

## Academic Project

**Project Title:**

> **Karunadu Dhwani – A Smart Citizen Grievance Reporting and Resolution Platform**

**Project Type:** College Academic Project

**Domain:** Smart Governance / Civic Technology

The project is being developed as a full-stack civic technology platform and may be used as the foundation for a research paper covering the system design, implementation, methodology, and evaluation.

---

## Team

### Project Lead / Developer

- **Yashwanth B K**

### Team Members

- *Add teammate names and roles here if applicable.*

### Project Guide

- *Add guide's name, department, and college.*

---

## License

The project license will be finalized before public distribution.

> If the project is later released under the MIT License, add the `LICENSE` file and update this section accordingly.

---

<p align="center">

**Karunadu Dhwani — Giving citizens a digital voice.**

Made with ❤️ in Karnataka

</p>
