# Medtrick-Smart-Health-Management-System

MediTrack is a comprehensive, role-based digital health system designed to streamline the management of patients, healthcare providers, appointments, and medical records. Built with a modern tech stack, it provides a secure and efficient platform for various clinical and administrative workflows.

This project was developed by:
*   **Mr. Stanley S Garyeazohn** – Project Head/Lead: `23ss02it253`
*   **Mr. Emmanuel Opa Payne** – Member: `23ss02it247`
*   **Mr. George S. Teaman** – Member: `23ss02it251`

---

## ✨ Key Features

MediTrack is built around a powerful role-based access control (RBAC) system, providing a unique and tailored experience for each user type.

#### 👩‍⚕️ **Admin Portal**
*   **Analytics Dashboard:** View high-level statistics like total users, patients, doctors, and pending appointments.
*   **Staff Enrollment:** Securely create new system accounts for Doctors, Receptionists, Lab Technicians, and other Admins.
*   **User Management:** View a list of all registered users and delete accounts from the system.
*   **Doctor Management:** Full CRUD (Create, Read, Update, Delete) capabilities for doctor profiles.

#### 🧑‍💼 **Receptionist Portal**
*   **Patient Registration:** Register new patients, which automatically creates their login credentials and a patient profile.
*   **Master Schedule:** View a master list of all appointments in the system.
*   **Appointment Management:** Schedule new appointments directly, approve or deny patient-requested appointments, and mark appointments as "Completed" or "Cancelled".
*   **Doctor Assignment:** Assign and re-assign doctors to patients.
*   **Vitals Recording:** Record patient vital signs during check-in.

#### 🧑‍⚕️ **Doctor Portal**
*   **Personalized Dashboard:** View a list of upcoming appointments for the day and a list of currently assigned patients.
*   **Patient Profile Hub:** Access a complete clinical view for each patient, including their details, vitals history, medical history, and lab results.
*   **Clinical Notes:** Create and view medical records, diagnoses, and prescriptions for patients.
*   **Lab Test Workflow:** Request new lab tests for patients and receive real-time notifications when results are ready.

#### 🧑‍🔬 **Lab Technician Portal**
*   **Pending Requests Queue:** View a real-time list of all pending lab test requests from doctors.
*   **Fulfill Requests:** View request details, enter test results, and mark requests as "Completed".
*   **Automated Notifications:** Automatically notifies the requesting doctor when results are submitted.

#### 👨‍👩‍👧 **Patient Portal**
*   **Personal Dashboard:** View upcoming appointments and recent medical history at a glance.
*   **Appointment Management:** Request new appointments with a preferred doctor and request to cancel upcoming appointments.
*   **Full Medical History:** View a complete, read-only history of all clinical notes, vitals, and lab results.
*   **Real-Time Notifications:** Receive notifications when an appointment is confirmed or a cancellation is approved.

---

## 🛠️ Technology Stack

This project leverages a modern, full-stack JavaScript architecture.

*   **Frontend:** [**Next.js**](https://nextjs.org/) (with Pages Router) & [**React**](https://reactjs.org/)
*   **Styling:** [**Tailwind CSS**](https://tailwindcss.com/) for utility-first styling and a responsive design.
*   **Language:** [**TypeScript**](https://www.typescriptlang.org/) for type safety and scalability.
*   **Backend & API:** [**Next.js API Routes**](https://nextjs.org/docs/api-routes/introduction) running in a serverless environment.
*   **Authentication:** [**Firebase Authentication**](https://firebase.google.com/docs/auth) for secure user management.
*   **Database:** [**Firestore**](https://firebase.google.com/docs/firestore) (a NoSQL, document-based database) for all application data.
*   **Admin Privileges:** [**Firebase Admin SDK**](https://firebase.google.com/docs/admin/setup) for secure server-side actions like creating and deleting users.
