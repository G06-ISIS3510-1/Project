# Sprint 1

## Introduction

Urban mobility represents a daily challenge for university students, especially in large cities where public transportation is often overcrowded, unreliable, or perceived as unsafe. In this context, many students rely on informal ride-sharing systems organized through messaging applications, which lack structure, transparency, and accountability. These informal practices generate coordination problems, payment conflicts, and trust issues that negatively affect students’ commuting experience.

This project proposes **NOMBRE_APP**, a digital platform designed to improve student-to-student carpooling at Universidad de los Andes. Through a user-centered design approach and data-driven analysis, NOMBRE_APP aims to transform informal transportation coordination into a reliable, accessible, and community-oriented mobility system.

---

## 1. Project Contextualization

This section describes the main problem addressed by the project, the proposed solution, the adopted revenue model, and the value proposition of NOMBRE_APP.

### 1.1 Selected Problem

University students at Universidad de los Andes face expensive, disorganized, and unreliable commuting options. Many students coordinate rides informally through WhatsApp groups and social media, which leads to excessive messaging, unclear pickup times, frequent last-minute cancellations, delayed payments, and safety concerns.

These informal systems lack standardized processes for booking, confirmation, payment, and reputation management. As a result, both drivers and passengers experience uncertainty, stress, and inefficiencies in their daily routines. Additionally, the absence of trust mechanisms discourages responsible behavior and reduces long-term participation in shared transportation.

Overall, the current situation forces students to choose between high-cost commercial ride-hailing services and poorly organized informal alternatives, neither of which adequately addresses their needs.

---

### 1.2 Proposed Solution

NOMBRE_APP is a mobile application that provides a structured, secure, and student-centered carpooling platform exclusively for Universidad de los Andes students. The platform replaces informal coordination with centralized ride management and transparent interaction mechanisms.

Key features of NOMBRE_APP include:

- Institutional user verification through university credentials.
- Structured ride publishing, booking, and confirmation.
- Integrated payment tracking and receipt generation.
- Real-time location sharing and route monitoring.
- Reliability and reputation scoring based on punctuality, cancellations, and payment behavior.
- Easy switching between driver and passenger modes.
- Automated notifications and status updates.

By integrating these features into a single platform, NOMBRE_APP simplifies coordination, reduces uncertainty, and improves trust among users, enabling more efficient and predictable daily commuting.

---

### 1.3 Revenue Model

NOMBRE_APP adopts a community-centered and accessibility-oriented revenue model that prioritizes affordability for students. All core transportation services are completely free of charge, ensuring that the platform does not increase commuting costs.

The primary source of revenue is voluntary user donations, allowing satisfied users to contribute to the maintenance and continuous improvement of the platform. This approach encourages community engagement and reinforces trust.

Additionally, NOMBRE_APP incorporates non-intrusive native advertising focused on local businesses and student entrepreneurship, such as nearby shops, services, and small student ventures. These advertisements are contextually relevant and designed to avoid disrupting the user experience.

In the long term, NOMBRE_APP may implement an optional freemium model, offering advanced features such as driver profile highlighting (subject to reliability standards) and advanced analytics dashboards. These premium features provide additional value without affecting access to essential services.

This hybrid model ensures financial sustainability while preserving fairness and accessibility.

---

### 1.4 Value Proposition

NOMBRE_APP provides Universidad de los Andes students with a free, secure, and structured carpooling platform that replaces informal coordination through messaging applications. By integrating verified profiles, automated bookings, real-time tracking, and transparent reputation systems, NOMBRE_APP reduces uncertainty, improves safety, and simplifies daily commuting.

Unlike commercial ride-hailing services that increase transportation costs through commissions, NOMBRE_APP prioritizes community trust and affordability. At the same time, it offers greater reliability and organization than informal alternatives.

Through its student-focused design and ethical monetization approach, NOMBRE_APP enables efficient, low-cost, and predictable mobility while strengthening cooperation within the university community.


---


## 2. Problems-Alternative-Solutions (PAS)

