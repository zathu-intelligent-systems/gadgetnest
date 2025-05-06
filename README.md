# gadgetnest
GadgetNest is a practice e-commerce system designed to simulate an online tech store selling tech gadgets. It demonstrates core concepts of transactional software, user management, product listings, and local image storage using a React Front End and Java Back End.

---

## Team

**Innocent Emmanuel Ngwenya** (System Analyst) <br> 
Email: ngwenyahinnocent@gmail.com <br>
Phone: +265 882 90 54 18 / +265 992 28 38 46 <br>
LinkedIn: [Innocent Ngwenya](www.linkedin.com/in/innocent-ngwenya-37873a326) <br>
WhatsApp: [Chat on WhatsApp](https://wa.me/265992283846) <br>
 <br>
**James Prince Goba** (Frontend Designer) <br>
Email: jamesprincegoba@gmail.com <br>
Phone: +265 881 46 37 01 / +265 991 51 24 41 <br>
LinkedIn: [Prince James Goba](www.linkedin.com/in/prince-james-goba-021b95212) <br>
WhatsApp: [Chat on WhatsApp](https://wa.me/265991512441) <br>
 <br>
**Prince Wycliff Dickson** (Frontend Developer) <br>
Email: princed.wycliff@outlook.com <br>
Phone: +265 886 29 24 23 / +265 993 82 72 85 <br>
LinkedIn: [Prince Dickson](www.linkedin.com/in/prince-dickson-906149281) <br>
WhatsApp: [Chat on WhatsApp](https://wa.me/265886292423) <br>
 <br>
**John Kabatika Chirwa (Backend Developer)** <br>
Email: [kingmlowoka16@outlook.com](mailto:kingmlowoka16@outlook.com) <br>
Phone: +265 998 21 24 66 / +265 881 88 94 87 <br>
LinkedIn: [John Kabatika Chirwa](https://linkedin.com/in/king-mlowoka-a7813a320) <br>
WhatsApp: [Chat on WhatsApp](https://wa.me/265881889487) <br>

---

## Features

- User registration and authentication
- Product listing with image uploads
- Shopping cart and checkout flow
- Admin dashboard for product management
- Local storage for product assets
- Clean API architecture

---

## Tech Stack

| Layer            | Technology       |
|------------------|------------------|
| Frontend         | React            |
| Backend          | Java, Spring Boot|
| Database         | PostgreSQL       |
| Version Control  | Git & Github     |

---

## Project Structure

```
gadgetnest/
│── backend/                     # Spring Boot Backend
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/gadgetnest/    # Where all Java code is stored
│   │   │   ├── resources/      # For static images and application settings
│   │   ├── test/               # Unit & Integration Tests
│   ├── Dockerfile              # Backend Docker Config
│   ├── pom.xml                 # Maven Dependencies
│   ├── README.md               # Backend Documentation
│
│── frontend/                   # React Frontend
│   ├── public/                 # Public Assets (index.html, favicon)
│   ├── src/
│   ├── package.json            # Dependencies
│   ├── Dockerfile              # Frontend Docker Config
│   ├── README.md               # Frontend Documentation
│
│── database/                   # Database Configurations
│   ├── init.sql                # Initial Schema & Sample Data
│   ├── migrations/             # Database Migrations
│
│── docker-compose.yml          # Docker Configuration for Backend & Frontend
│── .gitignore                  # Git Ignore for Unnecessary Files
│── LICENSE                     # Project Overview & Setup Guide
│── README.md                   # Project Overview & Setup Guide
```
---

## Project Setup

### 1. Clone the Repository

```bash
git clone https://github.com/zathu-intelligent-systems/gadgetnest.git
cd gadgetnest
```

### 2. Frontend Setup

The frontend is built using React for a modern and responsive user experience. it communicates with the backend via RESTful APIs and provides features such as product browsing, cart managemen, and user authentication. Refer to the README.MD file in the frontend folder on instructions for setting up the frontend 

### 2. Backend Setup

The backend is built using Java and Spring Boot. It handles all core business logic, REST APIs, user authentication, product management, and connects to a PostgreSQL database. Refer to the README.MD file in the backend folder on instructions for setting up the backend

---

## License

This project is licensed under the [MIT License](LICENSE)
