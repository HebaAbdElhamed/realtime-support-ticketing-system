# 🎫 Realtime Support Ticketing System

A full-featured **Support Ticketing System** with real-time capabilities, built using **Laravel 12**, **React**, **GraphQL**, and other modern technologies. It includes role-based access, live chat, email notifications, Google Sign-In, OTP authentication, and magic link support for password resets.

---

## 🚀 Features

- 🧑‍💼 Role-based access (Admins & Users)
- 💬 Real-time chat inside tickets
- 🔔 Real-time notifications for ticket updates and new messages
- 🔐 Google Sign-In via OAuth
- 📩 Email OTP for secure login and verification
- 🪄 Magic link support for forgotten password recovery
- ✅ Mark notifications as read
- 📂 Open/Close ticket management
- 🎨 Responsive and clean UI with TailwindCSS
- 🔄 GraphQL Subscriptions using Laravel Broadcasting

---

## 🛠️ Tech Stack

| Layer        | Technology                            |
|--------------|----------------------------------------|
| Backend      | Laravel 12                             |
| Auth         | Sanctum (session-based)                |
| API          | Lighthouse GraphQL                     |
| Frontend     | React + Vite                           |
| GraphQL      | Apollo Client                          |
| Styles       | TailwindCSS                            |
| Notifications| Laravel Notifications + GraphQL        |
| Realtime     | Laravel Broadcasting + WebSockets      |
| Icons        | React Icons                            |
| Email        | Laravel Mail for OTP & Magic Links     |

---

## 📦 Installation

### Backend (Laravel 12 + Lighthouse)

```bash
# Clone the repository
git clone https://github.com/HebaAbdElhamed/realtime-support-ticketing-system.git
cd realtime-support-ticketing-system

# Install PHP dependencies
composer install

# Configure environment
cp .env.example .env
php artisan key:generate

# Migrate the database
php artisan migrate

# Run the server
php artisan serve
```

### Frontend (React + Apollo)

```bash
cd ../frontend

# Install JS dependencies
npm install

# Run development server
npm run dev
```

---

## 🔐 Authentication

- **Google Sign-In** for users who prefer social login.
- **OTP via Email** sent during login or registration.
- **Magic Link** for password recovery with expiration control.
- **Sanctum session-based** authentication handled by Laravel.

---

## 📸 Screenshots

> *(Add actual screenshots or UI previews if available)*

```
📂 screenshots/
├── dashboard.png
├── chat-view.png
└── notifications.png
```

---

## 💡 Use Cases

- Customer support ticketing inside web applications
- Internal team communication & issue tracking
- Real-time admin-user collaboration for problem solving

---

## 👤 Author

**Heba Elgohary**  
🔗 [GitHub Profile](https://github.com/HebaAbdElhamed)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🏷️ Tags / Topics

`laravel` `react` `graphql` `apollo-client` `support-system` `ticketing` `realtime` `notifications` `sanctum` `lighthouse` `google-login` `otp` `magic-link` `tailwindcss`

---