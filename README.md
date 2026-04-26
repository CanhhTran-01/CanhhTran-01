# Hi there, I'm Trần Đức Cảnh 👋

**Backend Developer** · 3rd-year Student @ Academy of Cryptography Techniques (KMA) · Ha Noi City, Vietnam

I'm a passionate backend developer with a focus on Java & Spring Boot, building real-world projects to sharpen my skills and grow toward a backend engineering career. Currently in a 5-year program, I'm actively looking for an internship opportunity.

---

## 🛠️ Tech Stack

**Backend**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=spring-security&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apache-maven&logoColor=white)

**Frontend (basic)**

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

**Testing & Tools**

![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=flat&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=flat)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat&logo=cloudinary&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![JMeter](https://img.shields.io/badge/JMeter-D22128?style=flat&logo=apachejmeter&logoColor=white)

---

## 🚀 Featured Project — eCommerce Website

> Full-stack eCommerce web application (user-facing) built as a personal project to gain real-world experience and build a strong CV for internship applications.

**Architecture:** Monolith Spring Boot app with layered architecture. Frontend (HTML/CSS/Bootstrap/JS) is separated from backend and fetches data via REST API.

**Highlights:**

- 🔐 **Authentication & Security** — Spring Security + JWT with login/logout, token introspection, refresh token rotation. OAuth2 login (Google & Facebook) with local account merging to ensure email uniqueness. BCrypt password encoding. Rate limiting on login (lock after 5 failed attempts) and OTP endpoints (Redis-based).
- 📧 **OTP / Forgot Password** — Email service to generate, send, and store OTPs in Redis with TTL.
- 🛒 **Cart** — Redis hash storage with TTL auto-expiration.
- 📦 **40+ REST APIs** — Product listing, categories, discounts, orders, reviews, wishlist, user profile, order history, and more.
- 🔍 **Smart Search** — Custom repository with filter criteria. Redis ZSET for product suggestion keywords ranked by search frequency.
- 🖼️ **Image Upload** — Avatar, product, and category images uploaded to Cloudinary; only URL stored in DB.
- 🔒 **RBAC** — 4 roles: Guest, User, Seller, Admin with method-level security via `@PreAuthorize`.
- ⚡ **Performance** — Lazy/eager fetch type tuning, batch fetch + map lookup pattern to eliminate N+1 queries (verified with Hibernate statistics). Pessimistic Locking for concurrent order race conditions.
- 🧪 **Testing** — Unit tests (JUnit + Mockito) for AccountService, AuthenticationService, JWT handler. Integration tests with H2 in-memory DB for login and role-based access.
- 🐳 **Docker** — Dockerfile for Spring Boot image, Docker Compose orchestrating 3 containers (BE + MySQL + Redis) with health checks and volumes.
- 📖 **API Docs** — Swagger UI grouped by controller.

**Database:** MySQL (14 tables) + Redis · MapStruct for DTO mapping · Global exception handling with `@RestControllerAdvice` + ErrorCode enums · SLF4J logging · Custom validators.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=CanhhTran-01&show_icons=true&theme=default&hide_border=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CanhhTran-01&layout=compact&theme=default&hide_border=true" height="160"/>
</p>

---

## 📫 Contact

- 📧 [duccanh1102005@gmail.com](mailto:duccanh1102005@gmail.com)
- 📘 [Facebook](https://www.facebook.com/CT080107/)
- 💼 [LinkedIn](https://www.linkedin.com/in/cảnhh-trần-2570923b3)
