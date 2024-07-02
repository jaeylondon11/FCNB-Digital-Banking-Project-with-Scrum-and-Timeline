# Business Process Models

## Project Title: FCNB Digital Banking Project with Scrum and Timeline

### Overview
The Business Process Models for the FCNB Digital Banking Project provide a visual representation of the workflows and processes involved in the enhanced digital banking services. These models help in understanding, analyzing, and improving business processes to ensure efficient and effective service delivery.

### Key Business Processes

#### 1. User Registration and Authentication

**Description:**
This process involves the steps required for a user to register and authenticate themselves in the FCNB digital banking system.

**Steps:**
1. **User Registration:**
   - User accesses the registration page.
   - User provides personal information (name, email, phone number, etc.).
   - System validates the information.
   - System creates a new user account.
   - User receives a confirmation email/SMS.

2. **User Authentication:**
   - User accesses the login page.
   - User enters username and password.
   - System verifies credentials.
   - System generates a JWT token for the session.
   - User is granted access to their account.

**Flowchart:**

```mermaid
graph TD
    A[Access Registration Page] --> B[Provide Personal Information]
    B --> C[Validate Information]
    C --> D[Create New User Account]
    D --> E[Send Confirmation Email/SMS]
    E --> F[User Registered]

    G[Access Login Page] --> H[Enter Username and Password]
    H --> I[Verify Credentials]
    I --> J[Generate JWT Token]
    J --> K[Grant Access to Account]
