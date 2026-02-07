# Brainstorming Process - Smart Features

The brainstorming process started by identifying potential smart features that combine sensors and data to improve the user experience. In parallel, we reflected on common mobility problems faced by university students when commuting from home to campus in order to propose ideas that could address these issues. As a group, we also discussed existing informal solutions, such as students offering rides to other students at lower prices than traditional transportation options.

Each idea was proposed openly and discussed in terms of feasibility, value for students, and potential to solve recurring issues such as lack of payment, poor coordination, delays, and unclear communication. After the discussion, we shortlisted the most promising ideas.

We then organized these ideas using a simple clustering method, comparing their potential impact and feasibility. 

---

## Ideas Generated

- Student-to-student ride service (Wheels)
- Centralized app for ride coordination
- Real-time location tracking and route visibility
- On-time payment and punctuality reward system
- Smart arrival and waiting-time detection
- Group coordination and communication tools
- Reliability scoring for riders and drivers
- Notifications and reminders for payments and arrivals

---

## Output Themes

### Trust & Fairness
- On-time payment tracking
- Reliability scoring system
- Arrival and waiting-time detection

### Convenience & Coordination
- Centralized ride coordination
- Real-time tracking
- In-app communication

### Core Platform
- Student-to-student ride marketplace
- Smart notifications
- Incentive-based system

---

As described previously and following the techniques learned in class, we first conducted a group brainstorming session where all members contributed ideas. These ideas were captured using a virtual whiteboard, where we deliberately avoided using “but” and instead adopted the “yes, and” approach to encourage idea expansion. Each group member added their proposals to a shared virtual Padlet, as shown below:

<img width="1335" height="740" alt="Screenshot 2026-02-07 003425" src="https://github.com/user-attachments/assets/87cb9096-306c-4a62-aaa2-65b4344a5870" />

Next, we carried out a convergence step in which similar or repeated ideas were combined, and others were selected based on team voting. Ideas that overlapped significantly were removed, and the remaining ones were classified into the categories “Rational Choice,” “Most Likely to Delight,” “The Darling,” and “The Long Shot.”:


<img width="1328" height="758" alt="Screenshot 2026-02-07 002804" src="https://github.com/user-attachments/assets/f505c5f1-00f8-439d-80e6-3a0ba701b5a3" />

---

# Decision Process

The final idea for the semester, Wheels, was selected through a divergence and convergence process, following the ideation techniques learned in class. During the divergence phase, the team generated multiple ideas using the “Yes, and” approach to encourage open discussion and creativity. Examples of generated ideas included a student-to-student ride service, a centralized app for coordinating rides, real-time location tracking, reliability scoring for drivers and passengers, and notification systems for arrivals and payments.

In the convergence phase, the team discussed these ideas **verbally** and grouped related concepts, combining complementary features and discarding overlapping ones. Rather than using written post-it notes, the team relied on structured discussion guided by feasibility, relevance to student mobility problems, and alignment with insights obtained from the interviews. A final decision was reached through team voting, ensuring that all members participated equally in the selection process.

A final decision was reached through team voting, resulting in the selection of **Wheels: a centralized carpooling application designed exclusively for Uniandes students**.

Although in a previous milestone (MS2) the team explored an application focused on restaurant discovery and coordination at Uniandes, the convergence process revealed that Wheels addressed a more recurrent and impactful need for students. The voting results reflected a shared agreement that Wheels offered greater potential for user value and for incorporating smart features based on mobile sensors and data.

---

# Empathy Maps

## Empathy Map 1  
**User:** Occasional Passenger  
Student who uses Wheels only in specific situations such as late nights, rain, exams, or emergencies.

<img width="1920" height="1080" alt="Interfaces and options he doesn’t fully understand" src="https://github.com/user-attachments/assets/a0ff4257-61bd-49eb-bd08-8d02f8966fb5" />


---

## Empathy Map 2  
**User:** Student Driver  
Student who offers rides to others to reduce commuting costs or earn extra money.
<img width="1060" height="657" alt="Captura de pantalla 2026-02-07 a la(s) 12 14 42 a  m" src="https://github.com/user-attachments/assets/3460db8e-e9fc-44ef-9b7b-8af0212eee32" />


---

## Empathy Map 3  
**User:** Frequent Passenger 
Student who frequently uses shared rides and values punctuality and fairness.

<img width="1920" height="1080" alt="Interfaces and options he doesn’t fully understand (1)" src="https://github.com/user-attachments/assets/9ab16987-8285-43ea-9e22-31cdae7af37a" />


---

## Empathy Map 4  
**User:** Female User 
Female student who ocasionally uses shared rides and feels a little bit insecure.
<img width="1720" height="1133" alt="Captura de pantalla 2026-02-06 202039" src="https://github.com/user-attachments/assets/6b5d6bed-9d92-448c-b532-9de8b615beaf" />


---

## Empathy Map 5  
**User:** Budget-Conscious Student 
Student with limited financial resources who depends on low-cost rides.
<img width="1060" height="659" alt="Captura de pantalla 2026-02-07 a la(s) 12 10 06 a  m" src="https://github.com/user-attachments/assets/e1531a2d-fc36-4012-94b2-07edd3443a5b" />


---

# Personas

Based on the empathy maps and insights gathered during the user research phase, we identified recurring behavioral patterns, needs, and motivations among users. As a result, we decided to classify the users into three representative personas that capture the main roles within the Wheels Uniandes ecosystem: Student Driver, Student Passenger, and Student Passenger/Driver:

## Persona 1  
**Student Passenger**  
This persona represents students who rely on carpooling as their primary way to commute to university and prioritize safety, reliability, and time efficiency. She reflects users who currently depend on informal coordination through WhatsApp groups and experience stress due to uncertainty and long commute times.

<img width="1521" height="1636" alt="Passenger" src="https://github.com/user-attachments/assets/15956dd5-5622-4290-857f-a3d9ae8861a8" />

---

## Persona 2  
**Student Driver**  
A student who owns or has access to a car and offers rides to other students. Is concerned about late payments, delays, and lack of commitment from riders.


![Persona1](https://github.com/user-attachments/assets/c59106d1-dd4a-4313-9dcb-9041975ba012)

---

## Persona 3  
**Student Passenger / Driver (Hybrid)**  
This persona represents students who alternate between offering and requesting rides depending on their daily access to a car and schedule. He reflects users who seek flexibility and cost optimization while coordinating carpooling through unstructured communication channels.

<img width="1521" height="1636" alt="Hybrid" src="https://github.com/user-attachments/assets/cd3aa37e-240a-4868-b601-67747d3384d5" />

---

# Description of the Solution

Wheels is a **student-to-student mobility service** designed to help university students commute from home to campus at a much lower cost per trip than traditional transportation options. The platform centralizes everything in a single app, replacing informal and disorganized ride arrangements with a structured, reliable system.

Through Wheels, student drivers can offer rides while passengers can join trips based on availability, location, and schedule. The app integrates **real-time location tracking** to monitor routes, detect arrivals, and confirm when users reach pickup and drop-off points, reducing confusion and uncertainty.

To address common issues such as late payments and delays, Wheels includes a **Reliability and Rewards system** that tracks punctual arrivals, waiting behavior, and on-time payments. Responsible users are rewarded, while unreliable behavior is discouraged through transparent feedback rather than punishment.

By focusing on coordination, fairness, and trust, Wheels improves the shared ride experience for both drivers and passengers, making student commuting more affordable, organized, and stress-free.

---

