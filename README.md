# 📱 CFH Furnitualizer – AR Furniture Placement App

Flutter + Unity + ARCore | Final Year Project (2022–2023)
An augmented-reality–based furniture shopping application that allows users to visualize 3D furniture in their actual room using ARCore. Built with Flutter, Unity 3D, and Firebase, the app provides an immersive shopping experience combining e-commerce and mobile AR.

🚀 Overview

Traditional online furniture shopping lacks visualization — customers often buy items that do not fit their space. CFH Furnitualizer solves this by enabling users to:

Browse furniture products

View detailed specifications

Preview furniture in 3D

Place furniture directly in their room using Augmented Reality

Manage cart, orders, and profile

Use a clean, user-friendly app interface

The admin panel (Firebase) allows the business owner to manage products, users, and orders.

This project was built as a final year BSCS project at International Islamic University Islamabad.

🎯 Key Features
🌟 For Customers

🔐 User registration & login

🪑 Product browsing (categories + search)

📄 View detailed product specs

🛒 Add to cart, edit cart, checkout

🧾 Place orders & view order status

👤 Manage profile

🎥 View furniture in 3D (Unity)

📍 Place furniture in AR using ARCore

Plane detection

Real-world surface tracking

Rotation & scale gestures

Real-time lighting adoption

🛠️ For Admins

(Admin panel in Firebase)

Add/delete/edit products

Manage users

Manage orders

Update order status

🧰 Tech Stack
Frontend (User App)

Flutter (Dart)

Unity 3D

ARCore XR Plugin (Unity)

Backend

Firebase Authentication

Firebase Firestore (Database)

Firebase Storage

AR & 3D

Unity 3D for rendering

ARCore for:

Motion tracking

Plane detection

Environment understanding

Light estimation

🏗️ System Architecture

Below is the simplified architecture

Flutter App (User Interface)
     |
     | invokes AR mode
     |
Unity Module (3D + ARCore)
     | 
     | communicates with device sensors
     |
ARCore (Plane detection, motion tracking)

Firebase Backend
 ├── Authentication
 ├── Firestore (Products, Users, Orders)
 └── Storage


🧩 System Modules
Client App

Registration/Login

Product Management (view/search/filter)

AR Viewer

Cart & Orders

User Profile

Admin Panel

Product CRUD

User Management

Order Management

3D & AR Module (Unity)

Model rendering

Plane detection

3D product placement

Gesture controls

Real-world light matching

🔍 Functional Flow Summary
✔ 1. User opens the app → Login/Register
✔ 2. Browse categories → Select product
✔ 3. View product details → “View in 3D”
✔ 4. Unity loads product → ARCore scans room
✔ 5. Detects plane → User places 3D furniture
✔ 6. Scale/rotate → Confirm placement
✔ 7. Add to cart → Place order → Checkout
✔ 8. Order stored in Firebase → Admin processes

🧪 Testing Summary

Comprehensive testing was performed:

Unit Testing: Individual modules like login, cart, product view

Integration Testing: Flutter ↔ Unity ↔ Firebase

System Testing: End-to-end user scenarios

AR Testing:

Plane detection

Lighting estimation

Model scaling & movement

Multiple room environments

All test cases are documented in the FYP report.

📸 Screenshots
![On Board](screenshots
/onboard.jpg)



Authors

Sofia Shafique
Laiba Pervaiz

Supervised by:
Ms. Anum Yasmin
International Islamic University Islamabad

🏁 Conclusion

CFH Furnitualizer delivers a fully functional AR-enabled furniture shopping experience. By integrating Unity and ARCore with Flutter, users can realistically preview products before purchasing, reducing uncertainty and increasing confidence in online shopping.

The project successfully demonstrates the real-world application of Augmented Reality in e-commerce and sets a foundation for future enhancements.

🔮 Future Enhancements

Multi-product AR placement

Real-time occlusion

Measurement tools inside AR mode

Improved 3D asset optimization

Recommendation engine

Payment gateway integration
