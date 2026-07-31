# 🐍 Python Playwright Async Framework

### Modern Asynchronous End-to-End Automation with Playwright & pytest

![Python](https://img.shields.io/badge/Python-3.12%20|%203.13-3776AB?style=flat&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-Async-2CA5E0?style=flat&logo=playwright&logoColor=white)
![GitHub Actions](https://img.shields.io/github/actions/workflow/status/jerryfinol17/Python-Playwright-Async-Framework/main.yml?style=for-the-badge&label=CI&logo=github-actions&logoColor=white)

---

## About the Project

This repository showcases how I build modern asynchronous automation frameworks using **Python**, **Playwright**, and **pytest**.

Rather than simply automating user interactions, the goal was to design a framework that remains scalable, maintainable, and production-ready while taking full advantage of Python's asynchronous capabilities.

The framework automates the complete SauceDemo customer journey, demonstrating how asynchronous execution can improve performance without sacrificing readability.

---

## Why I Built It

Playwright's asynchronous API offers significant performance advantages when used correctly.

This project was built to explore those capabilities while maintaining clean architecture, reusable components, and reliable end-to-end automation.

Rather than treating asynchronous programming as an optimization, the framework embraces it as part of its overall design.

---

## Highlights

- Fully asynchronous implementation using `playwright.async_api`
- Production-ready Page Object Model architecture
- Reusable BasePage class
- Complete end-to-end customer journeys
- Strategic code coverage
- Smart flakiness handling with `pytest.mark.xfail`
- Automatic screenshots and video recording
- Parallel execution with `pytest-xdist`
- GitHub Actions CI/CD
- Cross-browser support
- Scalable folder organization

---

## What This Framework Covers

The automation validates complete business workflows including:

- Login
- Inventory
- Product selection
- Shopping cart
- Checkout
- Order confirmation
- Known edge cases
- Error handling

Rather than validating isolated pages, the framework reproduces realistic customer journeys from beginning to end.

---

## Repository Structure

```text
.
├── pages/
├── tests/
├── screenshots/
├── videos/
├── .github/
├── pytest.ini
└── requirements.txt
```

A detailed explanation of the framework architecture and engineering decisions is available in **ARCHITECTURE.md**.

---

## Running the Project

Clone the repository:

```bash
git clone https://github.com/jerryfinol17/Python-Playwright-Saucedemo-Pom-Framework.git

cd Python-Playwright-Saucedemo-Pom-Framework
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Install Playwright browsers:

```bash
playwright install --with-deps
```

Run the complete test suite:

```bash
pytest -n auto
```

Generate the coverage report:

```bash
pytest --cov=pages --cov-report=html
```

---

## Continuous Validation

Quality shouldn't only be verified when new code is written.

GitHub Actions continuously executes the framework to ensure compatibility across supported Python versions while validating the automation suite as dependencies continue evolving.

Software evolves.

Automation should evolve with it.

---

## Why This Repository Matters

This project demonstrates more than Python syntax.

It reflects my approach to automation engineering:

- Async-first architecture
- Maintainable Page Objects
- Clean code organization
- Reliable automation
- Production-ready engineering practices

Because good automation isn't just fast.

It should also be understandable, maintainable, and trustworthy.

---

## Technical Documentation

This repository includes a dedicated engineering document covering:

- Architecture decisions
- Async implementation
- Page Object Model
- Fixtures
- Reporting
- CI/CD
- Lessons learned

📖 **Read the full documentation:** `ARCHITECTURE.md`

---

## Looking for a Custom Automation Framework?

I help startups and software teams build reliable automation solutions through:

- Playwright (Python & TypeScript)
- Selenium
- API Testing
- CI/CD Integration
- Automation Framework Design
- Analytical Testing
- UX-Oriented QA Reviews

---
## Let's Connect

<p align="center">

<a href="mailto:jerrytest124@gmail.com">📧 Email</a> •
<a href="https://linkedin.com/in/jerry-finol">💼 LinkedIn</a> •
<a href="https://jerryfinol17.github.io/JerryFinolQA/">🌐 Portfolio</a>

<br><br>

<a href="https://x.com/JerryFinolQA">𝕏 X</a> •
<a href="https://www.reddit.com/user/Jerry_Finol17/">👽 Reddit</a> •
<a href="https://www.instagram.com/jerryfinolqa/">📷 Instagram</a>
<a href="https://www.facebook.com/JerryFinolQA">📘 Facebook</a>
---

> **Understand first. Test second. Explain always.**





