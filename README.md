## FreelanceHub

FreelanceHub is my second project that I've been able to implement on GitHub as part of my studies. It is a comprehensive solution for managing and mediating freelancer jobs, developed with modern web technologies. The project integrates advanced features such as user management, role-based access controls, frontend enhancements, end-to-end testing, and much more to create a user-friendly and secure platform for freelancers and clients.

### Features

- **User Management and Authentication**: Supported by Auth0, it allows secure login, registration, and management of user accounts.
- **Role-Based Access Control**: Enables differentiated access rights for freelancers, clients, and administrators.
- **Frontend Enhancements with Svelte**: Modern and reactive user interface that provides intuitive navigation and interaction.
- **Pagination and Filtering**: Efficient presentation and search of jobs through advanced filter options and page-by-page display.
- **End-to-End Testing with Cypress**: Ensures high quality and reliability through automated tests.
- **Email Validation and Sending**: Verification of email addresses and notification functions for user actions.
- **Integration of Third-Party Systems**: Integration of external services like ChatGPT for generating job descriptions.
- **Service Testing**: Comprehensive backend tests to ensure the reliability and security of the system.

### Technologies

- **Frontend**: Svelte, Bootstrap
- **Backend**: Spring Boot, MongoDB
- **Authentication**: Auth0
- **Testing**: Cypress, Spring Security Test
- **APIs**: Disify (Email Validation), SMTP (Email Sending), OpenAI (ChatGPT)

### Quick Start

1. **Prerequisites**: Install Node.js, npm, and MongoDB on your system.

2. **Clone the project**:

```bash
git clone https://github.com/YourGitHubUsername/FreelanceHub.git
cd FreelanceHub
```

3. **Set up the frontend**:

```bash
cd frontend
npm install
npm run dev
```

4. **Set up the backend**:

```bash
cd backend
./mvnw spring-boot:run
```

5. **Access**: Open `http://localhost:8080` in your browser.
