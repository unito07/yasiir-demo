# 🚗 Yasiir Demo

A modern ride-hailing platform built with Next.js, Java Spring Boot, and PostgreSQL.

## 🚀 Features

- 🔐 **Secure Authentication**
  - JWT-based auth
  - Role-based access control
  - Phone verification

- 📍 **Location Services**
  - Real-time tracking
  - Route optimization
  - Geofencing

- 🎯 **Smart Booking**
  - Intelligent driver matching
  - Dynamic pricing
  - Route optimization

- 💳 **Payments**
  - Secure transactions
  - Multiple payment methods
  - Digital receipts

## 🛠️ Tech Stack

### Frontend
- Next.js 14
- Tailwind CSS
- shadcn/ui
- Google Maps API

### Backend
- Java Spring Boot 3
- PostgreSQL + PostGIS
- Redis
- WebSocket

### Infrastructure
- Cloudflare
- ElephantSQL
- Render

## 📦 Project Structure

```
yasiir-demo/
├── frontend/                # Next.js frontend
│   ├── src/
│   │   ├── app/            # Pages
│   │   ├── components/     # UI components
│   │   └── lib/           # Utilities
│   └── package.json
│
└── backend/                # Java Spring Boot
    ├── src/
    │   └── main/
    │       ├── java/      # Source code
    │       └── resources/ # Configuration
    └── pom.xml
```

## 🚦 Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/unito07/yasiir-demo.git
cd yasiir-demo
```

2. **Setup frontend**
```bash
cd frontend
npm install
npm run dev
```

3. **Setup backend**
```bash
cd backend
./mvnw spring-boot:run
```

4. **Setup database**
- Install PostgreSQL
- Create database
- Run migrations

## 📱 Screenshots
[Coming soon]

## 🤝 Contributing
Contributions are welcome! Please read our contributing guidelines.

## 📝 License
MIT