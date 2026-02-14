# Todo App

Aplikasi Todo List sederhana menggunakan Spring Boot dan MySQL.

## Tech Stack
- Java 24
- Spring Boot 3.5.9
- MySQL 8.0
- Thymeleaf
- Maven

## Setup & Installation

### 1. Clone repository
```bash
git clone https://github.com/revuriiii99/todoapp.git
cd todoapp
```

### 2. Buat database MySQL
```sql
CREATE DATABASE `todo-app`;
```

### 3. Set environment variable untuk password
**Windows Command Prompt:**
```bash
set DB_PASSWORD=your_mysql_password
```

**Windows PowerShell:**
```bash
$env:DB_PASSWORD="your_mysql_password"
```

**Linux/Mac:**
```bash
export DB_PASSWORD=your_mysql_password
```

### 4. Run aplikasi
```bash
mvn spring-boot:run
```

### 5. Akses aplikasi
Buka browser dan akses: `http://localhost:8080/reviganteng`

## Features
- Create new tasks
- View all tasks
- Update tasks
- Delete tasks

## Author
revuriiii99