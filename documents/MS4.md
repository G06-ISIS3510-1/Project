# Problem & Solution Description
#### Problem Description
University students often face daily mobility challenges that make commuting to campus expensive, disorganized, and stressful. Many rely on public transportation or ride-hailing services that, over time, consume a significant portion of their monthly budget. Informal ride arrangements between students usually happen through messaging apps or social media, which leads to last-minute cancellations, miscommunication, payment delays, uncertainty about arrival times, and safety concerns. Additionally, there is often a lack of trust and accountability between drivers and passengers, making shared commuting unreliable and frustrating for both sides.

#### Proposed Solution
Wheels is a structured, student-to-student mobility platform designed to make commuting more affordable, coordinated, and trustworthy. The app centralizes ride scheduling, seat availability, and payments in a single system, eliminating informal and disorganized arrangements. With real-time location tracking, automated notifications, verified university profiles, and a Reliability and Rewards system, Wheels encourages punctuality, responsible behavior, and fairness. By improving coordination, transparency, and trust, Wheels transforms the student commuting experience into a more efficient, safe, and stress-free solution.

# Analytics persona
 
**Description:** This analytics persona represents a data-driven professional responsible for understanding user behavior and improving platform performance. With experience in mobility and digital platforms, this persona focuses on analyzing ride patterns, identifying retention drivers, and transforming operational data into strategic insights. Their main objective is to support data-informed decisions that enhance reliability, reduce churn, and enable sustainable business growth.
<img width="1521" height="1636" alt="Analytics Persona drawio" src="https://github.com/user-attachments/assets/2fa20be5-8eeb-49e6-af2b-a281ca7f27a7" />


# Problems-Alternative-Solutions (PAS)

**Description:** The following Problems–Alternative–Solutions (PAS) list was developed through a structured brainstorming session, applying the “yes… and” technique discussed in class. We identified both expressed needs (such as high transportation costs and disorganization) and latent needs (like trust, recognition, and reliability), then analyzed how students currently solve these issues through informal work-arounds. Based on this analysis, we generated alternative solutions that improve those existing practices and clearly demonstrate how Wheels creates greater value compared to current options.

| ID | Problem | Alternative | Solution |
|----|----------|------------|-----------|
| 1 | Many university students spend a large portion of their monthly budget on transportation to campus. | They use public transportation or ride-hailing apps despite the high cumulative cost. | Wheels provides a student-to-student ride-sharing platform with significantly lower per-trip costs. |
| 2 | Informal ride coordination between students is disorganized and unreliable. | Students arrange rides through WhatsApp or social media, leading to confusion and cancellations. | Wheels centralizes ride scheduling and confirmations in one structured app. |
| 3 | Students often feel uncertain about pickup times and arrival estimates. | They constantly message or call the driver for updates. | Wheels integrates real-time location tracking to monitor routes and confirm arrivals. |
| 4 | Drivers experience delayed or incomplete payments from passengers. | They demand cash upfront or stop offering rides. | Wheels includes integrated payment tracking and reliability scoring for on-time payments. |
| 5 | Passengers frequently deal with late drivers and excessive waiting times. | They return to more expensive but predictable transportation services. | Wheels implements a Reliability and Rewards system that encourages punctuality. |
| 6 | There is a lack of trust between student drivers and passengers. | Students prefer commuting alone or using impersonal transportation services. | Wheels verifies university profiles and includes transparent reliability feedback metrics. |
| 7 | Students are unaware of peers traveling similar routes at similar times. | They assume no ride is available and use alternative transport. | Wheels allows users to filter rides by schedule, location, and availability. |
| 8 | Drivers often travel with empty seats, missing the opportunity to share costs. | They absorb the full fuel and transportation expense. | Wheels allows drivers to publish available seats and match with students heading the same way. |
| 9 | Last-minute changes create stress and miscommunication between users. | Students rely on repeated messaging or cancel trips. | Wheels sends automated notifications and real-time updates to reduce confusion. |
| 10 | Students feel commuting is stressful due to unpredictability and lack of structure. | They tolerate inefficient systems or overpay for convenience. | Wheels improves coordination through structured bookings and route monitoring. |
| 11 | Some students worry about safety when sharing rides informally. | They avoid shared rides and use crowded public transport instead. | Wheels provides verified student-only access and real-time trip tracking for increased safety. |
| 12 | Students who behave responsibly receive no recognition compared to unreliable users. | Good users feel unmotivated and stop participating actively. | Wheels includes a Reliability and Rewards system that incentivizes punctual arrivals and responsible behavior. |

