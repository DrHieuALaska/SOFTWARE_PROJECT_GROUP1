
# GymHub — Smart Gym Management System

> A centralized, web-based gym management and fitness tracking platform designed for gym members and administrators.

## 📖 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [System Roles](#-system-roles)
- [Technology Stack](#-technology-stack)
- [Project Structure](#-project-structure)
- [Prerequisites](#-prerequisites)
- [Installation and Setup](#-installation-and-setup)
  - [1. Clone the Repository](#1-clone-the-repository)
  - [2. Install Dependencies](#2-install-dependencies)
  - [3. Configure Environment Variables](#3-configure-environment-variables)
  - [4. Set Up the Database](#4-set-up-the-database)
  - [5. Run the Application](#5-run-the-application)
- [Environment Variables](#-environment-variables)
- [Usage](#-usage)
- [Documentation](#-documentation)
- [Team Members](#-team-members)
- [License](#-license)

---

##  About the Project

### Overview
GymHub is a web-based smart gym management system developed
as a project for the Introduction to Software Engineering course.

The system streamlines gym operations by replacing fragmented workflows with a single, unified digital ecosystem. 

For members, GymHub provides the flexibility to freely customize personal workout plans or utilize automated workout generation for personalized guidance and driving accountability through an interactive workout streak and consistency system. while also visualizing progress analytics and tracking real-time gym occupancy. 

For administrators, it provides a dedicated dashboard to oversee memberships, billing, and analyze facility utilization.


---

##  Technology Stack

| Component | Technology |
|-----------|------------|
| Frontend | React + TypeScript + Vite|
| Backend | Node.js and Express.js|
| Database | PostgreSQL |
| Authentication | JWT  |
| AI Service | Groq |

---

##  Prerequisites

Before running GymHub, make sure the following software
is installed on your machine:

- Node.js 
- npm 
- PostgreSQL
- Git

---

## Installation and Setup

### 1. Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd <YOUR_PROJECT_DIRECTORY>
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up the Database

Create a new database and execute `gym_init.sql` to initialize it.
### 4. Configure Environment Variables

Create the required environment files based on
the provided example files.

```bash
# move to backend folder
cd .\apps\backend\
# copy .env.example 
cp .env.example .env
# Fill your variables in .env
```

### 5. Run the Application

#### Start the Backend Server

```bash
cd .\apps\backend\
node .\server.js
```

#### Start the Frontend Server

```bash
npm run dev
```

---

## 📚 Documentation

Detailed project documentation is available in the
[`docs/`](./docs/) directory.

## 👨‍💻 Team Members

| Student ID | Name | Role |
|------------|------|------|
| 24127041 | Hoàng Trung Hiếu  | Backend Developer, Database Management, Tester |
| 24127073 | Khả Phước Lộc| Project Manager, Frontend Developer |
| 24127125 | Nguyễn Thanh Phát Thịnh  | Frontend Developer |
| 24127264 | Trần Thái Vỹ | Backend Developer, Tester |

