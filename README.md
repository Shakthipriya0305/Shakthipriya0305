# Hi, I'm Shakthi Priya 👋

### 💻 Software Developer | 🤖 AI Enthusiast | 📊 Data Analytics | 🔌 IoT

I'm a final-year **Electronics and Communication Engineering student**
at **Velammal Engineering College, Chennai**, graduating in **2027**.

I enjoy building practical technology solutions that combine
**software development, AI, data, backend systems, and IoT**.

I'm currently strengthening my skills in **Java, Python, SQL,
Data Structures & Algorithms, backend development, and data analytics**.

---

## 👩‍💻 About Me

🎓 B.E. Electronics and Communication Engineering student  
📅 Expected Graduation: 2027  
📍 Chennai, India  

💻 Interested in Software Development  
🤖 Interested in AI-powered applications  
📊 Interested in Data Analytics  
🐍 Working with Python  
☕ Learning and developing with Java  
🗄️ Working with SQL and databases  
🔌 Interested in IoT and intelligent systems  
🚀 Passionate about building practical projects  
📚 Always learning new technologies and improving my problem-solving skills

---

# 🛠️ Tech Stack

## 👨‍💻 Programming Languages

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%20(Beginner)-A8B9CC?style=for-the-badge&logo=c&logoColor=black"/>
</p>

## 📊 Data Analytics

- Python
- NumPy
- Pandas
- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization

## ⚙️ Backend & APIs

- Python
- FastAPI
- REST APIs
- SQLAlchemy
- Pydantic
- PostgreSQL
- API Integration

## 🌐 Web Technologies

- HTML
- JavaScript
- Tailwind CSS

## 🔧 Tools

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
  <img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=google-colab&logoColor=black"/>
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
</p>

---

# 🚀 Featured Projects

## 🏥 Continuum — AI Health Memory Platform

> An AI-agent-powered persistent health memory platform for maintaining
> longitudinal patient health records across healthcare touchpoints.

Continuum is a **FastAPI + PostgreSQL backend system** paired with a
static frontend prototype.

The platform organizes patient health information into a structured
longitudinal timeline while providing consent management, medication
change tracking, and an AI-agent integration layer.

### 🎯 Problem

Patient health information can be distributed across different
records and healthcare interactions.

Continuum aims to provide a structured health memory layer that
maintains a continuous and traceable view of patient health history.

### ✨ Key Features

- 📋 Longitudinal patient health timeline
- 🗄️ PostgreSQL-based patient health record storage
- 🔌 REST APIs using FastAPI
- 🧩 SQLAlchemy ORM
- ✅ Pydantic request and response schemas
- 🔐 Consent and consent-expiry enforcement
- 💊 Medication change tracking
- 🤖 AI-agent integration layer
- 🔎 Health record traceability
- 📖 Swagger API documentation
- 👨‍⚕️ Patient and doctor data models
- 👥 Caregiver observation support

### 🏗️ Architecture

```text
                     CONTINUUM
                         │
             ┌───────────┴───────────┐
             │                       │
             ▼                       ▼
     Frontend Prototype          AI Layer
     HTML + JavaScript              │
             │              ┌───────┴────────┐
             │              │                │
             │        Consent Agent    Records Adapter
             │              │                │
             └──────────────┴────────────────┘
                            │
                            ▼
                       FastAPI API
                            │
                            ▼
                      SQLAlchemy ORM
                            │
                            ▼
                       PostgreSQL
                            │
                            ▼
                   Patient Health Records
```

### 📋 Longitudinal Timeline

The project provides:

```text
GET /api/patients/{id}/timeline
```

The endpoint returns patient health events in chronological order.

The timeline can contain:

- Medications
- Diagnoses
- Procedures
- Laboratory results
- Vital readings
- Caregiver observations

Each event contains a record identifier for traceability back to
its source database record.

### 🔐 Consent Enforcement

The consent agent checks the patient's consent expiry date before
records are passed to the AI layer.

This ensures that expired consent cannot simply be bypassed through
an AI prompt.

### 💊 Medication Change Tracking

The Medicine model includes a `change_note` field to record
medication changes.

Example:

```text
Dosage increased from 500mg to 750mg
```

### 🛠️ Technology

```text
Python
FastAPI
PostgreSQL
SQLAlchemy
Pydantic
REST API
HTML
JavaScript
Tailwind CSS
AI Agents
```

### 📁 Project Structure

```text
continuum-health-memory/
│
├── main.py
├── seed_demo.py
├── requirements.txt
├── .env.example
├── .gitignore
│
├── app/
│   ├── database.py
│   ├── models.py
│   ├── schemas.py
│   │
│   ├── routers/
│   │   └── patients.py
│   │
│   └── ai_agents/
│       ├── consent_agent.py
│       └── records_adapter.py
│
├── frontend/
│   └── index.html
│
└── docs/
    ├── PROJECT_AUDIT.md
    ├── INSTALLATION_STEPS.md
    ├── P0_CHANGES_MANIFEST.md
    └── IMPLEMENTATION_CHECKLIST.txt
```

### 🚀 Future Improvements

