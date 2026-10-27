<!-- HEADER BANNER -->
<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Rameez%20Karriem&fontSize=40&fontColor=ffffff"/>
</p>

<h2 align="center">💻 Application Development Student</h2>

<p align="center">
Motivated Application Development student pursuing a <b>Diploma in ICT at Cape Peninsula University of Technology</b>.  
Currently seeking a <b>Work Integrated Learning (WIL) internship</b> to apply technical skills and academic knowledge in a practical development environment.
</p>

---

# 📫 Contact Me

<p align="center">

📞 **0834270938**  
📧 **222357320@mycput.ac.za**  
📍 **Grassy Park, Cape Town**

<a href="https://www.linkedin.com/in/rameez-karriem-RK03">
<img src="https://img.shields.io/badge/LinkedIn-Rameez%20Karriem-blue?style=for-the-badge&logo=linkedin">
</a>

</p>

---

# 🚀 Technical Skills

<p align="center">

<img src="https://skillicons.dev/icons?i=python,java,html,css,javascript,github,mysql,vscode"/>

</p>

### Additional Skills

- Computer Hardware Troubleshooting & Repair  
- Software Installation & Configuration  
- Microsoft Office (Word, Excel, PowerPoint)  
- SQL & Database Fundamentals  

---

# 🎓 Education

### 🏫 Grassdale High School
**National Senior Certificate**  
2021

### 🏫 Cape Peninsula University of Technology
**Higher Certificate in IT**  
2023

### 🌐 Cisco
**IT Essentials**  
2023

### 🏫 Cape Peninsula University of Technology
**Diploma in Information Technology**  
2024 – 2026

---

# 💼 Work Experience

### NCC Environmental Services  
**Driver / Field Team Assistant**  
2025 – 2026  

- Coordinated and transported a **team of 5 members** to field locations  
- Planned **routes and schedules** to meet project deadlines  
- Led **on-site logistics** and ensured safe operations  
- Assisted with **environmental control tasks and field problem-solving**  
- Maintained clear **communication with supervisors and team members**

---

# 🧩 Projects

## 🖥 Student Management System
**Java Desktop Application | 2025**

A Java Swing-based application developed in a team environment to manage student records.  
The system allows users to add, update, and store student information using a connected SQL database.

**Key Features:**
- Object-oriented design using classes and encapsulation  
- Integration with SQL database for persistent storage  
- Input validation and exception handling for data accuracy  
- Graphical User Interface built with Java Swing

🔗 **Repository**

