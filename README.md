# 🏠 KZHomestay

## 📱 Overview
**KZHomestay** is an iOS application inspired by Airbnb, built to explore and manage homestay listings in Kazakhstan.  
The project focuses on modern iOS development using **SwiftUI**, **SwiftData**, and **MapKit**, with an emphasis on clean UI, scalable architecture, and hands-on learning.

---

## ✨ Features

### 🏡 Home (Listings)
- Display all available homestay listings
- Search by **city** or **title**
- Card-based UI with smooth navigation
- Pull-to-refresh support
- Swipe left to **delete listings**
- Empty and loading states

### ➕ Add Listing
- Create new listings with:
  - Title and description
  - City and location
  - Images
  - Host information
- Data persistence using **SwiftData**

### 🗺️ Map View
- Interactive map showing all listings
- Custom map annotations for homes
- Tap a marker to:
  - Center the map on the selected home
  - Open listing details in a modal sheet
- Automatic region adjustment based on listings

### 👤 Host Profile
- View host information
- See all homes created by a host
- Navigate to detailed listing pages

---

## 🧠 What I Did in This Project

During this project, I independently implemented and learned:

- **SwiftUI**
  - MVVM architecture
  - State management (`@State`, `@StateObject`, `@Published`)
  - Reusable UI components

- **SwiftData**
  - Local data persistence
  - Fetching, sorting, and filtering data
  - Deleting records with UI updates
  - `ModelContext` integration

- **MapKit**
  - Interactive maps with custom annotations
  - Tap gestures on map markers
  - Synchronizing map selection with UI
  - Dynamic map region calculations

- **UI / UX**
  - Swipe-to-delete gestures
  - Animations and transitions
  - User-friendly empty states
  - Modal sheet navigation

- **Debugging & Problem Solving**
  - Resolved CloudKit configuration issues
  - Migrated logic to SwiftData for local testing
  - Fixed gesture conflicts and state bugs

---

## 🛠️ Tech Stack
- **Language:** Swift
- **UI:** SwiftUI
- **Persistence:** SwiftData
- **Maps:** MapKit
- **Architecture:** MVVM
- **Tools:** Xcode, iOS Simulator

  
## 🚀 Future Improvements
- User authentication (Sign In / Sign Up)
- CloudKit synchronization
- Reviews and ratings
- Favorites
- Map navigation routes
- Multi-language support

---

## 👩‍💻 Author
**Nadira Seitkazy**  
Junior iOS Developer  
Faculty: Information Technology  
Specialization: Mobile Development  

---

## 📌 Notes
This project was created as a **learning and portfolio project**, focusing on modern iOS technologies, real-world features, and clean architecture.
