# ShopX – E-Commerce Admin Panel

A cross-platform mobile admin panel for managing an e-commerce store end-to-end. Built with Flutter for the frontend and powered by a custom ASP.NET Core REST API with PostgreSQL.

---

## Screenshots

<!-- Add your screenshots here -->
| Dashboard | Orders | Products | Settings |
|-----------|--------|----------|----------|
| ![](screenshots/dashboard.png) | ![](screenshots/orders.png) | ![](screenshots/products.png) | ![](screenshots/settings.png) |

---

## Features

- 📦 **Product Management** – Add, edit, and delete products with image upload via Supabase Storage
- 🛒 **Order Management** – View and manage customer orders with status tracking
- 📊 **Statistics & Analytics** – Sales overview and key metrics dashboard
- 🔔 **Push Notifications** – Firebase Cloud Messaging (FCM) with topic-based delivery

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Mobile Frontend | Flutter · Dart |
| Backend | ASP.NET Core (C#) |
| Database | PostgreSQL |
| Storage | Supabase Storage |
| Notifications | Firebase Cloud Messaging |

---

## Architecture

- **Frontend:** BLoC / Cubit state management, clean widget separation
- **Backend:** 3-layer architecture (Controllers → BLL → DAL), Result<T> pattern
- **Database:** PostgreSQL with stored functions and JSONB aggregation for nested data

---
## Try It Out

[Download APK](https://github.com/YousefAbuHzian/ShopX-Admin/releases/tag/v1.0.0)

> Android only. Enable "Install from unknown sources" if prompted.
> 
---
## Contact

**Yousef Abu Hzian** – Junior Full-Stack Developer
[LinkedIn](https://linkedin.com/in/YousefAbuHzian) ·
Email : yousefabuhzian@gmail.com