**Description:** The following Problems–Alternative–Solutions (PAS) list was developed through a structured brainstorming session, applying the “yes… and” technique discussed in class. We identified both expressed needs (such as high transportation costs and disorganization) and latent needs (like trust, recognition, and reliability), then analyzed how students currently solve these issues through informal work-arounds. Based on this analysis, we generated alternative solutions that improve those existing practices and clearly demonstrate how NOMBRE_APP creates greater value compared to current options.

| ID | Problem | Alternative | Solution |
|----|----------|------------|-----------|
| 1 | Many university students spend a large portion of their monthly budget on transportation to campus. | They use public transportation or ride-hailing apps despite the high cumulative cost. | NOMBRE_APP provides a student-to-student ride-sharing platform with significantly lower per-trip costs. |
| 2 | Informal ride coordination between students is disorganized and unreliable. | Students arrange rides through WhatsApp or social media, leading to confusion and cancellations. | NOMBRE_APP centralizes ride scheduling and confirmations in one structured app. |
| 3 | Students often feel uncertain about pickup times and arrival estimates. | They constantly message or call the driver for updates. | NOMBRE_APP integrates real-time location tracking to monitor routes and confirm arrivals. |
| 4 | Drivers experience delayed or incomplete payments from passengers. | They demand cash upfront or stop offering rides. | NOMBRE_APP includes integrated payment tracking and reliability scoring for on-time payments. |
| 5 | Passengers frequently deal with late drivers and excessive waiting times. | They return to more expensive but predictable transportation services. | NOMBRE_APP implements a Reliability and Rewards system that encourages punctuality. |
| 6 | There is a lack of trust between student drivers and passengers. | Students prefer commuting alone or using impersonal transportation services. | NOMBRE_APP verifies university profiles and includes transparent reliability feedback metrics. |
| 7 | Students are unaware of peers traveling similar routes at similar times. | They assume no ride is available and use alternative transport. | NOMBRE_APP allows users to filter rides by schedule, location, and availability. |
| 8 | Drivers often travel with empty seats, missing the opportunity to share costs. | They absorb the full fuel and transportation expense. | NOMBRE_APP allows drivers to publish available seats and match with students heading the same way. |
| 9 | Last-minute changes create stress and miscommunication between users. | Students rely on repeated messaging or cancel trips. | NOMBRE_APP sends automated notifications and real-time updates to reduce confusion. |
| 10 | Students feel commuting is stressful due to unpredictability and lack of structure. | They tolerate inefficient systems or overpay for convenience. | NOMBRE_APP improves coordination through structured bookings and route monitoring. |
| 11 | Some students worry about safety when sharing rides informally. | They avoid shared rides and use crowded public transport instead. | NOMBRE_APP provides verified student-only access and real-time trip tracking for increased safety. |
| 12 | Students who behave responsibly receive no recognition compared to unreliable users. | Good users feel unmotivated and stop participating actively. | NOMBRE_APP includes a Reliability and Rewards system that incentivizes punctual arrivals and responsible behavior. |


---


## 3. Context Canvas

**Description:** The following Context Canvas shows how NOMBRE_APP fits into the real-world environment where it will be used. It connects the personas, the mobile app, and the backend services to explain how they interact with each other, what information flows between them, and what technical conditions and constraints must be considered. By looking at all these elements together, we can better understand how the solution works as a whole.

<img width="4630" height="2864" alt="ContextCanvasG16 drawio (1)" src="https://github.com/user-attachments/assets/9e0d7342-493b-41cf-b70e-54438d604706" />


---


## 4. Personas

Based on the empathy maps and insights gathered during the user research phase, we identified recurring behavioral patterns, needs, and motivations among users. As a result, we decided to classify the users into three representative personas that capture the main roles within the NOMBRE_APP Uniandes ecosystem: Student Driver, Student Passenger, and Student Passenger/Driver:


### 4.1 Prospective personas

#### **Student Passenger**
**Description:** The Student Passenger depends on carpooling as a regular way of getting to campus, especially when public transportation feels too slow, crowded, or unsafe. She often starts her day early and wants a commute that feels predictable and calm, without having to send multiple messages or wait for replies in busy WhatsApp groups. Uncertainty about pickup times, driver availability, or delays adds stress to her routine and affects how she plans her day. What she values most is feeling safe, informed, and on time. 