# Context Canvas

**Description:** The following Context Canvas shows how Wheels fits into the real-world environment where it will be used. It connects the personas, the mobile app, and the backend services to explain how they interact with each other, what information flows between them, and what technical conditions and constraints must be considered. By looking at all these elements together, we can better understand how the solution works as a whole.

<img width="2315" height="1432" alt="ContextCanvasG16 drawio" src="https://github.com/user-attachments/assets/a1282118-e15b-4df5-a1f5-ad8c631f5c21" />


# 10 Business Questions

**Description:** In the following section, we present the main business questions that guide the development of Wheels. These questions were designed based on the five types proposed in the book, allowing us to use analytics not only to monitor the app’s performance, but also to improve user experience, evaluate features, and explore potential business opportunities in a structured and measurable way.

## Type 1 – App's Telemetry
**Q1.**  How many new users our app has each week?

**Justification:**  This is a Type 1 question because it focuses in a descriptive characteristic of the app, while also providing data that con be used to take decisions (such as marketing campaigns).

---

## Type 2 – Direct user experience improvement

**Q2.**  Where is the user going based on his location?

**Justification:**  By identifying where the user is, we can recommend a ride that best suits his necessity (if he's far from university, we can suggest rides that go there)

**Q3.**  Which time is the user using the app more frequently?

**Justification:**  We can send notifications to users at specific hours of a day based on his/her previous usage habits.

**Q4.**  Do users have a pattern (in terms of time before ride) on their cancellations?

**Justification:**  Some users may forget to cancel a ride they will not take, so by identifying how much time before a ride most cancellations take place, we can send him/her a notification asking if they are still interested in the ride they booked.

**Q5.**  How frequently a user cancels his rides?

**Justification:**  The app can manage a 'cancellation rating' where users that cancel a ride too close to the time it was scheduled get a harsher punishment than those that cancelled ahead of time.


---

## Type 3 – Features analysis

**Q6.**  Which features are passangers spending more time on?

**Justification:**  This question helps us identify which app features are relevant to passangers and this is key for type 3 questions, because their are related with the introduction of new features in our app.

**Q7.**  Which features are drivers spending more time on?


**Justification:**  Similar to the last question, this one allow us to comprehend if features are necessary but this time on the driver's side.

**Q8.**  Do passangers use the seat assignation method?


**Justification:**  In this question we are pursuing to know if a functionality is useful to drivers and passangers, in this case we will test and count to know if users do like our function.

---

##  Type 4 – Benefits from data

**Q9.**  Which type/location of adds produce the most amout of clicks?

**Justification:**  This question help us understand where and how to place our adds, if adds do have clicks, then we can have more revenue from our sponsors and then we can have a more profitable business.

---

##  Type 5 – * 

**Q10.**  Which are the most frecuent destinations of a user. **Type 2 & Type 4**

**Justification:**  This questions allow us to recommend better trips to our users by knowing their most frecuent destinations, so it serves as a type 2 question, howerver by doing this we can increase the amount of users that use our app having more revenue through adds, this way it serves a double purpose as a type 4.

---

# VD Map

**Description:** The next VD map shows how Wheels transforms raw data from the **User DB**, **Rides DB**, and phone context data (such as user location and time) into meaningful insights that answer our 10 business questions. The flow begins with data sources, continues through aggregation processes like calculating total new users per week, average cancellations per user, time spent per feature, most frequent destinations, seat reservation usage, and ad clicks, and then presents the results using visualizations such as line graphs, bar charts, pie charts, and simple lists. Each visualization directly answers a specific question (color-coded by type), clearly connecting backend data processing with user experience improvements, feature evaluation, telemetry monitoring, and business decision-making.

<img width="1521" height="1636" alt="VD Map" src="https://github.com/user-attachments/assets/90cb1125-ab93-4181-b81b-3976613dd359" />