- Connect the frontend prototype to the live FastAPI backend
- Implement authentication
- Add role-based access control
- Add automated testing
- Improve AI-agent capabilities
- Add audit logging
- Improve patient and caregiver workflows
- Deploy the application to a cloud environment

---

# 🎯 Career Compass — AI Career Guidance Platform

Career Compass is a **software-based AI career guidance platform**
designed to provide personalized career recommendations based on
a user's interests, skills, and academic profile.

### 💡 Features

- 👤 User profile-based recommendations
- 🎯 Interest-based career recommendations
- 🧠 Skill-based recommendations
- 🎓 Academic profile consideration
- 🤖 AI-powered career guidance
- 🔗 External API integration
- 🌐 Web-based interface

### 🛠️ Technology

```text
HTML
JavaScript
API Integration
AI
```

### 🎯 Objective

The goal of Career Compass is to help students explore suitable
career paths based on their individual interests, skills and
academic background.

---

# 💊 Smart Pill Dispenser — IoT / Embedded System

An Arduino-based medicine reminder system designed to provide
automated medication alerts.

### ✨ Features

- ⏰ Real-time scheduling
- 📺 LCD display
- 🔔 Automated buzzer alerts
- 🔧 Arduino Uno implementation
- 🕐 RTC-based time management

### 🛠️ Technology

```text
Arduino Uno
RTC
LCD
Buzzer
Embedded C
```

---

# 💼 Internship Experience

## 📊 Data Analytics Intern — Maincrafts Technology

**June 2026**

- Cleaned and analyzed structured datasets using Python, Pandas
  and NumPy
- Performed data preprocessing
- Conducted Exploratory Data Analysis (EDA)
- Identified patterns and trends in datasets
- Created data visualizations
- Generated insights to support data-driven decision-making

---

## 🌐 Student Intern — Bharati Airtel Limited

**November 2025**

- Studied enterprise communication networks
- Learned about broadband technologies
- Explored optical fiber and undersea cable systems
- Observed enterprise networking solutions
- Gained exposure to customer service workflows

---

# 🎓 Education

## Velammal Engineering College — Chennai

### Bachelor of Engineering
### Electronics and Communication Engineering

**2023 – 2027**

**CGPA: 8.23 / 10.0**

---

## Velammal Matriculation Higher Secondary School

**HSC:** 83%

**2022 – 2023**

---

## Velammal Matriculation Higher Secondary School

**SSLC:** 80%

**2020 – 2021**

---

# 🏆 Certifications & Achievements

### 📊 Data Analytics Job Simulation
**Deloitte Australia**

Completed a data analytics job simulation focused on practical
data analysis and business-oriented problem solving.

### ☕ Java for Beginners
**Udemy**

### 🔐 Cryptography and Network Security
**NPTEL**

### 🥇 First Prize — Technical Paper Presentation

**Smart Garments**

Received first prize for a technical paper presentation related
to Smart Garments.

---

# 👥 Leadership & Extracurricular Activities

## Student Coordinator — Department Symposium

- Collaborated with faculty, senior students and peers
- Helped plan and organize technical events
- Developed communication and teamwork skills
- Gained experience in event coordination and leadership

---


# 🎯 Career Interests

I'm interested in opportunities involving:

- 💻 Software Development
- ⚙️ Backend Development
- 📊 Data Analytics
- 🤖 AI Applications
- 🐍 Python Development
- ☕ Java Development
- 🗄️ SQL & Database Applications
- 🔌 IoT & Intelligent Systems
- 🚀 Technology-driven projects

---

# 🌱 My Learning Philosophy

```text
Learn → Build → Test → Improve → Repeat
```

I believe the best way to learn technology is by building projects,
solving problems and continuously improving existing solutions.

---

# 📌 What I'm Currently Working On

- Strengthening Java fundamentals
- Practicing SQL
- Improving Data Structures & Algorithms
- Building Python projects
- Learning backend development
- Exploring AI-powered applications
- Improving software development practices
- Building a stronger GitHub portfolio

---

# 📊 GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Shakthipriya0305&show_icons=true&theme=default)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Shakthipriya0305&layout=compact&theme=default)

---

# 📈 My Development Journey

```text
Electronics & Communication Engineering
                    │
                    ▼
             Programming
                    │
          ┌─────────┼─────────┐
          ▼         ▼         ▼
        Java      Python      SQL
          │         │         │
          └─────────┼─────────┘
                    ▼
             Software Projects
                    │
          ┌─────────┼──────────┐
          ▼         ▼          ▼
        Career   Continuum   Analytics
        Compass              Projects
          │         │          │
          └─────────┼──────────┘
                    ▼
              AI + Software
                    │
                    ▼
             Real-world Solutions
```

---

# 🤝 Connect With Me

### 📧 Email

poojahari473@gmail.com

### 💼 LinkedIn

https://www.linkedin.com/in/shakthi-priyah/

### 🐙 GitHub

https://github.com/Shakthipriya0305

---

# ⭐ Thanks for Visiting!

I'm always interested in learning, building and exploring new
technologies.

If you find any of my projects interesting, feel free to explore
the repositories and connect with me.

### 🚀 Let's Learn, Build and Grow Together!

⭐ Don't forget to check out my repositories!
<!--
**Shakthipriya0305/Shakthipriya0305** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
