# AI-Powered EdTech Platform

## Overview
ElevateEd is an AI-driven EdTech platform designed with a **microservices architecture** to ensure scalability and modularity. The platform enables students to **enroll in courses, take AI-generated assessments, and receive personalized learning recommendations**. Instructors can create and manage courses, while real-time communication fosters interactive learning. The platform is available as a **web and mobile application**.

## Repository Structure
The project is divided into multiple repositories, each handling a specific functionality within the microservices architecture:

| Repository | Tech Stack | Functionality |
|------------|-----------|--------------|
| [elevateed-backend-auth](https://github.com/ElevateEdOrg/elevateed-backend-auth) | Python, Django | User authentication & role management |
| [elevateed-backend-chat](https://github.com/ElevateEdOrg/elevateed-backend-chat) | Node.js, Express | Chat module for student-instructor communication |
| [elevateed-backend-course](https://github.com/ElevateEdOrg/elevateed-backend-course) | Node.js, Express | Course management (creation, enrollment, updates) |
| [elevated-api-gateway](https://github.com/ElevateEdOrg/elevated-api-gateway) | Node.js, Express | API Gateway for routing, authentication, and load balancing |
| [elevated-frontend-web](https://github.com/ElevateEdOrg/elevated-frontend-web) | Vite, React | Web frontend for students & instructors |
| [elevated-frontend-app](https://github.com/ElevateEdOrg/elevated-frontend-app) | React Native | Mobile application for course access & assessments |
| [elevated-ai-ml](https://github.com/ElevateEdOrg/elevated-ai-ml) | Python | AI models for assessments & personalized recommendations |

## Current Project Status
### **Completed**
✅ **Frontend**
- Home Page (Top courses, Browse by category, Popular instructors, Course previews)
- Search & Filtering (By title, description, price range, rating, category)
- Auth Module (Login, Signup, Profile Management)
- User Enrolled Courses Section
- Chat Module (Real-time messaging with notifications)
- Cart Module (Session storage, Course checkout flow)

✅ **Backend Services**
- Authentication service implemented (Django-based)
- Chat microservice completed (Node.js, WebSockets)
- Course management microservice implemented (CRUD operations)

✅ **AI/ML**
- AI models for assessments and recommendations are ready

### **In Progress**
⏳ **Backend APIs & Features**
- AI Service APIs need to be developed and integrated
- Course creation & management APIs are pending
- Payment integration for paid courses

⏳ **Frontend Features**
- Paid Course Page UI development
- SuperAdmin Panel UI implementation

### **Upcoming Milestones**
📌 **Day 10-12:** Complete AI Service API development & integrate with frontend
📌 **Day 12-13:** Finalize payment integration & test transaction workflows
📌 **Day 13-14:** Complete SuperAdmin Panel & refine UI/UX
📌 **Day 14:** Deployment on AWS & final testing

## Deployment Plan
- Each microservice will be deployed independently using **Docker & AWS (EC2, S3, RDS, Lambda)**
- API Gateway will handle **routing, authentication, and load balancing**
- Frontend apps will be hosted on **Vercel (web) & Google Play Store/App Store (mobile)**

## How to Contribute
1. **Fork** the repository you want to contribute to.
2. **Clone** it locally and create a new feature branch.
3. **Commit** your changes and push them to your fork.
4. **Create a Pull Request** to merge changes into the main branch.

## Team Structure
| Name | Role | Responsibilities |
|------|------|-----------------|
| Yash Solanki | Full-Stack Developer | Course Management, Chat System (MERN) |
| Premsingh | Full-Stack Developer | Course Management, Chat System (MERN) |
| Harsh Dadiya | AI/ML Developer | AI Assessments & Personalized Recommendations |
| Janvi Patel | Backend Developer | API Gateway, Authentication (Django) |
| Vraj Patel | Mobile Developer | Mobile App Development (React Native) |

## Contact
For any queries, reach out via [GitHub Issues](https://github.com/org-name) or email the respective team members.

---
This README will be updated as the project progresses. 🚀

