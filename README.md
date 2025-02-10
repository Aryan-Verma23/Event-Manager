# 📅 College Event Manager

A web-based event management platform for college clubs to create, manage, and promote multiple events efficiently. It includes role-based access for admins and students, email notifications, event registration, and live event tracking.

## 🚀 Features

- Role-Based Access: Admins can create and manage events, while students can register and participate.
- Email Notifications: Automatic emails for event reminders, updates, and confirmations.
- Upcoming Events: Displays all scheduled events with registration options.
- Live Events: Show ongoing events in real time.
- Event Registration: Easy sign-up process for students with confirmation emails.
- User-Friendly Dashboard: Separate interfaces for admins and students.
- Event Categories: Supports various types of events like workshops, hackathons, and cultural fests.

## 📂 Project Structure

--
event-manager/
│── backend/                # Backend API (Spring Boot)
│   ├── src/main/java/com/eventmanager/
│   │   ├── controller/     # REST Controllers
│   │   ├── model/          # Entity Classes
│   │   ├── repository/     # Database Repositories
│   │   ├── service/        # Business Logic Services
│   ├── resources/
│   │   ├── application.properties  # Configurations (DB, email, etc.)
│   ├── pom.xml             # Maven Dependencies
│── frontend/               # Frontend UI (React or any other)
│   ├── public/             # Static assets
│   ├── src/
│   │   ├── components/     # UI Components
│   │   ├── pages/          # Pages (Home, Events, Dashboard)
│   │   ├── services/       # API Calls
│   ├── package.json        # Dependencies
│── figma-design/           # Figma Design Files
│── README.md               # Project Documentation
--

## 🛠️ Tech Stack

### Backend:
- Java (Spring Boot) – Handles business logic and APIs
- MySQL – Stores user and event data
- Spring Security – Authentication and role-based access
- Lombok & Hibernate – For reducing boilerplate code
- JavaMailSender – Sends email notifications

### Frontend:
Using Figma -
🏠 Home Page (Shows upcoming & live events)
📅 Events Page (Detailed list of all events with registration options)
🛠️ Admin Dashboard (Create & manage events, send notifications)
👤 User Dashboard (Registered events, past events, notifications)
🔑 Login/Register Page (User authentication)

### Deployment:
- AWS EC2/S3 – Hosts the backend & frontend
- AWS RDS – MySQL database
- AWS SES – Email service for notifications

### 1️⃣ Backend Setup

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

### 2️⃣ Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

## 📧 Contact

For any queries, reach out to [aryan9.verma09@gmail.com]