[View Project](https://github.com/RameezKarriem/Term4_ADP_Assignment)

---

## 🎨 NSFAS App Redesign
**UI/UX Project | 2025**

A redesign of the NSFAS mobile application aimed at improving usability and user experience.  
The project focused on identifying user pain points and creating a more intuitive interface.

**Key Features:**
- User research and usability analysis  
- Wireframes and high-fidelity UI prototypes  
- Improved navigation and accessibility  
- Designed using Figma 

🎨 **Prototype**

[View Figma Prototype](https://www.figma.com/proto/2o459QPq1FgqfB1zrhvukq/Untitled)

---

# 🌧️ SAEON Real-Time Rainfall Monitoring System

**Student:** Rameez Karriem  
**Institution:** Cape Peninsula University of Technology (CPUT)  
**My Role:** Agile Lead and Presenter  
**Project Start Date (Reporting Period):** 28 July 2026  
**Reporting Period End:** 23 October 2026  
**Duration:** 13 Weeks

---

## 🌍 About the Project

The **South African Environmental Observation Network (SAEON)** is a national research network that collects environmental data to support climate research, ecological studies and environmental monitoring.

Our group worked on an **IoT-based Real-Time Rainfall Monitoring System** to improve how rainfall, temperature and humidity readings are collected from remote monitoring stations.

### The Problem

Traditional USB data loggers require researchers to physically visit monitoring stations to retrieve environmental readings. This can delay access to information, increase travel costs and limit real-time monitoring.

### Our Solution

Our team developed an **ESP32-based IoT prototype** designed to collect environmental readings and transmit them through a cellular network to a cloud-connected dashboard.

The system aims to reduce manual data collection and allow SAEON researchers to access measurements remotely. Final outdoor deployment and field validation were still outstanding at the reporting cut-off.

---

## 🔧 Hardware and Technologies Used

### Hardware Components

- **ESP32 WROOM-32:** Main microcontroller that processes sensor readings.
- **TR-525M Rain Gauge:** Measures rainfall using a tipping-bucket mechanism.
- **DHT11 Sensor:** Used during initial temperature and humidity testing.
- **SHT31 Sensor:** Selected for the final product to measure temperature and relative humidity; final verification evidence is still required.
- **SIM7000G Module:** Provides cellular communication without requiring local Wi-Fi.
- **Solar Panel and Battery:** Support the planned remote power supply.
- **PCB and Enclosure:** Support hardware assembly and outdoor deployment preparation.

### Software and Technologies

- **MQTT:** Communication protocol used to transmit sensor readings.
- **HiveMQ Cloud:** MQTT broker that receives messages from the station.
- **Backend Ingestion Service:** Subscribes to MQTT messages, validates readings and writes records to Firebase.
- **Firebase:** Database platform for storing and retrieving environmental measurements.
- **Web Dashboard:** Provides current and historical measurements and station information.
- **Trello:** Used for Agile task management and progress tracking.
- **GitHub:** Used for source code, project documentation and portfolio evidence.

### Dashboard Features

The dashboard requirements include:

- Current rainfall, temperature and humidity readings.
- Historical records, charts and filtering by station and date.
- CSV export for further data analysis.
- Station health and battery information.
- Secure sign-in and protected access.
- Responsive layouts for desktop, tablet and mobile devices.

These features form part of the project scope; final acceptance depends on implementation and test evidence.

### ⚙️ How the System Works

The TR-525M rain gauge measures rainfall, while the SHT31 was selected to measure temperature and humidity in the final product. The DHT11 was used during initial testing.

The ESP32 WROOM-32 processes sensor readings and uses the SIM7000G cellular module to transmit them through MQTT to HiveMQ Cloud. A **backend ingestion service** then receives and validates the messages before storing valid records in **Firebase**.

The web dashboard is designed to display current and historical environmental information so that researchers can monitor stations remotely. Although integration tasks were reported as completed, final sensor verification and field-validation evidence were still required.

**Planned System Data Flow:**

`Sensors → ESP32 WROOM-32 → SIM7000G → HiveMQ Cloud (MQTT) → Backend Ingestion Service → Firebase → Web Dashboard`

---

## 📅 Project Timeline

The SAEON project followed a **13-week Agile development schedule**.

- **Start Date:** 28 July 2026
- **Reporting Period End:** 23 October 2026
- **Recorded Working Days:** Tuesday to Friday
- **Total Sprints:** 13 weekly sprint periods

Development included project planning, sensor integration, cloud connectivity, dashboard development, power and hardware preparation, testing, documentation and presentation activities.

At the reporting cut-off, **43 original task cards were reported Completed**, while **six deployment and field-validation tasks remained In Progress**. These included final deployment, baseline calibration and the stages of the 48-hour field test. Final SHT31 verification and Firebase authentication/access-rule evidence also required confirmation.

The reporting period end date is **not a claim that final field acceptance was completed**.

---

## 👥 My Role – Agile Lead and Presenter

As the **Agile Lead and Presenter**, my responsibilities involved supporting the organisation and coordination of our team's development activities.

My responsibilities included:

- Supporting sprint planning and team meetings.
- Tracking tasks and project progress using Trello.
- Encouraging communication and collaboration.
- Helping identify outstanding tasks and challenges.
- Maintaining my personal Agile Logbook.
- Preparing and presenting project information.

This role helped me develop leadership, communication, teamwork and Agile project management skills.

---

## 📋 Agile Project Management – Trello

Our team used Trello to organise and monitor the development of the SAEON Real-Time Rainfall Monitoring System.

Trello helped us:

- Organise tasks into weekly sprints.
- Assign and track development activities.
- Monitor project progress and outstanding work.
- Improve communication and accountability.

The team's working agreement called for weekly planning and three progress check-ins per week, with reviews and retrospectives after project milestones.

### SAEON Trello Board

![SAEON Trello Project Board](PRP370-SAEON/SAEON-Trello-Board.jpeg)

*Figure 1: SAEON Trello board used to track the Product Backlog, In Progress and Completed workflow stages.*

---

## 🎥 SAEON Prototype Testing Videos

As part of our SAEON Real-Time Rainfall Monitoring
System project, our team conducted practical hardware
development and sensor testing.

Video demonstrations include:

- 🌧️ Rainfall Sensor Testing
- 🌱 Soil Moisture Sensor Testing
- 🌡️ Temperature and Humidity Testing
- 💻 Prototype and Dashboard Demonstration

**[▶️ CLICK HERE TO WATCH THE SAEON PROJECT VIDEOS](PRP370-SAEON/README.md)**

--- 

# 📚 Agile Portfolio Evidence and Personal Reflections

---

## 🎓 Graduate Attributes and Portfolio Evidence

This document explains how the SAEON project demonstrates the four CPUT graduate attributes: Ubuntu, Technological Capability and Foresight, Resilience and Problem Solving, and Ethical Capability.

It also outlines our team contributions and the evidence supporting our development activities.

📄 **[View SAEON Graduate Attributes and Portfolio Evidence (PDF)](PRP370-SAEON/SAEON%20Graduate%20Attributes%20and%20Portfolio%20Evidence.pdf)**

---

## 1. Agile Team Charter

### Evidence

📄 [View Agile Team Charter](PRP370-SAEON/Agile%20Team%20Charter.pdf)

The Agile Team Charter outlines our team's purpose, responsibilities, working agreements and communication arrangements.

### My Personal Reflection: Agile Team Charter

Working on the SAEON Real-Time Rainfall Monitoring System helped me understand why an Agile Team Charter is important when working in a group. As the Agile Lead, my responsibility was to help keep the team organised, encourage communication and make sure that everyone understood what needed to be done.

The Team Charter outlined our different roles, responsibilities, working agreements and expectations. This was useful because our project involved several areas, including hardware development, backend integration, frontend design and research. Each member had different responsibilities, but we still needed to work towards the same goal.

One thing I learned was that assigning roles is only one part of teamwork. Communication and accountability are just as important because one person's progress can affect another person's work. I also realised that having agreed procedures makes it easier to address problems when tasks are delayed or responsibilities are unclear.

This experience helped me develop a better understanding of leadership and teamwork. If I worked on a similar project again, I would focus on reviewing our working agreements more regularly and making sure that important decisions were documented.

---

## 2. User Stories and Tasks

### Evidence

📄 [View User Stories and Tasks](PRP370-SAEON/User%20stories%20and%20tasks.pdf)

This document outlines system requirements, user stories, acceptance criteria and development tasks.

### My Personal Reflection: User Stories and Tasks

The User Stories and Tasks document helped me understand how a technical project can be broken down into smaller requirements based on what users actually need. Our SAEON project aimed to make rainfall information easier to access by reducing the need for researchers to collect readings manually from remote stations.

Before looking closely at the user stories, it was easy to focus mainly on the hardware and software that needed to be developed. However, the stories helped connect those technical components to the actual purpose of the system. Features such as monitoring rainfall, viewing live readings, accessing historical data and checking station health all had a specific benefit for the user.

From an Agile perspective, I learned how important it is for requirements to be clear before tasks are assigned. If a user story is too broad or does not have proper acceptance criteria, it becomes difficult to determine whether the work is actually complete.

I also learned that user stories should be connected to development tasks and testing evidence. In future projects, I would pay more attention to this connection from the beginning so that the team can identify missing requirements earlier.

---

## 3. Product Backlog

### Evidence

📄 [View Product Backlog](PRP370-SAEON/Product%20Backlog.pdf)

The Product Backlog outlines project activities, priorities and task progress throughout development.

### My Personal Reflection: Product Backlog

The Product Backlog was an important part of understanding how our SAEON project was organised over the 13-week development period. It provided an overview of the work required, from the initial planning and hardware setup to the dashboard development, testing and presentation preparation.

As Agile Lead, task tracking and understanding the team's priorities were important parts of my role. The backlog helped me see how the different project activities were connected and why some tasks needed to be completed before others could begin. For example, the sensor and communication components were important because the dashboard depended on receiving data from the monitoring system.

One of the biggest lessons I took from this was that a backlog should not be treated as a fixed list that never changes. Projects can experience delays, technical problems and changing priorities, especially when hardware and software are being developed together.

I also understood the importance of recording progress accurately. Tasks such as final deployment and field validation should remain in progress until the necessary work and testing have been completed.

This experience improved my understanding of prioritisation and project tracking. In future, I would make sure that each backlog item has clear ownership, acceptance criteria and supporting evidence.

---

## 4. Sprint Backlog

### Evidence

📄 [View Sprint Backlog](PRP370-SAEON/Sprint%20Backlog.pdf)

The Sprint Backlog breaks down the project into weekly sprint goals, assigned tasks and progress updates.

### My Personal Reflection: Sprint Backlog

The Sprint Backlog helped me understand how a larger project can be managed through smaller, more achievable stages. For our SAEON project, the work was organised into 13 weekly sprints, with activities planned from Tuesday to Friday.

My role as Agile Lead involved understanding sprint goals, following the progress of tasks and helping keep the team focused on the work that needed attention. I learned that sprint planning is not simply about deciding what should be completed during a particular week. It also involves understanding dependencies, available time and possible obstacles.

Our project involved both physical components and software development, which made coordination important. Work on the sensors, cellular communication, cloud integration and dashboard could affect other parts of the system. This helped me understand why teams need to communicate when something is delayed or when a task is not ready for testing.

Another important lesson was that reaching the end of a sprint does not automatically mean every task has been completed successfully. Outstanding work still needs to be tracked and reviewed.

If I were managing another project, I would place more emphasis on recording sprint feedback, identifying blockers early and keeping evidence of completed tasks. This would make it easier to measure progress and improve future sprint planning.

---

## 5. Agile Logbook

### Evidence

📄 [View My Agile Logbook](PRP370-SAEON/Agile%20Logbook.pdf)

My Agile Logbook records personal progress, planned activities and possible challenges throughout the project.

### My Personal Reflection: Agile Logbook

The Agile Logbook was especially relevant to me because it relates directly to my responsibilities as the Agile Lead. It provided a way to reflect on the project's progress, the activities that needed coordination and the challenges involved in working towards our goals.

The logbook covered the 13-week project period and included activities related to planning, monitoring progress, following up on tasks and preparing for the presentation. Looking back at these activities helped me understand that an Agile Lead does more than organise meetings. The role also requires communication, consistency and an awareness of how different parts of the project affect one another.

One important thing I learned was the value of recording information while work is happening. When daily progress, decisions or problems are not documented properly, it becomes difficult to remember the exact details later. This showed me why a logbook should be maintained throughout a project rather than reconstructed near the end.

Reflecting on my role also helped me identify an area where I can improve: keeping clearer records of meetings, decisions, outstanding tasks and supporting evidence.

Overall, the project gave me a better understanding of Agile coordination and the responsibilities involved in helping a development team work towards a shared objective. I believe these are skills that will be useful when I work with development teams in the future.

---

## 🎓 Overall Project Learning

The SAEON project gave me a better understanding of IoT technologies, Agile development and how hardware and software work together.

As Agile Lead and Presenter, I developed valuable skills in teamwork, communication, task coordination and project management that I can apply in future software development projects.

---

**PRP370 Assessment 2 | SAEON Real-Time Rainfall Monitoring System | 2026**

**Rameez Karriem – Agile Lead and Presenter**  
*Cape Peninsula University of Technology*


# 📌 References

### NCC Environmental Services

**Aaliyah Sulaman**  
Project Manager  
📧 aaliyah@ncc-group.co.za  
📞 082 492 9662  

**Hilton Rhodes**  
Supervisor  
📧 hiltonrhodes123@gmail.com  
📞 062 410 2519  

---

<h3 align="center">🎥 Mock Interview Video</h3>
<video width="400" height="600" controls>
  <source src="Rameez-Karriem-Interveiw (1) (1).mp4" type="video/mp4">
</video>

---

# Reflection

This project involved creating a personal portfolio using Markdown, developing a professional CV, and recording and editing an interview video. Through this process, I gained both technical and personal skills that contributed to my overall development.

---

### 📄 Reflection on CV Development

While creating my CV, I learned important principles about professional presentation and structure. I gained a clear understanding of what information should be included, such as relevant skills, education, and experience, as well as what should be excluded. This helped me think more critically about how to present myself to potential employers.

Although I did not struggle to learn Markdown itself, I did experience some challenges when applying it to structure my CV. Formatting the layout correctly and ensuring that all sections were aligned and visually appealing required practice. As I continued working on it, I became more comfortable and was able to produce a clean and well-organised CV.

This experience improved my ability to present information clearly and professionally, which is an essential skill in both academic and career contexts.

---

### 🎥 Reflection on Interview Video

The interview video was one of the more challenging aspects of the project. I used my phone to record the video and the mobile application CapCut to edit it. During the recording process, I had to repeat the video multiple times due to stuttering, forgetting what I wanted to say, and struggling to maintain proper eye contact.

These challenges highlighted areas where I need improvement, particularly in confidence and communication skills. However, the process also helped me become more aware of how I present myself when speaking.

In addition, I learned basic video editing skills, such as trimming clips and improving the overall flow of the video. These are valuable skills that I can apply in future projects.

---

### 🌐 Reflection on GitHub Pages & Markdown

Creating my GitHub Pages portfolio allowed me to apply my knowledge of Markdown in a practical way. I found that Markdown was simple to learn, but applying it effectively required attention to detail, especially when working with formatting, headings, links, and images.

I learned how to structure content in a way that is both readable and visually appealing. Working on my GitHub repository also helped me understand how to present my work online in a professional manner.

As I continued developing my page, I became more confident in using Markdown and improved my ability to organise and display content effectively.

---

### 🔍 Overall Reflection

Overall, this project helped me develop both technical and soft skills. I improved my understanding of Markdown, learned how to create a professional CV, and developed better communication and presentation skills through the interview process.

If I were to complete this project again, I would focus more on preparation, especially for the interview video. Preparing my responses in advance and practicing would help improve my confidence and reduce mistakes.

These skills and experiences will be beneficial for my future studies and career development.

---

<p align="center"> 
✨ Thank you for visiting my GitHub profile!
</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer"/>
</p>
