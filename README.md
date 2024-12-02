# **Hospital Management System**

## **Project Description**
The **Hospital Management System** is a comprehensive full-stack web application developed using the **MEAN (MongoDB, Express, Angular, Node.js)** stack. This system streamlines hospital operations, including patient management, doctor schedules, appointment bookings, and role-based user access. It is designed to improve efficiency and organization in healthcare facilities.

---

## **Features**
### **Admin Features**
- Manage doctors (add, edit, delete).
- Manage patients (add, edit, delete).
- View and manage appointments.
- Generate activity reports.

### **Doctor Features**
- View assigned patients and appointments.
- Update patient diagnoses and medical history.
- Manage work schedules.

### **Patient Features**
- Register and book appointments.
- View appointment status and history.
- Access personal medical records.

---

## **Tech Stack**
- **Frontend**: Angular, AdminLTE for UI styling.
- **Backend**: Node.js, Express.
- **Database**: MongoDB with Mongoose ORM.
- **Authentication**: JSON Web Tokens (JWT).

---

## **Installation and Setup**

### **Prerequisites**
- Node.js (v16 or higher).
- MongoDB (local or cloud-based, e.g., MongoDB Atlas).
- Angular CLI.

### **Backend Setup**
1. Clone the backend repository:
   ```bash
   git clone https://github.com/Juniorbarry26/Hospital-Management-System
   cd hospital-management-backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file and configure:
   ```env
   PORT=3000
   MONGO_URI=<your_mongo_uri>
   JWT_SECRET=<your_secret_key>
   ```
4. Start the server:
   ```bash
   node app.js
   ```

### **Frontend Setup**
1. Clone the frontend repository:
   ```bash
   git clone https://github.com/Juniorbarry26/Hospital-Management-System
   cd hospital-management-system
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the Angular development server:
   ```bash
   ng serve
   ```

---

## **Usage**
1. Open the frontend in your browser at [http://localhost:4200](http://localhost:4200).
2. Use the following default credentials for testing:
   - Admin: `admin@example.com` / `password`
   - Doctor: `doctor@example.com` / `password`
   - Patient: `patient@example.com` / `password`

---

## **Project Structure**
### **Backend**
```
hospital-management-backend/
├── controllers/
├── routes/
├── models/
├── middlewares/
├── app.js
├── package.json
└── .env
```

### **Frontend**
```
hospital-management-frontend/
├── src/
    ├── app/
    │   ├── components/
    │   ├── services/
    │   ├── models/
    ├── assets/
    ├── environments/
└── angular.json
```

---

## **Contributors**
- **Alsainey Barry** – *Junior Software Engineer*
- **Abdoulie Jallow** *Full Stack Developer*
