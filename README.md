# InvestmentTracker — Backend

A Java/Spring Boot backend application for managing investment activity and financial history.  
It provides a clean REST API for recording transactions, tracking portfolio performance, and generating financial reports.

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

## 🛠️ Planned Enhancements

- Integration with external market data APIs  
- Notification system for portfolio changes  
- Advanced analytics and trend forecasting  
- Migration to a production‑grade database (e.g., PostgreSQL)

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

### Default Configuration
The application uses an embedded H2 database.  
Connection settings can be found in: `src/main/resources/application.properties`

---

## 📡 Usage

The backend exposes a set of RESTful endpoints for managing investments.  
Full API documentation will be added in a future update.

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

