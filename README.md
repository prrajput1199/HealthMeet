# 🏥 Full-Stack Healthcare Platform

This is a complete full-stack healthcare web application that enables patients to book appointments, consult doctors via video, manage medical records, and use a credit-based system. The system includes separate dashboards for Patients, Doctors, and Admins with full role-based access.

## 🚀 Demo

🎥 Watch the demo video here: [Click to Watch](https://www.youtube.com/watch?v=YOUR_VIDEO_LINK)

## 🌟 Features

### 👨‍⚕️ Multi-Role Dashboard System
- **Patient Dashboard**:
  - Book appointments with doctors.
  - View and manage upcoming and past appointments.
  - Access personal medical records.
  - Join video consultations using Vonage API.
  - View credits and transaction history.

- **Doctor Dashboard**:
  - Set availability and consultation timings.
  - View scheduled appointments.
  - Start video consultations.
  - Manage prescriptions and medical reports.

- **Admin Dashboard**:
  - Manage users (doctors and patients).
  - Monitor platform activity and metrics.
  - Resolve appointment disputes.
  - View revenue and credit usage.

### 🔗 Video Consultation
- Implemented using **Vonage (OpenTok) API**.
- Secure and real-time video calling between doctors and patients.

### 🗓️ Appointment Booking System
- Real-time doctor availability calendar.
- Slot-based appointment booking.
- Automatic reminders and notifications.

### 📁 Medical Records Management
- Patients can upload and manage their reports.
- Doctors can update prescriptions post-consultation.

### 💳 Credit System
- Patients use credits to book appointments.
- Admin can top-up or manage credit distribution.

## 🛠️ Tech Stack

| Frontend      | Backend        | Others             
|---------------|----------------|--------------|
| Next.js       | Next.js      |  PostgreSQL |
| Tailwind CSS  | Vonage API (Video)     | Prisma client   |
| Axios         | Prisma        | Nodemailer (optional) |

## 🧪 How to Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/prrajput1199/healthcare-platform.git
cd healthcare-platform
