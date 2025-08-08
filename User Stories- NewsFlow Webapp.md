# User Stories for NewsFlow

---

## 1. Public User (Mobile App - Flutter)

### 1.1 Account Registration & OTP Verification  
**User Story:**  
As a new user, I want to register using my Google email and verify my account with an OTP, so that I can securely create a profile and access personalized content.

**Acceptance Criteria:**  
- ✅ A “Sign Up” option is available on the homepage.  
- ✅ The user enters their Google email address.  
- ✅ An OTP code is sent to the provided email.  
- ✅ The user enters the OTP to verify their identity.  
- ✅ The user provides profile details (username, password, etc.).  
- ✅ Upon completion, the account is created, and the user can log in using their email and password.

---

### 1.2 Login & Password Reset  
**User Story:**  
As a user, I want to securely log in and reset my password if I forget it, so that I can access my account from any device.

**Acceptance Criteria:**  
- ✅ A “Login” button is available on the homepage.  
- ✅ The user can log in using registered email and password.  
- ✅ The system displays an error message if credentials are incorrect.  
- ✅ A “Forgot Password” link is available on the login page.  
- ✅ Clicking the link sends a password reset email.  
- ✅ The reset email contains a secure, time-limited link.  
- ✅ The user can set and confirm a new password on the reset page.  
- ✅ A confirmation email is sent after a successful reset.

---

### 1.3 Home Page & Content Interaction  
**User Story:**  
As a user, I want to browse, filter, and interact with articles, so that I can find and engage with content I enjoy.

**Acceptance Criteria:**  
- ✅ The home page displays all articles after login.  
- ✅ The user can filter articles by selected category.  
- ✅ The user can like or unlike articles.  
- ✅ The user can view, post, or delete their own comments.  
- ✅ The user can share articles externally via social media or direct link.  
- ✅ The user can send feedback to the admin from each article.  
- ✅ The user can toggle between light and dark mode.  
- ✅ The user can choose a theme color, which is saved between sessions.  
- ✅ The user can select a preferred language (Arabic, English, French, Spanish, Italian).  
- ✅ The user can view their real-time location and current weather on screen.  
- ✅ The user can delete their account.  
- ✅ The user can log out at any time.

---

### 1.4 Profile Management  
**User Story:**  
As a user, I want to update my profile information, so that my account details remain accurate.

**Acceptance Criteria:**  
- ✅ The user can update their profile image.  
- ✅ The user can update their username.  
- ✅ The user can update their email address.  
- ✅ The user can update their password.

---

### 1.5 Notifications for New Articles  
**User Story:**  
As a user, I want to receive notifications when new articles are published, so that I can stay updated with the latest news.

**Acceptance Criteria:**  
- ✅ When an employee adds an article and the admin publishes it, a notification email is sent to all users.  
- ✅ The notification contains the article title and a short summary.  
- ✅ The user can enable or disable notifications in account settings.

---

## 2. Admin Panel (Website)

### 2.1 Admin Registration & Login  
**User Story:**  
As an admin, I want to register securely and log in to the dashboard, so that I can manage the platform.

**Acceptance Criteria:**  
- ✅ The admin sees a welcome page with a “Login” option as the default entry point.  
- ✅ The registration form is accessible only via a secure URL.  
- ✅ The admin can register using an email and password.  
- ✅ The admin can log in using registered credentials.  
- ✅ Invalid credentials display an error message.

---

### 2.2 Dashboard Overview  
**User Story:**  
As an admin, I want to view key statistics on the dashboard, so that I can monitor platform performance.

**Acceptance Criteria:**  
- ✅ The dashboard displays total articles.  
- ✅ The dashboard displays total categories.  
- ✅ The dashboard displays total employees.

---

### 2.3 Manage Employees  
**User Story:**  
As an admin, I want to manage employee accounts, so that I can control access to content creation.

**Acceptance Criteria:**  
- ✅ The admin can view all employees.  
- ✅ The admin can add new employees.  
- ✅ The admin can update employee details.  
- ✅ The admin can delete an employee account.

---

### 2.4 Manage Articles  
**User Story:**  
As an admin, I want to control article publishing, so that only approved content is visible to users.

**Acceptance Criteria:**  
- ✅ The admin can view all articles and article details.  
- ✅ The admin can delete articles.  
- ✅ The admin can publish or unpublish articles.

---

### 2.5 Manage Categories  
**User Story:**  
As an admin, I want to manage news categories, so that articles are organized for better user navigation.

**Acceptance Criteria:**  
- ✅ The admin can view all categories.  
- ✅ The admin can add new categories.  
- ✅ The admin can update category details.  
- ✅ The admin can delete categories.

---

### 2.6 View Action Logs  
**User Story:**  
As an admin, I want to view system activity logs, so that I can track changes made on the platform.

**Acceptance Criteria:**  
- ✅ Logs show the action performed, the user who performed it, and the timestamp.  
- ✅ Example log entry: “Admin added Employee X on 2025-08-01.”

---

### 2.7 Logout  
**User Story:**  
As an admin, I want to log out securely, so that my session is protected.

**Acceptance Criteria:**  
- ✅ A logout option is available in the dashboard.  
- ✅ Logging out ends the session immediately.

---

## 3. Employee Dashboard (Website)

### 3.1 Employee Access  
**User Story:**  
As an employee, I want to log in to my dashboard, so that I can create and manage articles.

**Acceptance Criteria:**  
- ✅ Employee accounts are created only by the admin.  
- ✅ The employee can log in using the provided email and password.

---

### 3.2 Employee Dashboard Overview  
**User Story:**  
As an employee, I want to view my work statistics, so that I can monitor my content creation activity.

**Acceptance Criteria:**  
- ✅ The dashboard displays the total number of categories.  
- ✅ The dashboard displays the number of articles created by the employee.

---

### 3.3 Article Management  
**User Story:**  
As an employee, I want to create, edit, and delete my own articles, so that I can manage my published content.

**Acceptance Criteria:**  
- ✅ The employee can add a new article with title, content, and images.  
- ✅ The employee can view a list of their own articles.  
- ✅ The employee can update or delete their own articles.

---

### 3.4 Publishing Workflow  
**User Story:**  
As an employee, I want my articles reviewed by the admin before publishing, so that quality standards are maintained.

**Acceptance Criteria:**  
- ✅ Articles are marked as “Pending” after submission.  
- ✅ The admin reviews and either approves or rejects the article.  
- ✅ Approved articles are published to all users.  
- ✅ After publishing, a notification email is sent to all users containing the article title and summary.

---
