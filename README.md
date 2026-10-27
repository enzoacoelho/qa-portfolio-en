# Quality Engineering Portfolio

[![Postman](https://img.shields.io/badge/Postman-API_Testing-FF6C37?logo=postman&logoColor=white)](https://github.com/enzoacoelho)
[![Cypress](https://img.shields.io/badge/Cypress-E2E-04C38E?logo=cypress&logoColor=white)](https://github.com/enzoacoelho)
[![Playwright](https://img.shields.io/badge/Playwright-E2E-2EAD33?logo=playwright&logoColor=white)](https://github.com/enzoacoelho)
[![Jest](https://img.shields.io/badge/Jest-Unit_Testing-C21325?logo=jest&logoColor=white)](https://github.com/enzoacoelho)
[![Supertest](https://img.shields.io/badge/Supertest-API_Testing-150458?logo=node.js&logoColor=white)](https://github.com/enzoacoelho)
[![Appium](https://img.shields.io/badge/Appium-Mobile-662D91?logo=appium&logoColor=white)](https://github.com/enzoacoelho)
[![Robot Framework](https://img.shields.io/badge/Robot_Framework-Automation-000000?logo=robotframework&logoColor=white)](https://github.com/enzoacoelho)
[![k6](https://img.shields.io/badge/k6-Performance-7D64FF?logo=k6&logoColor=white)](https://github.com/enzoacoelho)
[![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?logo=docker&logoColor=white)](https://github.com/enzoacoelho)
[![Jira](https://img.shields.io/badge/Jira-Agile_Management-0052CC?logo=jira&logoColor=white)](https://github.com/enzoacoelho)
[![Zephyr Scale](https://img.shields.io/badge/Zephyr_Scale-Test_Management-F26522?logo=jira&logoColor=white)](https://github.com/enzoacoelho)
[![GitHub Actions](https://img.shields.io/badge/CI-GitHub_Actions-2088FF?logo=githubactions&logoColor=white)](https://github.com/enzoacoelho)

💡 From developer to QA: combining a code-level perspective with an analytical testing mindset.

## About me

4 years as a developer, now transitioning into QA — I bring technical experience that goes well beyond test execution.

I use that background to read code in depth and talk with dev teams as a peer. Here you will find my hands-on projects in manual testing, automation, and continuous integration.

## Portfolio goals

- Demonstrate my hands-on experience in software quality
- Showcase projects developed throughout my studies
- Show the application of best practices in testing, automation, and organization
- Highlight my ability to analyze context, define strategy, and make technical decisions

## Stack

| Category | Tools |
|---|---|
| Web (E2E) | Cypress, Playwright |
| API | Cypress, Playwright, Postman |
| Mobile | Appium, WebDriverIO, Robot Framework |
| Performance | k6, Artillery |
| Unit testing | Jest, Supertest |
| CI/CD & Containers | GitHub Actions, Docker |
| Manual test management | Jira Cloud, Zephyr Scale |

## Highlights

Projects that best represent how I think about test strategy, not just execution:

- **[`Manual Testing - (Tool Shop)`](https://github.com/enzoacoelho/qa-manual-toolshop)** — Manual and exploratory testing on a tool e-commerce site. I focused on risk analysis and edge cases in the checkout flow, building a traceability matrix, test cycles, and bug reports with visual evidence. (Jira and Zephyr)
- **[`Automated API Tests - Reading Hub (Cypress)`](https://github.com/enzoacoelho/cy-api-hub-de-leitura)** — API automation (Cypress) for a library system. Strong focus on business rules and role-based permission validation (authorization), with Allure reports integrated via CI/CD on GitHub Actions.
- **[`Automated Web E2E Tests - Streaming (Playwright)`](https://github.com/enzoacoelho/pw-streaming.git)** — E2E test automation with Playwright and JavaScript on a streaming web application, covering functional tests for the login, leads, and catalog flows, plus automated test scenarios.

> The individual READMEs of these three projects provide full context, test strategy, and evidence.

## Projects

Projects developed throughout my studies, organized by category.

### 1. Manual Testing and Strategy
- [`qa-manual-toolshop`](https://github.com/enzoacoelho/qa-manual-toolshop) — Suite of manual, functional, and exploratory tests and edge-case scenarios for the "Practice Software Testing - Tool Shop" web application, structured with a traceability matrix, execution cycles, and defect (bug) reports.
- [`qa-manual-agileway-travel`](https://github.com/enzoacoelho/qa-manual-agileway-travel) — Suite of manual, functional, and exploratory tests and edge-case scenarios for AgileWay's travel booking ecosystem, managed with cycle planning and structured defect reporting.

### 2. Web Automation
- [`cy-realworld-app`](https://github.com/enzoacoelho/cy-realworldapp) — Peer-to-peer payments app *(highlighted above)*
- [`pw-streaming`](https://github.com/enzoacoelho/pw-streaming) — E2E with Playwright on a streaming platform (login, leads, catalog), with PostgreSQL integration.

### 3. Mobile Automation
- [`appium-wdio`](https://github.com/enzoacoelho/appium-wdio) — Android automation with Appium + WebDriverIO on WebdriverIO's official sample app (puzzles/quiz).
- [`appium-robot-yodapp`](https://github.com/enzoacoelho/appium-robot-yodapp) — Mobile automation with Robot Framework on a task management app.

### 4. API Automation
- [`postman-serverest-usuarios`](https://github.com/enzoacoelho/postman-serverest-usuarios) — Postman API test suite for user management on ServeRest. Includes business rule validations, negative scenarios (duplicate email, non-existent ID), and dynamic ID chaining using collection variables.
- [`cy-api-hub-de-leitura`](https://github.com/enzoacoelho/cy-api-hub-de-leitura) — Library system with role-based permissions *(highlighted above)*

### 5. Unit Testing (Jest)
- [`jest-viacep`](https://github.com/enzoacoelho/jest-viacep) — Function that looks up an address by postal code (CEP) using the public ViaCEP API, with 16 unit tests and 100% coverage. `fetch` is mocked with `jest.fn()` to simulate the API being down, network failure, and a malformed response. It also covers input edge cases (CEP with hyphen, dot, spaces, number, empty, letters, and extra digits) and uses `test.each`.
- [`jest-api`](https://github.com/enzoacoelho/jest-usuarios-api) — REST API for users built with Express, tested with Jest and Supertest: 26 tests and roughly 98% coverage. Validates business rules (legal age, email, active user, and unique email), status codes (201, 400, 404, 409, 204), malformed JSON, and the full cycle of creating, listing, retrieving, and deleting users.

### 6. Performance Testing
- [`k6-tests`](https://github.com/enzoacoelho/k6-tests) — Load scripts with k6, including analysis of latency, error rate, and throughput.

### 7. DevOps and Test Infrastructure (CI/CD & Containers)
- [`cy-interception-docker`](https://github.com/enzoacoelho/cy-interception-docker) — Headless Cypress tests in Docker containers, ensuring a reproducible environment.

## Best practices adopted

The projects were structured around risk-based scenario mapping to guide both manual and automated testing. In automation, I applied Page Objects, custom commands, and centralized requests to avoid code duplication, managing test data with fixtures and Faker. Execution was integrated with Allure reports and performance tools to ensure visibility into the results.
