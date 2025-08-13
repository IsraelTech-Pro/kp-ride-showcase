# 🚖 KP Ride — Ride-Hailing Platform (Bolt-like)

A complete **ride-hailing system** built with Flutter and Supabase, featuring:
- **Rider App** – For customers to book rides
- **Driver App** – For drivers to accept and complete trips
- **Admin Dashboard** – For managing rides, drivers, and users

This is a showcase repository containing cleaned versions of all apps **(no API keys)** and screenshots.

---

## 📱 Rider App
The Rider app allows users to:
- Sign in using Google
- View their current location on **Google Maps**
- Search destinations with **Google Places**
- View available drivers in real-time
- Request a ride & track driver arrival
- View ride history

### Screenshots
| Loading Screen | Login | Home | Request Ride |
|---------------|-------|------|--------------|
| ![Rider Loading](assets/rider-Loading_screen.png) | ![Rider Login](assets/rider-login.png) | ![Rider Home](assets/rider-home.png) | ![Rider Request Ride](assets/rider-request-ride.png) |

| Looking for Driver | Pickup & Dropoff | My Rides 1 | My Rides 2 |
|--------------------|------------------|------------|------------|
| ![Rider Looking for Driver](assets/rider%20looking-for-driver-page.png) | ![Rider Pickup Dropoff](assets/rider-pickup-dropoff-page.png) | ![Rider My Rides 1](assets/rider-myRides1.png) | ![Rider My Rides 2](assets/rider-myRides2.png) |

| Profile | About |
|---------|-------|
| ![Rider Profile](assets/rider-profile.png) | ![Rider About](assets/rider-about-page.png) |

---

## 🚗 Driver App
The Driver app allows drivers to:
- Sign in using Google
- Go online/offline
- View ride requests in real-time
- Accept or reject rides
- Get navigation assistance via Google Maps
- Mark rides as completed

### Screenshots
| Login | Offline Homepage | Online Homepage | Ride Request |
|-------|------------------|-----------------|--------------|
| ![Driver Login](assets/driver-login.png) | ![Driver Offline](assets/driver-offline-homepage.png) | ![Driver Online](assets/driver-online-homepage.png) | ![Driver Ride Request](assets/driver-ride-request.png) |

| My Rides 1 | My Rides 2 | Earnings | Support |
|------------|-----------|----------|---------|
| ![Driver My Rides 1](assets/driver-my-rides-page1.png) | ![Driver My Rides 2](assets/driver-my-rides-page2.png) | ![Driver Earnings](assets/driver-earning-page.png) | ![Driver Support](assets/driver-support-page.png) |

---

## 🖥️ Admin Dashboard
The web-based dashboard allows admins to:
- View all registered riders & drivers
- Track ongoing rides in real-time
- Manage user accounts
- View ride history and statistics
- Respond to feedback

### Screenshots
| Login | Main Dashboard | Drivers |
|-------|----------------|---------|
| ![Dashboard Login](assets/dashboard-login-page.png) | ![Dashboard Main](assets/dashboard-main-page.png) | ![Dashboard Drivers](assets/dashboard-drivers-page.png) |

| Rides | Earnings | Feedback Response |
|-------|----------|-------------------|
| ![Dashboard Rides](assets/dashboard-rides-page.png) | ![Dashboard Earnings](assets/dashboard-earnings-page.png) | ![Dashboard Feedback](assets/dashboard-feedback-response-page.png) |

---

## 🛠 Tech Stack
**Frontend (All Apps)**
- Flutter (Dart)
- Google Maps API
- Google Places API
- Supabase (Auth, DB, Realtime)
- Go Router
- Lottie Animations

**Backend**
- Supabase (PostgreSQL + Realtime subscriptions)
- REST APIs (Laravel/Node.js compatible)

**Other**
- Geolocator & Geocoding
- Push Notifications
- Image Picker
- Vibration Feedback
- Polyline Navigation

---


---

## 📜 License
This project is for **portfolio demonstration only**. Commercial use is not permitted without permission.

---

