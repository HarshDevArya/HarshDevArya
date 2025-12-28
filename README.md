# Hello, I'm Harsh Dev! 👋                  <img align="center" src="https://komarev.com/ghpvc/?username=HarshDevArya&color=green" alt="HarshDevArya" />


## 🙋‍♂️ About Me

As a full-stack web development educator with expertise in MongoDB, React, Node, and Express, I blend teaching with practical application, creating projects that showcase dynamic and scalable web solutions. My solid foundation in Python and C/C++ enriches my development skill set. I am passionate about mentoring aspiring developers and preparing them for real-world challenges.

Open to exploring full-time web developer roles, I aim to leverage my unique blend of teaching experience and technical expertise to contribute to innovative projects and create exceptional digital experiences.


- 🔭 I’m currently working on web development projects that leverage my full-stack skills to solve real-world problems.
- 🌱 I’m continuously improving my skills in MongoDB, React, Node, and Express, while also exploring new technologies in the web development ecosystem.
- 👯 I’m looking to collaborate on projects that are at the intersection of education and web development.
- 📫 How to reach me: `harshdevarya09@gmail.com`
- ⚡ Fun fact: `I am Happy.`

## 💻 Technologies & Tools

| Frontend | Backend | Database | Languages | Design | Tools |
|----------|---------|----------|-----------|--------|-------|
| ![](https://img.shields.io/badge/Code-HTML5-informational?style=flat&logo=html5&logoColor=white&color=E34F26) <br> ![](https://img.shields.io/badge/Code-CSS3-informational?style=flat&logo=css3&logoColor=white&color=1572B6) <br> ![](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=javascript&logoColor=white&color=F7DF1E) <br> ![](https://img.shields.io/badge/Code-React-informational?style=flat&logo=react&logoColor=white&color=2bbc8a) <br> ![](https://img.shields.io/badge/Framework-Next.js-informational?style=flat&logo=nextdotjs&logoColor=white&color=2bbc8a) | ![](https://img.shields.io/badge/Code-Node.js-informational?style=flat&logo=node.js&logoColor=white&color=2bbc8a) <br> ![](https://img.shields.io/badge/Code-Express.js-informational?style=flat&logo=express&logoColor=white&color=000000) | ![](https://img.shields.io/badge/Database-MongoDB-informational?style=flat&logo=mongodb&logoColor=white&color=47A248) | ![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=3776AB) <br> ![](https://img.shields.io/badge/Code-C%2FC%2B%2B-informational?style=flat&logo=c%2B%2B&logoColor=white&color=00599C) | ![](https://img.shields.io/badge/Design-Figma-informational?style=flat&logo=figma&logoColor=white&color=F24E1E) <br> ![](https://img.shields.io/badge/Design-Canva-informational?style=flat&logo=canva&logoColor=white&color=00C4CC) | ![](https://img.shields.io/badge/Tools-Git-informational?style=flat&logo=git&logoColor=white&color=2bbc8a) |




## Projects

### Learning Management System (LMS) for Advanced Tech Labs.

Developed as a pivotal solution for Advanced Tech Labs, this Learning Management System (LMS) is tailored to meet the unique educational and training needs of our organization. This project underscores our commitment to leveraging technology to enhance learning outcomes and operational efficiency within the company.

Key Features:
- **Customized Course Management:** Designed specifically for our corporate environment, enabling seamless creation, customization, and management of courses to align with our organizational goals and employee skill development.
- **Integrated Assessment Tools:** Features robust tools for quizzes, assignments, and grading, facilitating effective evaluation and feedback mechanisms for employee performance enhancement.
- **Employee and Management Dashboards:** Offers personalized dashboards for employees for learning progress tracking and for managers to monitor and analyze training effectiveness.
- **Interactive Forums:** Encourages knowledge sharing and collaboration among employees, fostering a learning community within our organization.
- **Corporate Analytics:** Advanced analytics tailored to corporate needs, providing insights into course effectiveness, employee engagement, and learning outcomes.

Technologies Used:
- **Frontend:** Utilizes HTML, CSS, and JS for a dynamic and responsive user interface, ensuring a seamless user experience for our employees.
- **Backend:** Built with Node.js and Express.js, ensuring robust server-side logic, efficient API management, and seamless database interactions.
- **Database:** Employs MongoDB for its scalable storage solutions, accommodating our growing organizational data needs.
- **Design and Prototyping:** Designed with Figma, ensuring a user-friendly interface that meets our corporate branding and usability standards.

---

### 🐔 Mommy’s Chicken – Consumer Ordering Platform  
**Full-stack, location-aware food ordering system used by real customers**

**Overview**  
Built a production-grade food-tech platform supporting multi-city operations, hub-based delivery, and real-time POS integration. The system ensures users only see products that can actually be delivered to their location.

**Key Contributions**
- Implemented location-based serviceability using Maps and distance APIs to assign the nearest delivery hub.
- Built hub-level product visibility to prevent orders from inactive or out-of-range locations.
- Integrated PetPooja POS for real-time synchronization between online orders and store operations.
- Designed intelligent order routing mapped to the correct city and PetPooja outlet.
- Implemented delivery slot validation, coupon logic, and checkout safeguards.
- Optimized frontend performance and UX for mobile-first, high-traffic usage.

**Tech Stack:** Next.js, React, Node.js, Express, MongoDB, Google Maps API, PetPooja POS, Payment Gateway

---

### ⚙️ Mommy’s Chicken Admin System – Operations & Control Platform  
**Internal system powering daily operations and integrations**

**Overview**  
Built a secure admin platform that acts as the operational backbone of Mommy’s Chicken, managing hubs, inventory, orders, and third-party integrations.

**Key Contributions**
- Developed hub management with delivery radius, service zones, and active/inactive controls.
- Mapped hubs to PetPooja outlets to ensure accurate POS synchronization.
- Built real-time order monitoring with hub assignment and sync status.
- Added admin workflows for cancellations, refunds, and operational overrides.
- Implemented role-based access for operations, support, and management teams.
- Ensured strict data consistency between the consumer app and admin system.

**Tech Stack:** React, Next.js, Node.js, Express, MongoDB, PetPooja POS, Role-based Authentication

---

### 📋 Task & HR Management System  
**Task, time tracking, and productivity platform (ClickUp / Zoho-style)**

**Overview**  
Designed and built a task and time management system focused on accountability, accurate work tracking, and productivity insights for teams.

**Key Contributions**
- Built project-based task management with ownership and status workflows.
- Implemented real-time start/stop timers with auto-stop and global timer visibility.
- Added manual time logging with flexible formats such as `1h 30m` or `2h`.
- Built task-wise and user-wise timesheets with calendar views.
- Logged all actions in activity feeds for audit and accountability.
- Designed role-based permissions for secure task and time management.

**Tech Stack:** Next.js, React, Node.js, Express, MongoDB, NextAuth

---

## 🧠 System Highlights (Architecture Thinking)

- **Location-Driven Architecture**  
  Orders are validated using live location APIs before checkout to ensure hub-level feasibility.

- **Multi-Hub Routing Logic**  
  Each order is dynamically assigned to the nearest active hub and corresponding PetPooja outlet.

- **Third-Party POS Integration**  
  Reliable synchronization with PetPooja, including error handling and retry mechanisms.

- **Operational Safeguards**  
  Prevented overselling and invalid orders through inventory visibility, hub status checks, and delivery cutoffs.

- **Scalable Data Modeling**  
  MongoDB schemas are designed to support growth across cities, users, and operational roles.

- **Audit & Accountability**  
  Centralized activity logs and timesheets provide full traceability across systems.

---

## 📈 GitHub Stats
<p align="left">
  <a href="https://github.com/HarshDevArya">
      <img src="https://github-readme-stats-one-bice.vercel.app/api?username=HarshDevArya&show_icons=true&theme=radical" />
  </a>
</p>
<p align = "right">
<p align="left">
<a href="https://github.com/HarshDevArya">
     <img src="https://github-readme-stats-one-bice.vercel.app/api/top-langs/?username=HarshDevArya&layout=compact&theme=radical" />
  </a>
</p>

## 📫 How to Reach Me

- LinkedIn: [Harsh Dev](https://www.linkedin.com/in/harsh-dev-v)
- Twitter: [@Harsh_DevArya](https://twitter.com/Harsh_DevArya)
<!--
- Email: <Your Email>
-->
