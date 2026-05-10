# 🎓 COMSATS University Notice Board

A static university notice board web app for COMSATS Lahore Campus. Built to learn and practice CI/CD pipelines, GitHub Actions, Docker, and feature branch workflows.

## Pages

- **Home** — Dashboard with active notices, exam schedule, and admission updates
- **Notices** — Academic announcements and urgent alerts
- **Exams** — Upcoming exam schedule
- **Admissions** — Admission updates and deadlines
- **Contact** — Contact information

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML, CSS, JavaScript |
| Bundler | Parcel |
| Container | Docker |
| CI/CD | GitHub Actions |

## Run with Docker

```bash
docker build -t uni-notice-board .
docker run -p 5500:5500 uni-notice-board
```

Open `http://localhost:5500`

## Run Locally

```bash
npm install
npm start
```

## CI/CD Pipeline

Every push and pull request triggers GitHub Actions which installs dependencies, runs build checks, and validates the project. Feature branches are merged into develop via pull requests.

## Branch Strategy

- main
- develop
- feature/notices
- feature/exams
- feature/admissions
- feature/contact

## Author

Fatima Azfar — [@fatima-azfarr](https://github.com/fatima-azfarr)
