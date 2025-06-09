# Dockerized WordPress

This project runs a WordPress website and a MySQL database using Docker Compose.

## 🚀 Features

- WordPress container
- MySQL database container
- Persistent volumes for data
- Easy setup with Docker Compose

## 🧱 Technologies Used

- Docker
- Docker Compose
- WordPress
- MySQL 5.7

## 📦 Getting Started

### 1. Clone this repository

```bash
git clone https://github.com/your-username/dockerized-wordpress.git
cd dockerized-wordpress
```

## 2. Run Docker Compose
```bash
docker compose up -d
```

## 3. Open in browser
Go to: http://localhost:8000

Complete the WordPress installation wizard.

## 4. Stop the containers
```bash
docker compose down
```

## 🗂 Folder Structure
```bash
dockerized-wordpress/
├── docker-compose.yml
└── README.md
```

## 💾 Data Persistence
WordPress files stored in Docker volume: wordpress_data

MySQL data stored in Docker volume: db_data


## 👨‍💻 Author
Thilina Gamage

GitHub: @thilinagamage

LinkedIn: https://www.linkedin.com/in/thilinagamage010/
