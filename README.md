# 🍲 MealBridge

## 🌍 Overview

**MealBridge** is a real-time food redistribution platform that connects surplus food donors with NGOs and volunteers to reduce food waste and fight hunger efficiently. The system enables seamless coordination through live updates, role-based dashboards, and smart matching.

## 🚀 Features

### 👤 Authentication

* Firebase Authentication (Email/Google login)
* Role-based access (Donor / NGO / Volunteer)

### 🧑‍🍳 Donor Features

* Add surplus food listings
* Specify quantity, type, expiry time, and location
* Track food status in real time
* Cancel listings if needed

### 🏢 NGO Features

* View available food listings
* Accept food requests
* Track assigned deliveries
* Real-time notifications for new food

### 🚴 Volunteer Features

* View assigned deliveries
* Update delivery status (Picked → Delivered)
* Real-time updates

### ⚡ Real-Time System

* Instant notifications using Socket.io
* Live status updates across all dashboards

### 🗺️ Map Integration

* View food locations using Leaflet + OpenStreetMap


## 🛠️ Tech Stack

### Frontend

* React
* Tailwind CSS
* Axios
* Firebase (Authentication)

### Backend

* Node.js
* Express.js
* Socket.io

### Database

* MongoDB Atlas

### Maps

* Leaflet + OpenStreetMap

### Deployment

* Frontend: Vercel
* Backend: Render / Railway
* Database: MongoDB Atlas

## 🔄 Workflow

1. Donor adds surplus food
2. NGOs receive real-time notification
3. NGO accepts request
4. Volunteer is assigned
5. Delivery status updates in real time


