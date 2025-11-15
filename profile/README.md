# Memis

**An Alzheimer's assistance platform designed to help patients and caregivers manage daily routines and stay connected.**

---

## What is Memis?

Memis is a comprehensive digital health solution specifically designed to support individuals living with Alzheimer's disease and their caregivers. The platform combines a user-friendly mobile application with a robust backend API to provide essential tools for managing daily care, maintaining routines, and facilitating family communication.

## What Does Memis Do?

Memis addresses the daily challenges faced by Alzheimer's patients and their support networks through several key capabilities:

### 📱 **Smart Reminders**
- Set customizable reminders for daily tasks (medications, meals, appointments, personal care)
- Support for recurring schedules (daily, hourly, custom patterns)
- Track completion history to monitor adherence
- Reduce cognitive load with simple, clear notifications

### 👥 **Family Communication Hub**
- Hierarchical chat system (Rooms → Threads → Messages)
- Private family rooms for coordinated care discussions
- Keep all caregivers informed and aligned
- Quick communication when decisions are needed

### 🔗 **Simplified Device Pairing**
- Passwordless authentication for patients using 8-character pairing codes or QR codes
- Once paired, devices become trusted with PIN/biometric unlock
- Eliminates password management burden for patients
- Secure yet accessible device management

### 📞 **Contact Management**
- Maintain a curated list of important family members and contacts
- Quick access to key support people
- Emergency contact information at hand

### 🏥 **Caregiver Tools**
- Create and manage patient profiles
- Generate pairing codes for device setup
- Monitor reminder adherence and activity
- Track multiple patients with role-based access (Owner, Editor, Viewer)

## Key Benefits

### For Patients
- **Reduced Cognitive Load**: Simple, intuitive interface designed for accessibility
- **Independence**: Manage daily routines with minimal assistance
- **Peace of Mind**: Stay connected with family without complex technology
- **Dignity**: Maintain autonomy while receiving necessary support

### For Caregivers
- **Coordinated Care**: Multiple family members can collaborate on patient care
- **Remote Monitoring**: Track patient adherence and activity from anywhere
- **Efficient Communication**: Quick updates and coordination through the chat system
- **Reduced Stress**: Automated reminders reduce the need for constant oversight

### For Families
- **Centralized Information**: All care-related information in one place
- **Shared Responsibility**: Multiple caregivers can contribute with appropriate permissions
- **Real-Time Updates**: Stay informed about patient status and needs
- **Better Care Coordination**: Reduce miscommunication and gaps in care

## Technical Architecture

Memis is built as a modern, scalable full-stack application:

### Frontend
- **Mobile App**: React Native with Expo for iOS, Android, and Web (PWA)
- **UI Framework**: NativeWind (Tailwind CSS for React Native)
- **State Management**: Zustand
- **Navigation**: React Navigation

### Backend
- **API Framework**: NestJS (Node.js/TypeScript)
- **Database**: PostgreSQL with Prisma ORM
- **Authentication**: JWT with refresh token rotation
- **Documentation**: Swagger/OpenAPI

### Infrastructure
- **Containerization**: Docker Compose for local development
- **Cloud Deployment**: Designed for cloud hosting (Render, Vercel, Neon)

### Security Features
- Secure session management with refresh token rotation
- Passwordless authentication for patients
- Role-based access control (RBAC)
- Device-based trust model
- Secure data encryption and storage

## Core Features

✅ **Multi-Role System**: Guest, Patient, Caregiver, Admin roles  
✅ **Reminder Management**: Full CRUD with recurrence patterns  
✅ **Hierarchical Chat**: Room → Thread → Message structure  
✅ **Device Pairing**: QR code and manual code entry  
✅ **Contact Management**: Family contact directory  
✅ **Patient Profiles**: Comprehensive patient information management  
✅ **Session Management**: Secure authentication with refresh token rotation  
✅ **Accessibility**: Designed with accessibility in mind  

## Use Cases

- **Daily Medication Reminders**: Ensure patients take medications on schedule
- **Family Care Coordination**: Multiple family members managing care for a loved one
- **Remote Caregiving**: Monitor and support patients from a distance
- **Routine Management**: Help maintain daily routines that support cognitive function
- **Emergency Preparedness**: Quick access to important contacts and information

## Project Structure

```
Memis/
├── memis-frontend/      # React Native mobile app (iOS, Android, Web)
├── memis-backend/       # NestJS REST API
└── memis-infra/         # Docker Compose infrastructure
```

## Technology Stack

**Frontend:**
- React Native (Expo)
- TypeScript
- NativeWind / Tailwind CSS
- React Navigation
- Zustand

**Backend:**
- NestJS
- TypeScript
- Prisma ORM
- PostgreSQL
- JWT Authentication

**Infrastructure:**
- Docker
- PostgreSQL
- Redis
- pgAdmin

---

## Learn More

For detailed API documentation, visit our [Swagger documentation](https://memis-backend.onrender.com/swagger).

For technical implementation details, please refer to the individual README files in the `memis-frontend` and `memis-backend` directories.

---

**Memis** - *Supporting memory, supporting care, supporting life.*

