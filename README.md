<div align="center">
  
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="src/banner.png">
  <source media="(prefers-color-scheme: light)" srcset="src/banner.png">
  <img src="src/banner.png" alt="Personal banner showing Andrew Prasetya, Full Stack Developer">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="Divider">
</picture>

</div>

```python
class Developer:
    def __init__(self):
      self.name = "Andrew Prasetya"
      self.role = "Full-Stack Developer"
      self.location = "Tangerang, Indonesia"

    def say_hi(self):
      return """
      👋 Hello there!
      I'm a final-year Computer Science student at Universitas Kristen Satya Wacana, currently interning
      at PT Lancar Wiguna Sejahtera (Lawson), developing internal business applications using ReactJS, Vue.js, Python, and Oracle Database.
      My current focus is developing and optimising backend endpoints, system design, API development, and scalable software architecture,
      as well as building frontend and UI using Node.js tailored to user needs and business goals.
      Passionate about optimising data transfer and delivering user-centric solutions.
      """

# Initialize
me = Developer()
print(me.say_hi())
```

<picture>
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="Divider">
</picture>

### Languages

<p align="center">
  <a href="#"><img src="https://skillicons.dev/icons?i=go,python,js,php,java" alt="Languages 1"/></a>
  <a href="#"><img src="https://skillicons.dev/icons?i=c,cpp,ts" alt="Languages 2"/></a>
</p>

### Frontend

<p align="center">
  <a href="#"><img src="https://skillicons.dev/icons?i=vuejs,react,tailwind,bootstrap,nextjs" alt="Frontend"/></a>
</p>

### Backend

<p align="center">
  <a href="#"><img src="https://skillicons.dev/icons?i=flask,go,laravel,spring,nestjs" alt="Backend"/></a>
</p>

### Database

<p align="center">
  <a href="#"><img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis,mongodb" alt="Databases"/></a>
  <br>
  <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle"/>
</p>

<picture> 
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="Divider">
</picture>

## Featured Projects

<div align="center">

### EduVerse — Multi-School Learning Management System

<table>
  <tr>
    <td width="50%">
      <b>Description:</b>
      <br>
      EduVerse is a multi-tenant Learning Management System (LMS) designed to support academic management across multiple schools. The platform provides role-based access control, class management, learning materials, assignments, assessments, and academic workflows within a scalable architecture.
      <br><br>
      <b>Highlights:</b>
      <ul>
        <li>Built RESTful APIs using Go (Gin) and PostgreSQL with GORM</li>
        <li>Implemented JWT Authentication and Role-Based Access Control (RBAC)</li>
        <li>Designed multi-tenant architecture with isolated academic data per school</li>
        <li>Developed student portal, teacher portal, school admin dashboard, and superadmin web app with Vue.js</li>
        <li>Applied layered architecture (Handler → Service → Repository)</li>
        <li>Won 1st Place in university-wide UI/UX competition</li>
      </ul>
      <br>
      <b>Tech Stack:</b>
      <br>
      <img src="https://img.shields.io/badge/Gin-00ADD8?style=flat&logo=go&logoColor=white" alt="Gin"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white" alt="Vue.js"/>
      <br><br>
      <a href="https://github.com/andrewprasetya-k/eduverse-backend">
        <img src="https://img.shields.io/badge/View%20on%20GitHub-58a6ff?style=for-the-badge&logo=github&logoColor=white&labelColor=0a0e27" alt="GitHub"/>
      </a>
    </td>
    <td width="50%">
      <img src="/src/ev_student.png" alt="EduVerse Screenshot" width="100%" style="border-radius: 8px; border: 2px solid #58a6ff"/>
      <br>
      <img src="/src/ev_teacher.png" alt="EduVerse Screenshot" width="100%" style="border-radius: 8px; border: 2px solid #58a6ff"/>
      <br>
      <img src="/src/ev_admin.png" alt="EduVerse Screenshot" width="100%" style="border-radius: 8px; border: 2px solid #58a6ff"/>
    </td>

  </tr>
</table>

---

### PMI Kota Salatiga — Blood Donation Information System

