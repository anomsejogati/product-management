# CofitRehab — COVID-19 Rehabilitation Application

> **Type:** Health-tech Application (Web + Mobile)
> **Domain:** Pulmonary Rehabilitation & Physical Recovery
> **Platforms:** Web App (Admin & Doctor) + Mobile App (Patient)
> **Target Users:** COVID-19 survivors undergoing post-recovery rehabilitation

---

## Product Overview

**CofitRehab** is a digital health application designed to support **COVID-19 survivors** in their post-recovery rehabilitation journey. The app provides structured guidance for **pulmonary rehabilitation**, **aerobic exercise**, and **physical strengthening techniques** — enabling patients to perform rehabilitation activities independently while being remotely monitored by their assigned doctor.

The platform bridges the gap between clinical supervision and home-based rehabilitation by connecting patients, doctors, and administrators through an integrated digital ecosystem.

---

## Problem Statement

After recovering from COVID-19, many patients experience lingering respiratory issues, physical weakness, and reduced lung capacity. Traditional rehabilitation requires frequent in-person hospital visits, which creates barriers:

- **Limited hospital capacity** for rehabilitation programs
- **Geographic distance** between patients and specialist facilities
- **Lack of structured home-based rehabilitation** guidance
- **No visibility** for doctors to monitor patient progress remotely
- **Low patient adherence** without proper tracking and motivation

CofitRehab addresses these challenges by delivering a guided, tracked, and doctor-supervised rehabilitation program directly to patients' mobile devices.

---

## Key Stakeholders & Roles

| Role | Platform | Responsibilities |
|---|---|---|
| **Admin CofitRehab** | Web App | Manage system data — register doctors and patients, assign patients to doctors, manage rehabilitation programs |
| **Doctor** | Web App | Review patient rehabilitation activity logs, monitor vital measurements, provide evaluations and feedback |
| **Patient** | Mobile App | Follow guided rehabilitation exercises (video/instructions), input daily health measurements (SpO2, heart rate, etc.), track progress |

---

## Core Modules

### 1. User & Account Management (Admin)
- Register doctors with credentials and specialization
- Register patients with medical profile and condition severity
- Assign patients to doctors for supervision
- Manage rehabilitation program catalog

### 2. Rehabilitation Program Module
- **Pulmonary Rehabilitation** — Breathing exercises (pursed-lip breathing, diaphragmatic breathing, incentive spirometry techniques)
- **Aerobic Exercise** — Low-to-moderate intensity cardio exercises (walking, stationary cycling, step exercises) with progressive intensity levels
- **Physical Strengthening** — Muscle conditioning and flexibility exercises (upper body, lower body, core strengthening) tailored for post-COVID recovery

### 3. Guided Exercise Module (Patient - Mobile)
- Step-by-step exercise instructions with video/animation guidance
- Timer and rep counter for each exercise session
- Session scheduling with daily/weekly rehabilitation plans
- Exercise completion tracking and history

### 4. Health Measurement Module (Patient - Mobile)
- Daily vital sign input: **SpO2 (Oxygen Saturation)**, **Heart Rate**, **Respiratory Rate**, **Body Temperature**
- Pre-exercise and post-exercise measurement comparison
- Subjective symptom assessment (Borg Scale for perceived exertion, breathlessness scale)
- Measurement history and trend visualization

### 5. Doctor Review & Evaluation Module (Doctor - Web)
- Patient activity dashboard — see completed exercises and adherence rate
- Review patient vital sign trends over time
- Provide written evaluations and recommendations
- Flag patients with concerning measurement trends
- Adjust rehabilitation program intensity per patient

### 6. Reporting & Analytics
- Patient progress reports (per session, weekly, monthly)
- Vital sign trend charts (SpO2, heart rate over time)
- Rehabilitation adherence rate tracking
- Doctor workload summary (patients assigned, evaluations given)

---

## Rehabilitation Program Structure

```
Rehabilitation Plan (6-12 weeks)
├── Phase 1: Recovery (Week 1-2)
│   ├── Breathing exercises (2x/day, 10 min)
│   ├── Gentle stretching (1x/day, 10 min)
│   └── SpO2 monitoring before & after
│
├── Phase 2: Conditioning (Week 3-6)
│   ├── Pulmonary exercises (2x/day, 15 min)
│   ├── Light aerobic exercise (1x/day, 15-20 min)
│   ├── Basic strengthening (3x/week, 15 min)
│   └── Heart rate & SpO2 monitoring
│
└── Phase 3: Strengthening (Week 7-12)
    ├── Advanced breathing techniques (1x/day, 15 min)
    ├── Moderate aerobic exercise (1x/day, 20-30 min)
    ├── Progressive strengthening (3x/week, 20 min)
    └── Full vital measurement tracking
```

---

## Key Differentiators

| Feature | Traditional Rehab | CofitRehab |
|---|---|---|
| Location | Hospital/clinic only | Home-based via mobile app |
| Monitoring | During visit only | Continuous remote tracking |
| Doctor Feedback | In-person appointments | Async digital evaluations |
| Exercise Guidance | Printed handouts | Video-guided with timer |
| Progress Tracking | Paper-based log | Digital dashboard with charts |
| Patient Adherence | No tracking | Daily tracking with history |

---

## Technical Overview

| Aspect | Detail |
|---|---|
| **Web App (Admin & Doctor)** | Responsive web application for desktop/laptop |
| **Mobile App (Patient)** | Android application for patient self-service |
| **Backend** | REST API server with JWT authentication |
| **Database** | Relational database (MySQL/PostgreSQL) |
| **Notifications** | Push notification (mobile), Email |
| **Architecture** | Multi-role, role-based access control (RBAC) |

---

## Product Background

CofitRehab was developed in response to the COVID-19 pandemic's impact on Indonesian healthcare, where post-recovery rehabilitation demand far exceeded hospital capacity. The application was designed to enable **scalable, remote pulmonary rehabilitation** that could serve patients across geographic boundaries while maintaining clinical oversight through doctor-patient digital connectivity.

The product demonstrates end-to-end product development capabilities — from clinical requirement gathering, system analysis, UX design for multi-platform (web + mobile), API architecture, to implementation and deployment.
