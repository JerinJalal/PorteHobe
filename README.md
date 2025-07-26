# Web Application Development
The project focuses on building a full-stack web application using:  Backend: Laravel (PHP)  Frontend: React.js with HTML, CSS, and JavaScript  Rendering: Client-Side Rendering (CSR)  DevOps Practices: GitHub Project boards, version control, deployment preparation.

# PorteHobe

**PorteHobe** is an smart study time tracker that helps students manage their academic routines with personalized study planning, a built-in calendar, session timer, goal tracking, badge achievements, and intelligent summarization. It’s built using **Laravel** (backend) and **React.js** (frontend) with **Client-Side Rendering (CSR)**.

---
# Figma Link : 
View our UI prototype on Figma: [PorteHobe Figma Design](https://www.figma.com/design/FoAR51kOeeZjd4ZVgG9m9c/PortreHobe?node-id=0-1&t=3r9grvoPjmGdOVqE-1)



##  Project Overview

- **Project Title:** PorteHobe
- **Objective:** Help students manage their study time efficiently with smart planning, motivational tracking, and AI-assisted tools.
- **Target Audience:** School and university students seeking structured, distraction-free, and personalized learning support.
- **Rendering Method:** Client-Side Rendering (CSR)

---

## Core Features

-  AI-Powered Note Summarization  
-  Smart Study Plans  
-  Goal & Streak Tracker
-  Smart Resource Finder (YouTube/Articles) & Quizes

---

##  Tech Stack

- **Backend:** Laravel (PHP Framework)
- **Frontend:** React.js with Tailwind CSS
- **Database:** MySQL
- **APIs:** 
  - Mock AI API / DeepSeek API (summarization & quiz generation)
  - YouTube API (resource finder)
- **Deployment:** Vercel / Heroku / Render / AWS
- **Version Control:** Git + GitHub
- **Authentication:** Laravel Sanctum / JWT + OAuth (Google)

---

##  Team Members

| Roll Number      | Name                 | github account                                                             | WakaTime             |
|------------------|----------------------|----------------------------------------------------------------------------|----------------------|
| 20220204035      | Sadia Sultana        | <a href="https://github.com/Steadfast404" target="_blank"> Steadfast404</a>|                      |
| 20220204039      | Jerin Jalal          | <a href="https://github.com/JerinJalal" target="_blank"> JerinJalal </a>   |                      |
| 20220204051      | Md. Nafiun Alom      | <a href="https://github.com/NafiunAyon" target="_blank"> NafiunAyon </a>   |                      |
| 20220204052      | Prionty Kundu Aurin  | <a href="https://github.com/Source-Soul" target="_blank"> Source-Soul</a>  |                      |

---

##  UI Pages & Features

### 1. Authentication

- **Login & Register Pages**
  - Google Sign-In
  - Password-based login
  - Role-based access: Student / Admin

---

### 2. Term Setup (After Login)

- 2-column layout:  
  - Left: Welcome message, branding  
  - Right: Setup form:  
    - University/School toggle  
    - Term name, start/end dates  
    - Study goal (weekday/weekend)  
    - Live summary of term length and goal

---

### 3. Dashboard

- Sidebar Navigation:
  - Home, Subjects, Study Plan, Resources, Summarizer, Progress, Calendar, Badges, Profile, Logout  
- Home Panel:
  - Daily tasks
  - Motivational quote
  - Quick action cards

---

### 4. Subjects Page

- Add/Edit/Delete Subjects  
- Set deadlines & individual goals  
- Display as responsive cards or table

---

### 5. AI Study Plan Generator

- Select subjects  
- Set deadlines  
- Input available hours/day  

---

### 6. Smart Resource Finder

- Search bar with keyword input  
- Filter by content type (YouTube, Articles, Quizzes)  
- Display in card layout with thumbnails and links  

---

### 7. Note Summarizer 

- Paste text box  
- Summarize via Mock AI API or DeepSeek API
- Show bullet-point summary  

---

### 8. Timer & Session Tracker

- Two-column layout:  
  - Left: Create session  
  - Right: Session history with illustration if empty  
- Session Form includes:
  - Date, Start/End Time, Course, Activity, Notes  
  - Break time and submit button  
- Header shows:
  - Date, Goal status, Average study duration  
- **Top Right: Timer **

---

### 9. Progress & Calendar

- Progress bar 
- Heatmap calendar (study streaks)
- Calendar color boxes by intensity

---

### 10. Badges Page 

- **Categories:**
  - Daily, Weekly, Milestone  
- **Examples:**
  - Gold Medal (>300min)
  - Early Bird (Before 7 AM)
  - Golden Week (Daily Gold for 7 days)
- Lock icon for locked badges
- Modern cards with trophy icons and shadows

---

### 11. Profile Page 

- Name, email, profile photo  
- Change password  
- Set preferences

---

### 12. Admin Panel

- Add/edit motivational quotes  
- View platform usage stats  
- Post announcements or updates

---

##  Theme & Design

- **Dark / Light Mode Toggle** in Navbar
- **Fonts:** Inter or Poppins
- **Colors:** Soft pastels (violet, green, yellow, blue)


---