<img width="1521" height="1636" alt="Passenger" src="https://github.com/user-attachments/assets/15956dd5-5622-4290-857f-a3d9ae8861a8" />

---

#### **Student Driver**  
**Description:** The Student Driver is a Uniandes student who usually goes to campus by car and often has empty seats during the trip. Offering rides to other students helps them reduce fuel and parking costs, but only if it doesn’t make their commute more complicated or stressful. Right now, they rely on WhatsApp groups to coordinate rides, which often leads to last-minute changes, uncertainty about whether passengers will arrive on time, and awkward payment situations. They care about efficiency and fairness, and they want to feel confident  that the users will pay.


![Persona1](https://github.com/user-attachments/assets/c59106d1-dd4a-4313-9dcb-9041975ba012)

---

#### **Student Passenger / Driver (Hybrid)**  
**Description:** The Student Passenger / Driver moves between being a driver and a passenger depending on the day, their schedule, and whether they have access to a car. Some days they are happy to offer rides and share costs, while on others they prefer to ride with someone else to save time or money. This flexibility makes informal coordination difficult, as switching roles repeatedly in WhatsApp groups can become confusing and inefficient. They want a system that adapts to their changing needs without requiring extra effort or explanation.

<img width="1521" height="1636" alt="Hybrid" src="https://github.com/user-attachments/assets/cd3aa37e-240a-4868-b601-67747d3384d5" />

---

### 4.2 Analytics personas

#### **Data Driven Professional**
**Description:** This analytics persona represents a data-driven professional responsible for understanding user behavior and improving platform performance. With experience in mobility and digital platforms, this persona focuses on analyzing ride patterns, identifying retention drivers, and transforming operational data into strategic insights. Their main objective is to support data-informed decisions that enhance reliability, reduce churn, and enable sustainable business growth.
<img width="1521" height="1636" alt="Analytics Persona drawio" src="https://github.com/user-attachments/assets/2fa20be5-8eeb-49e6-af2b-a281ca7f27a7" />


---

## 5. Empathy Maps

Empathy maps were developed to better understand the thoughts, emotions, behaviors, and contextual factors that influence how different types of students experience informal and structured ride-sharing. Each map represents a specific user scenario and captures what users see, think, feel, and do when interacting with transportation alternatives. These maps were built based on interviews, observations, and prior analysis, and they serve as a foundation for identifying pain points, guiding feature design, and ensuring that NOMBRE_APP responds effectively to real user needs.

### Empathy Map 1  
**User:** Occasional Passenger  
Student who uses NOMBRE_APP only in specific situations such as late nights, rain, exams, or emergencies.

<img width="1920" height="1080" alt="Interfaces and options he doesn’t fully understand" src="https://github.com/user-attachments/assets/a0ff4257-61bd-49eb-bd08-8d02f8966fb5" />


---

### Empathy Map 2  
**User:** Student Driver  
Student who offers rides to others to reduce commuting costs or earn extra money.
<img width="1060" height="657" alt="Captura de pantalla 2026-02-07 a la(s) 12 14 42 a  m" src="https://github.com/user-attachments/assets/3460db8e-e9fc-44ef-9b7b-8af0212eee32" />


---

### Empathy Map 3  
**User:** Frequent Passenger 
Student who frequently uses shared rides and values punctuality and fairness.

<img width="1005" height="637" alt="Captura de pantalla 2026-02-18 a la(s) 9 11 17 a  m" src="https://github.com/user-attachments/assets/a3ead0cb-9552-44c5-a173-12a703304d6f" />



---

### Empathy Map 4  
**User:** Female User 
Female student who ocasionally uses shared rides and feels a little bit insecure.
<img width="1720" height="1133" alt="Captura de pantalla 2026-02-06 202039" src="https://github.com/user-attachments/assets/6b5d6bed-9d92-448c-b532-9de8b615beaf" />


---


## 6. Business questions



---




## 7. VD Map


---


## 8. Functional scenarios 



---

## 9. Quality scenarios


---


## 10. Ethics video


---