<table>
  <tr>
    <td width="50%">
      <img src="/src/pmi_landing.png" alt="PMI Landing Page" width="100%" style="border-radius: 8px; border: 2px solid #58a6ff; margin-bottom: 8px"/>
      <br>
      <img src="/src/pmi_admin.png" alt="PMI Admin Dashboard" width="100%" style="border-radius: 8px; border: 2px solid #58a6ff; margin-bottom: 8px"/>
      <br>
      <img src="/src/pmi_rs.png" alt="PMI RS View" width="100%" style="border-radius: 8px; border: 2px solid #58a6ff"/>
    </td>
    <td width="50%">
      A full-stack information system for PMI (Indonesian Red Cross) Kota Salatiga to manage blood donation scheduling, donor records, and public information services. Published as a final academic project.
      <br><br>
      <b>Highlights:</b>
      <ul>
        <li>Built RESTful APIs and backend workflows using Laravel and PostgreSQL</li>
        <li>Developed public-facing portal, admin dashboard with ReactJS, and hospital admin dashboard with ReactJS</li>
        <li>Implemented JWT Authentication and Role-Based Access Control (RBAC)</li>
        <li>Published academic research project</li>
      </ul>
      <br>
      <b>Tech Stack:</b>
      <br>
      <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white" alt="Laravel"/>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" alt="ReactJS"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      <br><br>
      <a href="https://github.com/andrewprasetya-k/pmi-salatiga">
        <img src="https://img.shields.io/badge/View%20on%20GitHub-58a6ff?style=for-the-badge&logo=github&logoColor=white&labelColor=0a0e27" alt="GitHub"/>
      </a>
    </td>
  </tr>
</table>

---

### Chat App — Real-Time Messaging Application

<table>
  <tr>
    <td width="50%">
      <b>Description:</b> A real-time chat application supporting instant message delivery through WebSocket-based communication, with persistent message history stored in PostgreSQL.
      <br><br>
      <b>Highlights:</b>
      <ul>
        <li>Built real-time messaging with NestJS WebSocket Gateways</li>
        <li>Persistent chat history with PostgreSQL</li>
        <li>Server-side rendered frontend using Next.js</li>
      </ul>
      <br>
      <b>Tech Stack:</b>
      <br>
      <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white" alt="NestJS"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      <img src="https://img.shields.io/badge/WebSocket-010101?style=flat&logo=socketdotio&logoColor=white" alt="WebSocket"/>
      <br><br>
      <a href="https://github.com/andrewprasetya-k/chat-app">
        <img src="https://img.shields.io/badge/View%20on%20GitHub-58a6ff?style=for-the-badge&logo=github&logoColor=white&labelColor=0a0e27" alt="GitHub"/>
      </a>
    </td>
    <td width="50%">
      <img src="https://raw.githubusercontent.com/andrewprasetya-k/chat-app/main/screenshot.png" alt="Chat App Screenshot" width="100%" style="border-radius: 8px; border: 2px solid #58a6ff"/>
    </td>
  </tr>
</table>

---

### Lynks — URL Shortener with Analytics

<table>
  <tr>
    <td width="50%">
      <img src="https://raw.githubusercontent.com/andrewprasetya-k/lynks/main/screenshot.png" alt="Lynks Screenshot" width="100%" style="border-radius: 8px; border: 2px solid #58a6ff"/>
    </td>
    <td width="50%">
      <b>Description:</b> A URL shortening service with built-in click tracking and analytics. Uses MongoDB for fast key-value-based redirection and aggregates access events per shortened URL.
      <br><br>
      <b>Highlights:</b>
      <ul>
        <li>Fast URL redirection using MongoDB key-value storage</li>
        <li>Click-tracking mechanism to record and aggregate access events</li>
        <li>Full-stack implementation with NestJS backend and Next.js frontend</li>
      </ul>
      <br>
      <b>Tech Stack:</b>
      <br>
      <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white" alt="NestJS"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js"/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" alt="MongoDB"/>
      <br><br>
      <a href="https://github.com/andrewprasetya-k/lynks">
        <img src="https://img.shields.io/badge/View%20on%20GitHub-58a6ff?style=for-the-badge&logo=github&logoColor=white&labelColor=0a0e27" alt="GitHub"/>
      </a>
    </td>
  </tr>
</table>

</div>

</div>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/andrewprasetya-k/andrewprasetya-k/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/andrewprasetya-k/andrewprasetya-k/output/github-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/andrewprasetya-k/andrewprasetya-k/output/github-snake.svg">
</picture>

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="Divider">
</picture>

</div>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=100&section=footer">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=100&section=footer">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=100&section=footer" width="100%" alt="Footer Wave">
</picture>

</div>
