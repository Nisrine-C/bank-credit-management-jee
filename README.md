# Bank Credit Management JEE Application

This is a Java EE (JEE) application for managing bank clients, credits (loans), and repayments. Developed as an academic project, it demonstrates modern Java EE architecture and concepts including entity management, REST APIs, and a layered structure.

## Features

- Client creation and management
- Loan management (multiple credit types: immobilier, personnel, professionnel)
- Repayment (remboursement) schedules and tracking
- Credit status tracking (request, acceptance, etc.)
- Secure access with role-based permissions

## Architecture & Technologies

- **Backend:** Java EE  (JPA, Servlets, JDBC)
- **Database:** (Specify your DB: MySQL, PostgreSQL, etc.)
- **Build Tool:** Maven
- **REST API:** Provided for client, credit, and repayment operations

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Nisrine-C/bank-credit-management-jee.git
   cd bank-credit-management-jee
   ```
2. **Configure your database** settings in the resources or persistence config.
3. **Build the project** using Maven:
   ```bash
   mvn clean install
   ```
4. **Deploy the WAR file** to a Java EE server (e.g., Tomcat, GlassFish).

## Usage

- Access the web interface or REST endpoints as documented.
- Add clients, create and approve credits, record repayments.

## License

Educational/Academic use.
