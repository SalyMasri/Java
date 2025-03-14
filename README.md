# 🍽️ Antons Skafferi - Full Stack Development Project

## 📌 Project Overview
**Antons Skafferi** is a **Jakarta EE-based** system designed to modernize restaurant operations by improving staff communication, streamlining order management, and enhancing the restaurant’s online presence.

The project includes:
- 🌐 **Customer Website** – Displays menus, events, and a booking system.
- 🔧 **Admin Dashboard** – Manages restaurant operations, staff schedules, and menu updates.
- 📱 **Restaurant App** – Mobile app for waitstaff to take and manage orders.
- 🍳 **Kitchen App** – Mobile app for kitchen staff to track and update order statuses.

## 🛠️ Technologies & Tools Used
- **Backend & API:** Jakarta EE, JPA, RESTful API, Payara Server, GlassFish
- **Frontend:** XHTML, JavaServer Faces (JSF), HTML/CSS, JavaScript
- **Mobile Apps:** Android Studio, Retrofit (REST API integration)
- **Database:** MariaDB, XAMPP, phpMyAdmin
- **Development & Collaboration:** IntelliJ IDEA, GitHub, Trello, Discord
- **Version Control:** GitHub repositories for modular project development
- **Project Management:** Agile (Scrum, XP), task tracking via Trello

## 📂 Project Structure
### 🌍 **Website**
- Displays **daily menus**, **à la carte options**, and **event listings**.
- **Reservation system** for customers.
- Responsive UI with **dynamic content updates** from the database.

### 🔧 **Admin Dashboard**
- CRUD operations for **menus, events, and employee schedules**.
- JSF-based UI with **database integration**.

### 📱 **Restaurant App**
- Order management system for waitstaff.
- **Color-coded table statuses** (🟢 Available, 🔴 Occupied).
- Uses **Retrofit** to communicate with the backend API.

### 🍳 **Kitchen App**
- Displays **real-time orders** sent from the waitstaff.
- **Checkbox system** to mark orders as completed.
- Uses a **REST API** to fetch and update data dynamically.

## ✅ Final Results
✔️ Fully functional **customer website** with real-time menu updates.  
✔️ A working **admin dashboard** for managing menus, staff schedules, and events.  
✔️ **Restaurant app** for seamless order management and table tracking.  
✔️ **Kitchen app** for tracking and updating meal preparation statuses.  
✔️ **REST API** integration for data communication between mobile and web apps.

## 🚀 Future Improvements
- 🕒 **Employee Scheduling App** – A dedicated mobile app for shift management.
- ⚡ **Enhanced Real-time Sync** – Improve automatic updates between apps and API.
- 🎨 **UI/UX Refinements** – Enhance admin dashboard styling and navigation.
- 🔄 **Auto-refresh for Orders** – Eliminate the need for manual updates.

## 💾 How to Run the Project
1. **Clone the repositories** from GitHub:
   - 📂 [Website Repository](https://github.com/ybond93/Website)
   - 📂 [Restaurant Application Repository](https://github.com/ybond93/Application_Restaurant)
   - 📂 [Kitchen Application Repository](https://github.com/ybond93/Application_Kitchen)
2. **Set up the database** using MariaDB with the provided DDL scripts.
3. **Deploy the backend** using **Payara Server** or **GlassFish**.
4. **Run the frontend** using **IntelliJ IDEA** (for web apps) and **Android Studio** (for mobile apps).
5. **Use REST API endpoints** for seamless communication between frontend and backend.

## 👥 Team Members
| Name  | Responsibilities |
|--------|------------------------------------|
| **Arvid**  | Database, Admin Page, Restaurant App API |
| **Jakob**  | Database, Web Server, DTOs |
| **Luwam**  | Website Validation, Admin UI, Java Classes |
| **Saly**  | UI Design, Restaurant App Development |
| **Yasan**  | API Development, DTOs, Retrofit, Kitchen App |

---

📢 **For any issues or contributions, please create a pull request or issue in the respective repository.**  
🚀 **Happy coding!**
