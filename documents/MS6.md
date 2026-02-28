# 1) One Defined Idea (Single Solution)

**Wheels is a university-exclusive ride-sharing platform that connects verified students inside the same campus community to coordinate safe, reliable and cost-efficient rides, with two tailored experiences: Passenger and Driver.**

Wheels is built around **trust-by-design**: only verified university members can access the platform, reducing uncertainty and increasing safety during ride coordination and financial transactions.

The system includes:
- A **Passenger interface** for searching and joining rides.
- A **Driver interface** for publishing rides and managing earnings.

This dual-experience approach reinforces clarity of roles and optimizes the UX for each user type.

---

# 2) Value Proposition

## For Passengers
- Safer rides within a **verified university network**
- Lower cost compared to traditional ride-hailing
- Higher reliability for recurring routes (home–campus–events)
- Transparent ride information and ratings

## For Drivers
- Flexible income from trips they already make
- Reduced cancellation risk through verified users
- Clear financial transparency (earnings, ride history, states)
- Reputation system that reinforces accountability

## Key Differentiators

1. Closed community (university verification required)
2. Driver-centered financial clarity
3. Mobility optimized for student routines
4. Community-based trust model

> **Wheels delivers safe, verified student mobility with transparent earnings and community-based accountability.**

---

# 3) UI/UX Design System (Material + Flat Design)

The design follows **Material Design** and **Flat Design** principles, ensuring it is aligned with mobile application standards and not web-only interaction patterns.

---

## 3.1 Color Palette

### Primary – Navy Blue
- #1a3a5c
- #2d5280
- #5b89c8

**Rationale:**  
Conveys trust, stability, professionalism and security. High contrast ensures mobile readability (WCAG compliant).

### Accent – Electric Green
- #00d9a3
- #00c794

**Rationale:**  
Represents action, financial success, safety and positive confirmation. Used for CTAs and earnings.

### Neutral Scale
- Text Primary: #1a3a5c
- Text Secondary: #64748b
- Background: #f7f9fc
- Border: #e5e9f2

### Alerts
- Warning: #ffa726
- Error: #ff5252
- Success: #00d9a3

---

## 3.2 Typography

### System Font Stack (Implemented)

Ensures:
- Native mobile feel
- No load delay
- High readability
- Accessibility optimization

Alternative (branding option):
- Headings: Poppins (600–700)
- Body: Inter (400–500)

Mobile sizing:
- H1: 24–28px
- H2: 20–24px
- Body: 14–16px
- Minimum touch target: 44px

---

## 3.3 Icon System

Style: Outlined icons with rounded corners  
Library: Lucide (Material-compatible)

Why:
- Clear at small sizes
- Modern aesthetic
- Consistent 2px stroke
- Easy state coloring

---

## 3.4 Navigation Pattern

Primary Navigation: **Bottom Tab Bar**

Tabs:
1. Home
2. Create Ride / Search Rides
3. Alerts
4. Profile

Why Bottom Navigation:
- Thumb-friendly
- Always visible
- Mobile-native pattern
- Supports quick task switching
- Material Design compliant

Secondary Navigation:
Stack navigation inside each tab.

Bottom navigation remains visible except for full-screen overlays.

# Navigational Patterns - Wheels

## Login Page (`/`)

**Actions:**
- Login ➔ Dashboard Page (`/dashboard`)
- Forgot Password ➔ Password Recovery (not implemented in prototype)

---

## Dashboard Page (`/dashboard`)

**Bottom Navigation:**
- Home (current) ➔ Dashboard Page (`/dashboard`)
- Create ➔ Create Ride Page (`/create-ride`)
- Alerts ➔ Notifications Page (`/notifications`)
- Profile ➔ Profile Page (`/profile`)

**Page Actions:**
- Quick Pay Button ➔ Quick Payment Page (`/payment`)
- View Active Ride ➔ Active Ride Management Page (`/active-ride`)
- Back ➔ Login Page (`/`)

---

## Create Ride Page (`/create-ride`)

**Bottom Navigation:**
- Home ➔ Dashboard Page (`/dashboard`)
- Create (current) ➔ Create Ride Page (`/create-ride`)
- Alerts ➔ Notifications Page (`/notifications`)
- Profile ➔ Profile Page (`/profile`)

**Page Actions:**
- Publish Ride Button ➔ Active Ride Management Page (`/active-ride`)
- Back ➔ Dashboard Page (`/dashboard`)

---


## Search a ride page (`/rides`)

**Bottom Navigation:**
- Home ➔ Dashboard Page (`/dashboard`)
- Create (current) ➔ Find a ride (`/rides`)
- Alerts ➔ Notifications Page (`/notifications`)
- Profile ➔ Profile Page (`/profile`)

**Page Actions:**
- Publish Ride Button ➔ Active Ride Management Page (`/active-ride`)
- Back ➔ Dashboard Page (`/dashboard`)

---

## Notifications Page (`/notifications`)

**Bottom Navigation:**
- Home ➔ Dashboard Page (`/dashboard`)
- Create ➔ Create Ride Page (`/create-ride`)
- Alerts (current) ➔ Notifications Page (`/notifications`)
- Profile ➔ Profile Page (`/profile`)

**Page Actions:**
- Mark all read ➔ Updates notification states (same page)
- Notification Item ➔ Relevant page based on notification type
- Back ➔ Dashboard Page (`/dashboard`)

---

## Profile Page (`/profile`)

