# Job Listings Application

A React-based web application for managing job listings with full CRUD operations. Built with Vite, React, and Tailwind CSS.

## Features

- Browse job listings with details like title, type, location, salary, and company information.
- Add new job listings.
- Edit existing job listings.
- Delete job listings.
- Responsive design using Tailwind CSS.
- Modular components for navigation, hero section, home cards, job listings, and viewing all jobs.
- Sample job data stored in JSON format.
- Backend simulation using JSON Server for API endpoints.

## Tech Stack

- **Frontend:** React 19, Vite
- **Styling:** Tailwind CSS
- **Build Tool:** Vite
- **Linting:** ESLint

## Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SatyaTejaChukka/jobListings-react.git
   
   cd joblistings
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

## Usage

To run the backend simulation (JSON Server):

```bash
npm run server
```

To run the application in development mode (in a separate terminal):

```bash
npm run dev
```

To build for production:

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

To lint the code:

```bash
npm run lint
```

## Directory Structure

```
joblistings/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── images/
│   │       └── logo.png
│   ├── components/
│   │   ├── Card.jsx
│   │   ├── Hero.jsx
│   │   ├── HomeCards.jsx
│   │   ├── JobListing.jsx
│   │   ├── JobListings.jsx
│   │   ├── Navbar.jsx
│   │   ├── Spinner.jsx
│   │   └── ViewAllJobs.jsx
│   ├── layouts/
│   │   └── MainLayout.jsx
│   ├── pages/
│   │   ├── AddJobPage.jsx
│   │   ├── EditJobPage.jsx
│   │   ├── HomePage.jsx
│   │   ├── JobPage.jsx
│   │   ├── JobsPage.jsx
│   │   └── NotFoudPage.jsx
│   ├── App.jsx
│   ├── index.css
│   ├── jobs.json
│   └── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── README.md
└── vite.config.js
```

