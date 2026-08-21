<div align="center">

# ☢️ DOOMSDAY

### THE WORLD IS RUNNING OUT OF TIME.

**A full-stack interactive survival command center.**

</div>

<br>

<img src = "./docs/images/doomsday-hero.png" alt = "Doomsday Command Center" width= "100%">

<br>

![Status](https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-red)

</div>

---

## ☢️ THE WORLD HAS CHANGED

DOOMSDAY is a full-stack survival command center built around a simple question:

> **How prepared are you when civilization collapses?**

The platform combines survival management, threat monitoring, resource tracking, missions, real-time alerts, and team coordination into a single interactive system.

This project is being built from the ground up as a practical exploration of modern full-stack web development, system architecture, databases, APIs, real-time communication, animation, and deployment.

---

## ⚠️ SYSTEM CAPABILITIES

### 🛰️ Command Center

A centralized dashboard providing an overview of the user's survival status, resources, active threats, missions, and system alerts.

### 🌍 Threat Monitoring

Monitor fictional global disasters, regional threat levels, environmental conditions, and changing emergency situations.

### 🎒 Survival Inventory

Track essential resources such as water, food, medicine, fuel, equipment, and other survival supplies.

### 📊 Survival Score

Calculate a dynamic survival score based on resource availability, preparedness, skills, health, shelter, and other factors.

### 🚨 Emergency Alerts

Receive critical system alerts and simulated emergency broadcasts as global conditions change.

### 🎯 Missions

Complete survival-oriented missions, earn XP, increase your survival score, and unlock achievements.

### 🧑‍🤝‍🧑 Survivor Teams

Create and manage survivor groups, coordinate resources, assign missions, and eventually communicate in real time.

### 🗺️ Global Threat Map

Explore an interactive map containing disaster zones, threat levels, affected regions, and emergency information.

### 🏆 Achievements

Unlock achievements by reaching survival milestones and completing increasingly difficult objectives.

---

## 🛠️ TECHNOLOGY STACK

### Frontend

| Technology    | Purpose                                |
| ------------- | -------------------------------------- |
| React         | Building the user interface            |
| Vite          | Frontend development and build tooling |
| Tailwind CSS  | Styling and responsive UI              |
| Framer Motion | Animations and page transitions        |

### Backend

| Technology | Purpose                          |
| ---------- | -------------------------------- |
| Node.js    | Backend runtime                  |
| Express.js | REST API and server architecture |

### Database

| Technology | Purpose                            |
| ---------- | ---------------------------------- |
| PostgreSQL | Persistent application data        |
| Prisma     | Database ORM and schema management |

### Authentication & Security

| Technology | Purpose                                 |
| ---------- | --------------------------------------- |
| JWT        | Authentication and protected API access |
| bcrypt     | Password hashing                        |

### Real-Time Systems

| Technology | Purpose                           |
| ---------- | --------------------------------- |
| WebSockets | Real-time alerts and team updates |

### Development & Deployment

| Technology | Purpose                            |
| ---------- | ---------------------------------- |
| Git        | Version control                    |
| GitHub     | Source code and project management |
| Docker     | Containerization                   |
| CI/CD      | Automated testing and deployment   |

---

## 🧠 SYSTEM ARCHITECTURE

DOOMSDAY follows a modular full-stack architecture designed to separate the user interface, application logic, data access, and persistent storage.

```text
                         ┌──────────────────────┐
                         │       USER           │
                         └──────────┬───────────┘
                                    │
                                    ▼
                         ┌──────────────────────┐
                         │   React Frontend     │
                         │                      │
                         │  Components          │
                         │  Pages               │
                         │  State Management    │
                         │  Animations          │
                         └──────────┬───────────┘
                                    │
                              HTTP / REST
                                    │
                                    ▼
                         ┌──────────────────────┐
                         │   Express Backend    │
                         │                      │
                         │  Routes              │
                         │  Controllers         │
                         │  Middleware          │
                         │  Business Logic      │
                         └──────────┬───────────┘
                                    │
                                    ▼
                         ┌──────────────────────┐
                         │       Prisma         │
                         │     ORM Layer        │
                         └──────────┬───────────┘
                                    │
                                    ▼
                         ┌──────────────────────┐
                         │     PostgreSQL       │
                         │      Database        │
                         └──────────────────────┘


                 ┌──────────────────────────────┐
                 │       Real-Time Layer        │
                 │          WebSockets          │
                 └──────────────┬───────────────┘
                                │
                 ┌──────────────┴──────────────┐
                 ▼                             ▼
          Emergency Alerts              Team Updates
```

