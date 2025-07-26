# 🇮🇳 Bharath Darshika - Explore Incredible India

**Bharath Darshika** is a modern tourism web application designed to guide users through India's most beautiful destinations. From spiritual temples to adventurous treks and beaches, this platform provides detailed information, smart recommendations, and booking options — all in one place.

---

## 🌟 Key Features

- 🌐 Tourism categorized by Zones: South, North, East, West
- 📍 State-wise tourist attractions: Temples, Beaches, Forests, Hills, etc.
- 💼 Skilled Worker Profiles based on location & need (guides, drivers, etc.)
- 🧳 Travel Packages: High-end, Medium, and Budget-friendly
- 🔍 Image Recognition: Upload an image to identify a place (AI-powered)
- 💬 Smart Chatbot Assistant for user help
- 🎨 Beautiful, responsive UI with dark mode toggle
- 🗺️ Google Maps integration for place directions
- 👤 Admin Dashboard to manage states, places, packages, images
- 🔐 Login & Session-based secured access

---

## 💻 Technologies Used

- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Extras:** Google Maps API, Dark Mode, AI (optional Python Flask), JS chatbot

---

## 🛠️ How to Run

1. ✅ Install XAMPP / MAMP and start Apache & MySQL
2. ✅ Place project folder in `htdocs`
3. ✅ Import `bharathdarshika.sql` into phpMyAdmin
4. ✅ Update DB credentials in your PHP config file:
   ```php
   $conn = mysqli_connect("localhost", "root", "", "bharathdarshika");
