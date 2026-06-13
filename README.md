# ⚙️ React App — CI/CD Pipeline with GitHub Actions

> A hands-on DevOps project implementing a complete CI/CD pipeline for a **React + Vite** application using **GitHub Actions** — covering automated linting, unit testing, and build validation on every push and pull request.

---

## 🧑‍💻 About Me

I'm a **DevOps Engineer** with **3.5+ years** of hands-on experience designing and automating cloud infrastructure, CI/CD pipelines, and container orchestration at scale. Currently at **DXC Technology**, driving reliability and delivery velocity for Hewlett Packard Enterprise's cloud ecosystem.

- 🔭 I build and maintain **production-grade AWS infrastructure** using Terraform & CloudFormation
- ⚡ I live in the terminal — **Bash/Python scripts, Kubernetes clusters, and Helm charts** are my daily playground
- 📈 Obsessed with **observability** — Prometheus, Grafana, and zero-downtime deployments
- 🏆 Certified in **AZ-900** and **GitHub Actions (GH-200)**
- 📍 Based in **Hyderabad, India** — building, shipping, and automating

---

## 🚀 Project Overview

This project demonstrates how to integrate a production-style CI/CD pipeline into a modern React application using GitHub Actions. The pipeline automatically runs ESLint checks, Vitest unit tests, and a Vite production build on every code change — ensuring code quality and build integrity before any merge.

The app itself is a React 18 component-based project built with Vite for fast development and optimized production output.

---

## ⚙️ CI/CD Pipeline — What's Implemented

| Stage | Tool | Description |
|---|---|---|
| Trigger | GitHub Actions | Workflow fires on `push` and `pull_request` to `master` |
| Lint | ESLint + `eslint-plugin-react` | Enforces React code quality rules |
| Test | Vitest + Testing Library | Runs unit tests with jsdom environment |
| Build | Vite | Compiles and bundles the app for production |

### Pipeline Highlights
- ✅ Automated lint + test + build on every commit
- ✅ PR-gated checks — broken builds can't slip through
- ✅ Fast feedback loop using Vite's optimized build system
- ✅ Testing Library setup for component-level unit tests

---

## 🛠️ Tech Stack

**Application**
- React 18 — UI components and application logic
- Vite — dev server and production bundler
- prop-types — runtime prop validation

**Testing & Quality**
- Vitest — unit test runner
- @testing-library/react — component testing utilities
- @testing-library/user-event — user interaction simulation
- ESLint + eslint-plugin-react — static code analysis

**CI/CD**
- GitHub Actions — pipeline orchestration

---

## 📁 Project Structure

```
├── .github/
│   └── workflows/         # GitHub Actions workflow definitions
├── public/                # Static assets
├── src/                   # React components and app logic
├── .eslintrc.json         # ESLint configuration
├── vite.config.js         # Vite build configuration
└── package.json           # Dependencies and scripts
```

---

## 🧪 Running Locally

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Run unit tests
npm test

# Lint the codebase
npm run lint

# Build for production
npm run build
```

---

## 🔗 Links

- 💼 **LinkedIn:** [linkedin.com/in/sai-mouli](https://www.linkedin.com/in/sai-mouli/)
- 🐙 **GitHub:** [github.com/saimoulichalla](https://github.com/saimoulichalla)

---

<p align="center">Built with React ⚛️ | Automated with GitHub Actions 🤖 | Bundled with Vite ⚡</p>
