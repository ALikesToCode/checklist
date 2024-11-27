### **General Setup**
- [ ] Install Flask, Jinja2, Bootstrap, and SQLite.
- [ ] Set up a local development environment for the application.
- [ ] Create a Git repository for version control.

---

### **Database**
- [ ] Design and implement the database schema.
  - Tables for **Admin**, **Customer**, **Service Professional**, **Service**, **Service Request**.
- [ ] Ensure proper relationships between tables (e.g., foreign keys for `service_id`, `customer_id`, `professional_id`).
- [ ] Create an **ER Diagram** for submission.

---

### **User Roles and Functionality**
#### **Admin**
- [ ] Admin login system with root access.
- [ ] Admin Dashboard with:
  - [ ] View and manage all users (customers and service professionals).
  - [ ] Approve service professionals after document verification.
  - [ ] Block/Unblock users based on reviews or activity.
- [ ] Service Management:
  - [ ] Add new services with base price and details.
  - [ ] Update existing services.
  - [ ] Delete services.

#### **Service Professional**
- [ ] Login/Registration system.
- [ ] Profile with:
  - [ ] ID, name, description, service type, experience, reviews.
- [ ] Accept/Reject assigned service requests.
- [ ] Mark a service request as "Completed."
- [ ] Exit the location after service is closed.

#### **Customer**
- [ ] Login/Registration system.
- [ ] Search services by:
  - [ ] Name.
  - [ ] Location.
  - [ ] Pin code.
- [ ] Create a service request.
- [ ] Edit or update a service request.
- [ ] Close a service request after completion.
- [ ] Provide reviews/remarks for completed services.

---

### **Application Core Functionalities**
- [ ] **Login/Register Forms**:
  - [ ] Separate forms for Admin, Customer, Service Professional.
  - [ ] Optional: Use `flask_login` or `flask_security` for secure login.
- [ ] **Service Management**:
  - [ ] CRUD operations for services (Create, Read, Update, Delete).
- [ ] **Service Requests**:
  - [ ] CRUD operations for service requests.
  - [ ] Status updates (e.g., requested, assigned, closed).
- [ ] **Search Functionality**:
  - [ ] Search for services by location or name.
  - [ ] Admin search for professionals to manage (block/unblock/review).

---

### **Recommended Features**
- [ ] **API Resources**:
  - [ ] Create APIs for:
    - User operations.
    - Service CRUD.
    - Service request operations.
  - [ ] Use `flask_restful` or return JSON directly.
- [ ] **Frontend Validation**:
  - [ ] Validate all forms with HTML5 or JavaScript.
- [ ] **Backend Validation**:
  - [ ] Add validation logic in controllers for secure input.
- [ ] **Data Visualization**:
  - [ ] Use `ChartJS` or similar libraries for:
    - Service professional reviews.
    - Service request status distribution.

---

### **Optional Features**
- [ ] **Styling**:
  - [ ] Use CSS/Bootstrap for a responsive and aesthetic UI.
- [ ] **Login System**:
  - [ ] Implement a secure login system with `flask_login` or `flask_security`.
- [ ] **Dummy Payment Portal**:
  - [ ] Create a dummy view for payment handling.
- [ ] Any additional feature you think will improve usability.

---

### **Submission Requirements**
- [ ] **Code Submission**:
  - [ ] Include all project files in a single zip file.
- [ ] **Project Report**:
  - [ ] **Student Details.**
  - [ ] **Project Details**:
    - Problem statement.
    - Approach to solving the problem.
    - Frameworks and libraries used.
  - [ ] **ER Diagram** of the database.
  - [ ] **API Endpoints** (if any).
  - [ ] Include the video link in the report.
- [ ] **Video Presentation**:
  - [ ] 5-10 minute video explaining the approach and implemented features.
  - [ ] Drive link with unrestricted access.
- [ ] **Live Demo**:
  - [ ] Be prepared for a live demo with code changes if requested.

---

### **Testing**
- [ ] Test the application for all roles (Admin, Customer, Professional).
- [ ] Test core functionalities (CRUD operations, login/register, search).
- [ ] Test the UI for responsiveness and usability.
- [ ] Test API endpoints (if implemented) using tools like Postman.
