<!-- Banner -->
<div align="center">

```
~/thaiduong1705 $ whoami
```

# Dương Minh Thái

**Backend Engineer** · Go & Node.js · Ho Chi Minh City 🇻🇳

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dmthai-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/dmthai)
[![Email](https://img.shields.io/badge/Email-thaiduong7v.work%40gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:thaiduong7v.work@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-thaiduong1705-181717?style=flat-square&logo=github)](https://github.com/thaiduong1705)

</div>

---

## 🛠 Tech Stack

```
Languages   │ Go (Golang) · Node.js (Express, NestJS)
Backend     │ RESTful APIs · gRPC · WebSocket · Microservices · Asynq
Databases   │ PostgreSQL · MySQL · MongoDB · Redis
DevOps      │ Docker · GitHub Actions · Linux
Auth        │ JWT · OAuth 2.0 · RBAC · Casbin
Integrations│ VNPay · ZaloPay · Momo · GHN Shipping
Cloud       │ AWS Lambda · S3 · SQS · SNS · EventBridge · KMS
```

---

## 🚀 Featured Projects

### 📣 Public Messaging & Announcement System
`Go` `gRPC` `AWS Lambda` `SQS` `EventBridge` `Casbin` `VueJS`

Government-scale notification platform serving push notifications to citizens.
- Event-driven Lambda with per-use-case trigger strategies (SQS → email, EventBridge → push, S3 → image resize)
- Pessimistic locking (`SELECT FOR UPDATE`) to prevent duplicate notifications under concurrent broadcast
- Multi-tenant RBAC via Casbin with domain-scoped policies — stored on S3 for zero-downtime updates

---

### 🍱 Internal Food Ordering Platform
`Go` `ReactJS` `PostgreSQL` `Redis` `WebSocket` `Asynq`

Real-time canteen ordering system deployed across 2+ corporate sites.
- Kiosk interface with WebSocket live order updates, QR-code scanning & face-recognition login (~30% faster meal retrieval)
- Async batch pipeline: checkout events buffered in Redis → flushed every 5 min, reducing peak-hour DB write load
- Redis menu cache with 30-min TTL, cutting redundant reads on frequently accessed data

---

### 💳 E-commerce Cosmetic Platform
`Go` `PostgreSQL` `Redis` `ReactJS`

Full-featured cosmetic storefront with multi-gateway payment and 3PL integration.
- Strategy Pattern abstraction for VNPay / ZaloPay / Momo — new gateway = new class, zero changes to order logic
- Webhook handlers with per-gateway HMAC signature validation before processing callbacks
- GHN API integration for automated shipping order creation, fee calculation & status tracking

---

### 🛒 Food Selling Online Shop *(personal)*
`Node.js` `MongoDB` `Redis` `Docker`

[github.com/thaiduong1705](https://github.com/thaiduong1705)

- Full eCommerce REST API with JWT auth + configurable voucher engine (min order value, usage caps, expiry)
- Redis distributed locking to prevent overselling under concurrent submissions
- Containerized with Docker Compose (app + MongoDB + Redis)

---

## 📊 Stats

<div align="center">

| 🎓 Education | 📝 English | 💼 Experience |
|:---:|:---:|:---:|
| UIT — Software Engineering | TOEIC L&R 830/990 | Software Engineer @ AIPower |
| GPA 8.16/10 | S&W 320/400 | Jun 2024 – Present |

</div>

---

<div align="center">
  <sub>Open to opportunities · <a href="mailto:thaiduong7v.work@gmail.com">thaiduong7v.work@gmail.com</a></sub>
</div>