**Bottom Navigation:**
- Home ➔ Dashboard Page (`/dashboard`)
- Create ➔ Create Ride Page (`/create-ride`)
- Alerts ➔ Notifications Page (`/notifications`)
- Profile (current) ➔ Profile Page (`/profile`)

**Page Actions:**
- Trust & Fairness ➔ Trust & Fairness Page (`/trust`)
- Payment Methods ➔ Payment Settings (not implemented in prototype)
- Notifications Settings ➔ Notification Settings (not implemented in prototype)
- Help & Support ➔ Support Page (not implemented in prototype)
- Logout ➔ Login Page (`/`)

---

## Trust & Fairness Page (`/trust`)

**Bottom Navigation:**
- Home ➔ Dashboard Page (`/dashboard`)
- Create ➔ Create Ride Page (`/create-ride`)
- Alerts ➔ Notifications Page (`/notifications`)
- Profile ➔ Profile Page (`/profile`)

**Page Actions:**
- Back ➔ Profile Page (`/profile`)
- View Full History ➔ Penalty History (same page, expanded)
- Expand Examples ➔ Penalty Examples Modal (same page)

---

## Active Ride Management Page (`/active-ride`)

**Bottom Navigation:**
- Home ➔ Dashboard Page (`/dashboard`)
- Create ➔ Create Ride Page (`/create-ride`)
- Alerts ➔ Notifications Page (`/notifications`)
- Profile ➔ Profile Page (`/profile`)

**Page Actions:**
- Start Ride Button ➔ Updates ride status (same page)
- Mark Passenger No-Show ➔ No-Show Modal (same page)
- End Ride Button ➔ Quick Payment Page (`/payment`)
- Group Chat ➔ Group Coordination Page (`/group/:rideId`)
- Back ➔ Dashboard Page (`/dashboard`)

---

## Quick Payment Page (`/payment`)

**Bottom Navigation:**
- Home ➔ Dashboard Page (`/dashboard`)
- Create ➔ Create Ride Page (`/create-ride`)
- Alerts ➔ Notifications Page (`/notifications`)
- Profile ➔ Profile Page (`/profile`)

**Page Actions:**
- Send Payment Request ➔ Success message (same page)
- Split Costs ➔ Updates payment distribution (same page)
- Request Payment ➔ Sends request to passengers (same page)
- Back ➔ Dashboard Page (`/dashboard`)

---

## Group Coordination Page (`/group/:rideId`)

**Page Actions:**
- Send Message ➔ Updates chat (same page)
- Close/Back ➔ Active Ride Management Page (`/active-ride`)

**Note:** This is a full-screen overlay modal, no Bottom Navigation visible.

---

**Page Actions:**
- Filter Reviews ➔ Updates review list (same page)
- Back ➔ Profile Page (`/profile`)

---
## Reviews & Ratings Page (`/reviews`)

**Bottom Navigation:**
- Home ➔ Dashboard Page (`/dashboard`)
- Create ➔ Create Ride Page (`/create-ride`)
- Alerts ➔ Notifications Page (`/notifications`)
- Profile ➔ Profile Page (`/profile`)

**Page Actions:**
- Filter Reviews ➔ Updates review list (same page)
- Back ➔ Profile Page (`/profile`)

---

# 4) Deployed Prototypes (Public Links)

Both prototypes are deployed and accessible publicly.

### Passenger Prototype
https://train-icon-23170077.figma.site

### Driver Prototype
https://charm-scrum-09656872.figma.site

These links are accessible without authentication.

---

# 5) How to View the Prototype (Mandatory Instructions)

Since the prototypes were built using web technologies but designed as mobile interfaces, they must be viewed in mobile mode.

Steps:

1. Open the prototype link in a browser.
2. Open Developer Tools:
   - Windows: Ctrl + Shift + I
   - Mac: Cmd + Option + I
3. Activate Device Toolbar:
   - Windows: Ctrl + Shift + M
   - Mac: Cmd + Shift + M
4. Select a mobile device (e.g., iPhone 13 / Pixel 7).
5. Refresh if needed.


The UI is optimized for mobile viewport only.

---
# 6) Logo
The Wheels logo is designed with a minimalist and modern approach, aligned with Material Design and flat design principles to ensure clarity, scalability, and optimal performance in mobile environments.

The main symbol consists of a deep navy blue circular shape representing a wheel, reinforcing the concept of mobility and transportation. The circular form also communicates stability, trust, and security — core values of the platform, which operates as a verified, university-exclusive community.

Inside the circle, there is an upward geometric shape in navy blue that simultaneously suggests a road and a stylized “W”, directly referencing the application’s name. This upward movement conveys direction, progress, and growth within the university community.

Above this central element, three electric green nodes are connected by thin lines, symbolizing the student network and the connection between drivers and passengers. The electric green color represents action, movement, financial success, and positive confirmation within the user experience.

The combination of navy blue (#1a3a5c) and electric green (#00d9a3) creates strong visual contrast while maintaining a professional and trustworthy appearance. The logo works effectively both as a complete brand mark with the “Wheels” wordmark and as a simplified app icon, maintaining recognizability even at small sizes.

Overall, the logo communicates safe university mobility, verified community access, and financial transparency, fully aligned with Wheels’ trust-by-design value proposition.

<img width="1080" height="1350" alt="Diseño sin título (2)" src="https://github.com/user-attachments/assets/6aa82557-28c3-464d-8ff0-a166310d8cc9" />

