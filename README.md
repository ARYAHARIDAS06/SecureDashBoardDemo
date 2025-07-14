# 🔐 Secure Internal Dashboard with Passkey Authentication & Web Dialer

A full-stack internal dashboard using **React + Tailwind CSS** (frontend) and **Django + PostgreSQL** (backend), secured using **passkey-only (WebAuthn)** authentication. The platform allows users to manage contacts and make/receive Twilio-powered voice calls via a web dialer interface.

---

## ✨ Features

### 🔐 Secure Passkey Authentication
- WebAuthn login & registration (no passwords)
- Platform authenticators supported (Touch ID, Windows Hello, etc.)
- Uses `django-passkeys` or `webauthn` for authentication
- JWT-based authorization for secure API access

### 📇 Contact Management
- Contact table with name, phone, and notes
- Search and filter contacts
- Backend API to retrieve, create, update, delete contacts

### 📞 Web Dialer (Twilio Voice)
- Dial numbers from browser using `Twilio.Device`
- Accept incoming calls via Twilio webhook
- Call status updates: ringing, in-call, ended
- Call logs stored and accessible via API
- Incoming call popup on dashboard

---

## 🛠 Tech Stack

| Layer        | Tech                               |
|--------------|------------------------------------|
| Frontend     | React, Tailwind CSS, Vite          |
| Backend      | Django, Django REST Framework      |
| Auth         | WebAuthn (Passkey), JWT            |
| Database     | PostgreSQL                         |
| Voice API    | Twilio Voice SDK                   |



