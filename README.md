<h1 align="center">To-Do List</h1>

## Installation

### Step 1: Adding .env in todolist-backend

```bash
# ================================
# Database Configuration
# ================================
DB_USERNAME=postgres
DB_PASSWORD=

# ================================
# Mail Configuration (App Password của Gmail)
# ================================
MAIL_USERNAME=
MAIL_PASSWORD=" "

# ================================
# Google OAuth2 Configuration
# ================================
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

# ================================
# JWT Configuration
# ================================
JWT_SECRET=MySuperSecureJwtSecretKey1234567890
JWT_EXPIRATION=86400000

# ================================
# Server Configuration
# ================================
PORT=8080
```

### Step 2: In todolist run docker

```bash
docker compose up --build -d
```

If you want to delete the container then run:

```bash
docker compose down -v
```