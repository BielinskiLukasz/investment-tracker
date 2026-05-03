# Investment Tracker — Backend

![Status](https://img.shields.io/badge/status-concept-lightgrey)
![Version](https://img.shields.io/badge/version-0.0.0-blue)

A Java/Spring Boot backend application for managing investment activity and financial history.  
It provides a clean REST API for recording transactions, tracking portfolio performance, and generating financial reports.

---

## ⚠️ Project Status / Disclaimer

This project is currently in the **concept phase**.  
The codebase is **highly experimental**, **incomplete**, and **not functional yet**.

- No features are fully implemented  
- API endpoints are placeholders  
- No stable release exists  
- Architecture and domain model are still being designed  
- Breaking changes will occur frequently  

This repository currently serves as a **technical sandbox** for exploring backend design ideas.

---

## 📘 Overview

InvestmentTracker enables users to:

- Log investment transactions (stocks, ETFs, funds, crypto, etc.)
- Track profits, losses and ROI over time
- Generate detailed portfolio summaries and reports
- Perform basic budgeting and financial planning

The backend is built with **Spring Boot** and uses an **H2 in‑memory database** for development and testing.  
It is designed with scalability in mind and can be easily extended with additional modules or external integrations.

---

## 🏗️ Architecture (Placeholder)

A detailed architecture description will be added later.

Planned structure outline:

```
src/main/java/com.example.investmenttracker
 ├── controller        # REST endpoints (planned)
 ├── service           # Business logic (planned)
 ├── repository        # Data access layer (planned)
 ├── model             # Domain entities (planned)
 └── InvestmentTrackerApplication.java
```

More details will be added once the domain model and API stabilize.

---

## 📡 Planned API Endpoints (Placeholder)

The API is not implemented yet.  
Below is the **planned** structure:

### Transactions
- `POST /transactions` — create a new transaction  
- `GET /transactions` — list all transactions  
- `GET /transactions/{id}` — get transaction details  

### Portfolio
- `GET /portfolio` — portfolio summary  
- `GET /portfolio/performance` — ROI, P/L, trends  

### Reports
- `GET /reports/summary`  
- `GET /reports/annual`  

Full OpenAPI/Swagger documentation will be added later.

---

## 🚀 Features

- **Transaction Management**  
  Create, update and store investment transactions.

- **Portfolio Tracking**  
  Monitor performance metrics such as ROI, profit/loss and asset distribution.

- **Financial Reporting**  
  Generate summaries and detailed reports of your investment history.

- **Lightweight Storage**  
  Uses H2 for quick setup and local development.

---

## 🛠️ Roadmap (Placeholder)

Planned development milestones:

- **v0.1.0** — Basic project structure, empty endpoints  
- **v0.2.0** — Domain model + initial services  
- **v0.3.0** — First working transaction flow  
- **v0.4.0** — Portfolio calculations  
- **v0.5.0** — Reporting module  
- **v1.0.0** — First stable release  

---

## 🧪 Development Notes

Since the project is in a very early stage, the following elements are **not implemented at all**:

- No validation  
- No error handling  
- No business logic  
- No persistence beyond H2 defaults  
- No authentication or authorization  
- No tests  
- No DTO mapping  
- No API documentation  

This section will expand as the project matures.

---

## 🧰 Technologies Used

- **Java 17+**
- **Spring Boot**
- **Spring Web / REST**
- **H2 Database**
- **Maven**

---

## 📦 Installation

### Prerequisites
- Java **17+**
- Maven **3.8+**

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/BielinskiLukasz/investment-tracker.git
   cd InvestmentTracker-Backend
   ```
2. Build the project using Maven:
   ```bash
   mvn clean install
   ```
3. Run the application:
   ```bash
   java -jar target/investment-tracker-backend-0.0.1-SNAPSHOT.jar
   ```

### Run in Development Mode (Placeholder)

Planned dev workflow:

```bash
mvn spring-boot:run
```

Additional dev tools (e.g., Docker, Testcontainers) may be added later.

---

## 🐞 Known Issues

Since the project is not functional yet, **almost nothing works**.

Current limitations:

- No endpoints return meaningful data  
- No calculations are implemented  
- No persistence beyond in-memory defaults  
- No error handling  
- No validation  
- No tests  
- No security  
- No configuration profiles  

This section will be updated as features appear.

---

## 📄 Release & Versioning (Placeholder)

There are **no releases** at this stage.

Planned versioning strategy:

- Semantic Versioning (SemVer)
- Pre‑release tags (`-alpha`, `-beta`) before v1.0.0
- GitHub Releases once the project becomes functional

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repository and submit a pull request.  
Please ensure your changes are well‑tested and follow clean coding practices.

---

## 📄 License

This project is licensed under the **MIT License**.  
See the `LICENSE` file for details.

---

For questions or issues, contact: **l.p.bielinski@gmail.com**
