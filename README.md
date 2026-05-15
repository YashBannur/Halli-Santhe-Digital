# README.md

````md
# Halli-Santhe Digital 🌾

## A Hyper-Local Marketplace for Rural Artisans

Halli-Santhe Digital is a modern Android application developed using Jetpack Compose and Firebase that helps rural artisans showcase and sell handmade products digitally.

The application acts as a hyper-local marketplace where artisans can upload products and buyers can browse, search, and connect with sellers easily.

---

# 📱 Features

## User Authentication
- User Signup
- User Login
- Firebase Authentication integration

## Product Management
- Upload product details
- Upload product images
- Store product information in Firestore
- Firebase Storage integration

## Marketplace Features
- Product grid display using LazyVerticalGrid
- Product detail screen
- Product search functionality
- Seller contact option
- Empty state UI

## AI Feature
- AI-based product description generator (mock/simulated)

## UI/UX
- Modern Jetpack Compose UI
- Vibrant and colorful design
- Responsive layouts
- Material 3 components

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Kotlin | Programming Language |
| Jetpack Compose | UI Development |
| Firebase Authentication | Login & Signup |
| Firestore Database | Product Data Storage |
| Firebase Storage | Image Storage |
| MVVM Architecture | App Architecture |
| Navigation Compose | Navigation |
| Coil | Image Loading |
| Coroutines | Async Operations |

---

# 🧱 Project Architecture

The application follows MVVM (Model-View-ViewModel) Architecture.

```text
com.hallisanthe

│
├── data
│   ├── model
│   ├── repository
│
├── ui
│   ├── screens
│   ├── components
│   ├── navigation
│   ├── theme
│
├── viewmodel
│
├── utils
│
└── MainActivity.kt
````

---

# 🔥 Firebase Services Used

* Firebase Authentication
* Cloud Firestore
* Firebase Storage

---

# 📂 Firestore Structure

## Collection: products

```json
{
  "id": "101",
  "name": "Clay Pot",
  "price": "250",
  "description": "Handmade traditional clay pot",
  "category": "Home Decor",
  "imageUrl": "firebase-image-url",
  "sellerPhone": "9876543210"
}
```

---

# 🚀 Installation Steps

## 1. Clone the Repository

```bash
git clone <your-repository-link>
```

---

## 2. Open Project

Open the project using:

* Android Studio Hedgehog or later

---

## 3. Connect Firebase

### Steps:

1. Create Firebase Project
2. Enable Authentication
3. Enable Firestore Database
4. Enable Firebase Storage
5. Download `google-services.json`
6. Place it inside:

```text
app/google-services.json
```

---

## 4. Sync Gradle

Click:

```text
Sync Project with Gradle Files
```

---

## 5. Run the App

Connect:

* Android device
  OR
* Emulator

Then click:

```text
Run ▶
```

---

# 📸 Screenshots

Add screenshots here:

* Splash Screen
* Login Screen
* Signup Screen
* Home Screen
* Product Grid
* Add Product Screen
* Product Details Screen
* Search Functionality
* Empty State Screen

---

# 🎯 Future Enhancements

* Online payment integration
* Real-time chat system
* Voice search
* Product reviews and ratings
* Admin dashboard
* Multi-language support
* AI recommendations

---

# 📌 Conclusion

Halli-Santhe Digital successfully demonstrates the implementation of a modern Android marketplace application using Jetpack Compose and Firebase.

The application helps bridge the gap between rural artisans and digital consumers through a simple and accessible marketplace platform.

---

# 👩‍💻 Developed By

Yashavant N B 
Computer Science & Engineering
City Engineering College

---

# 📚 References

* [https://developer.android.com](https://developer.android.com)
* [https://firebase.google.com](https://firebase.google.com)
* [https://kotlinlang.org](https://kotlinlang.org)
* [https://developer.android.com/jetpack/compose](https://developer.android.com/jetpack/compose)

```
```