---

## 🖥️ SYSTEM INTERFACE

The DOOMSDAY interface is designed around a dark, cinematic emergency-command aesthetic, combining real-time information, resource management, and interactive survival systems.

### Command Center

> Coming soon — the primary survival dashboard.

### Global Threat Map

> Coming soon — interactive visualization of global disaster zones.

### Survival Inventory

> Coming soon — resource tracking and management interface.

### Emergency Alerts

> Coming soon — real-time emergency notification system.

### Survivor Teams

> Coming soon — collaborative survival management.

---

## ☢️ DEVELOPMENT ROADMAP

### PHASE 01 — FOUNDATION

- [x] Create public GitHub repository
- [x] Initialize local Git repository
- [x] Configure `.gitignore`
- [x] Establish project documentation
- [x] Define final project architecture
- [ ] Set up development environment

### PHASE 02 — VISUAL SYSTEM

- [ ] Define DOOMSDAY design system
- [ ] Establish typography
- [ ] Establish spacing and layout system
- [ ] Define color palette
- [ ] Create reusable UI components
- [ ] Configure animations and transitions
- [ ] Build responsive design foundation

### PHASE 03 — FRONTEND

- [ ] Build landing page
- [ ] Build authentication interface
- [ ] Build command center
- [ ] Build survival inventory
- [ ] Build survival score system
- [ ] Build threat monitoring interface
- [ ] Build global threat map
- [ ] Build mission system
- [ ] Build achievement system
- [ ] Build survivor team interface

### PHASE 04 — BACKEND

- [ ] Initialize Node.js backend
- [ ] Configure Express
- [ ] Establish API architecture
- [ ] Create controllers and services
- [ ] Implement request validation
- [ ] Implement centralized error handling
- [ ] Implement API logging

### PHASE 05 — DATABASE

- [ ] Configure PostgreSQL
- [ ] Configure Prisma
- [ ] Design database schema
- [ ] Create migrations
- [ ] Implement relationships
- [ ] Seed development data

### PHASE 06 — AUTHENTICATION & SECURITY

- [ ] User registration
- [ ] User login
- [ ] Password hashing
- [ ] JWT authentication
- [ ] Protected routes
- [ ] Authorization
- [ ] Input validation
- [ ] Rate limiting
- [ ] Security hardening

### PHASE 07 — REAL-TIME SYSTEM

- [ ] WebSocket infrastructure
- [ ] Real-time emergency alerts
- [ ] Live threat updates
- [ ] Real-time team updates
- [ ] Connection management

### PHASE 08 — TESTING

- [ ] Unit testing
- [ ] API testing
- [ ] Component testing
- [ ] Integration testing
- [ ] End-to-end testing
- [ ] Error and edge-case testing

### PHASE 09 — DEPLOYMENT

- [ ] Production environment configuration
- [ ] Dockerize application
- [ ] Configure CI/CD
- [ ] Deploy frontend
- [ ] Deploy backend
- [ ] Deploy database
- [ ] Configure production monitoring
- [ ] Final performance optimization

### PHASE 10 — RELEASE

- [ ] Final security review
- [ ] Final UI polish
- [ ] Documentation review
- [ ] Production testing
- [ ] Capture application screenshots
- [ ] Update README
- [ ] Release DOOMSDAY v1.0

---

## 🚀 INSTALLATION & LOCAL DEVELOPMENT

### Prerequisites

Before running DOOMSDAY locally, make sure you have the following installed:

- Node.js
- npm
- Git

### Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/DOOMSDAY.git
cd DOOMSDAY
```
