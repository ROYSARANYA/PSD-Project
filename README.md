# 📁 PSD-Project – Project Management Tool

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [Maintainers](#maintainers)
- [License](#license)


Managing multiple projects, teams, and deadlines can quickly become overwhelming—especially when using a patchwork of tools that don't integrate well. PSD-Project was created to streamline that chaos.

This tool is ideal for small-to-medium development teams, startups, academic project groups, and freelance managers. It offers a unified interface for handling:

- Project creation and tracking
- Team and user role management
- Task visibility by project
- Email-based task notifications
- Simple user registration and authentication

## Install

Make sure you have the following installed:
- Node.js (v18 or later)
- Docker & Docker Compose

Then clone the repository and run:

```bash
git clone https://github.com/your-username/PSD-Project.git
cd PSD-Project
docker compose up --build


Usage
Once the containers are up, visit:

Frontend: http://localhost:3000
Backend API: http://localhost:5000

The app includes:

Registration/Login

Dashboard with user-specific project visibility
Project creation/editing
User role management
Email task notifications

Project Structure:
PSD-Project/
├── backend/
│   ├── models/                # Mongoose models
│   ├── routes/                # Express routes (auth, project, users)
│   ├── emailService.js        # Nodemailer setup
│   ├── index.js               # Backend entry
│   └── Dockerfile
│
├── frontend/
│   ├── public/                # Static assets
│   ├── src/app/               # Next.js app directory
│   │   ├── login, register/
│   │   ├── dashboard/
│   │   ├── projects/
│   │   ├── settings/
│   │   └── components/
│   └── Dockerfile
│
├── docker-compose.yml         # Docker multi-service config
└── README.md



## Built With

- [Next.js](https://nextjs.org/) – Frontend framework
- [TypeScript](https://www.typescriptlang.org/) – Typed JavaScript
- [Node.js](https://nodejs.org/) – Backend runtime
- [Express.js](https://expressjs.com/) – Web framework for Node.js
- [MongoDB](https://www.mongodb.com/) – NoSQL database
- [Docker](https://www.docker.com/) – Containerization
- [Tailwind CSS](https://tailwindcss.com/) – Styling framework


Contributing Section:-
We welcome contributions to improve PSD-Project!  
Follow these simple steps to get started:

### Contribution Workflow
1. Fork this repository.
2. Clone your fork:
    ```bash
    git clone https://github.com/your-username/PSD-Project.git
    ```
3. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
4. Make and test your changes.
5. Commit your changes with clear messages.
6. Push your branch and open a Pull Request.

