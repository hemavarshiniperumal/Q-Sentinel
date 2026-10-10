🍽️ SpiceKart — Online Food Ordering System

«[ A Modern & Interactive Food Ordering Website ]»

SpiceKart is a responsive online food ordering web application built using HTML, CSS, and JavaScript. It provides users with an attractive food menu, category filtering, search functionality, favorites, shopping cart, checkout, login, order tracking, and customer reviews.

---

✨ Features

🍴 Food Menu

- [x] 15+ food items
- [x] South Indian dishes
- [x] North Indian dishes
- [x] Non-Vegetarian dishes
- [x] Desserts
- [x] Italian desserts
- [x] Food-specific images
- [x] Ratings and customer reviews

🔍 Search & Filtering

- [x] Search food by name
- [x] Search by cuisine
- [x] Search by description
- [x] Filter food by category
- [x] "No food found" message

❤️ Favorites

- [x] Add food to favorites
- [x] Remove food from favorites
- [x] Favorite item counter
- [x] Favorite status displayed on food cards

🛒 Shopping Cart

- [x] Add items to cart
- [x] Increase quantity
- [x] Decrease quantity
- [x] Remove items
- [x] Automatic price calculation
- [x] Cart item counter
- [x] Empty cart message

📦 Checkout

- [x] Customer name validation
- [x] Indian mobile number validation
- [x] Delivery address
- [x] Payment method selection
- [x] Automatic order ID generation
- [x] Order confirmation

🚚 Order Tracking

- [x] Order confirmation
- [x] Preparing status
- [x] Picked-up status
- [x] Delivered status
- [x] Generated order number

👤 Login

- [x] Email input
- [x] Password input
- [x] Basic login validation
- [x] Login success notification

⭐ Customer Reviews

- [x] Overall customer reviews
- [x] Food-specific reviews
- [x] Star ratings
- [x] Review section

---

🖥️ Technologies Used

Technology| Purpose
🟧 HTML5| Website structure
🎨 CSS3| Styling and responsive design
🟨 JavaScript| Functionality and interaction
🖼️ Unsplash / Wikimedia Commons| Food images

---

📁 Project Structure

SpiceKart/
│
├── 📄 index.html
│
└── 📄 README.md

«Note: The complete project is currently contained in a single "index.html" file with HTML, CSS, and JavaScript included internally.»

---

🎨 Website Sections

┌─────────────────────────────────────────┐
│              🍽️ SpiceKart              │
├─────────────────────────────────────────┤
│ 🔍 Search     ❤️ Favorites   🛒 Cart   │
├─────────────────────────────────────────┤
│                                         │
│        Delicious Food                   │
│        Delivered To You                 │
│                                         │
│             [ Order Now ]               │
│                                         │
├─────────────────────────────────────────┤
│              🍴 Food Menu               │
├─────────────────────────────────────────┤
│ All | South Indian | North Indian       │
│ Non-Veg | Desserts | Italian            │
├─────────────────────────────────────────┤
│                                         │
│   🍛 Food Card   🍕 Food Card           │
│   🍰 Food Card   🥘 Food Card           │
│                                         │
├─────────────────────────────────────────┤
│          ⭐ Customer Reviews            │
├─────────────────────────────────────────┤
│             📞 Contact                  │
└─────────────────────────────────────────┘

---

🍛 Available Food Categories

🇮🇳 South Indian

- Idli Sambar
- Medu Vada
- Masala Dosa

🥘 North Indian

- Samosa
- Paneer Tikka
- Biryani
- Dal Makhani
- Chole Bhature
- Garlic Naan & Curry

🍗 Non-Veg

- Butter Chicken

🍰 Desserts

- Gajar Halwa
- Gulab Jamun
- Rasmalai
- Chocolate Brownie

🇮🇹 Italian

- Italian Tiramisu

---

⚙️ Main JavaScript Functions

The application uses JavaScript functions to provide interactive features.

┌──────────────────────────┐
│     JavaScript Logic     │
├──────────────────────────┤
│ renderFoods()            │
│ filterCategory()         │
│ searchFood()             │
│ toggleFavorite()         │
│ addToCart()              │
│ changeQuantity()         │
│ removeFromCart()         │
│ openCart()               │
│ renderCart()             │
│ openCheckout()           │
│ placeOrder()             │
│ showDetails()            │
│ openLogin()              │
│ login()                  │
│ showToast()              │
└──────────────────────────┘

---

📱 Responsive Design

SpiceKart is designed to work across different screen sizes.

💻 Desktop
   ↓
📱 Tablet
   ↓
📲 Mobile

The website uses CSS media queries to automatically adjust:

- Navigation
- Food card layout
- Hero section
- Review section
- Footer
- Search bar
- Images
- Modal windows

---

🖼️ Image Handling

Each food item has its own image URL.

The project also includes an image fallback system.

If an external food image fails to load:

Image unavailable
        ↓
     🍽️
        ↓
Food Name
        ↓
"Food image unavailable"

This prevents the website from incorrectly displaying another food's image.

---

🛒 Order Flow

The basic ordering process is:

[ Browse Menu ]
       ↓
[ Search / Filter ]
       ↓
[ Select Food ]
       ↓
[ Add to Cart ]
       ↓
[ View Cart ]
       ↓
[ Checkout ]
       ↓
[ Enter Details ]
       ↓
[ Select Payment ]
       ↓
[ Place Order ]
       ↓
[ Order Confirmed ]
       ↓
[ Track Order ]

---

🔐 Form Validation

The checkout form validates:

✓ Customer Name
✓ 10-Digit Mobile Number
✓ Delivery Address
✓ Payment Method

The mobile number follows the Indian format:

[ 6-9XXXXXXXX ]

Example:

9876543210

---

🚀 How to Run the Project

Step 1 — Download the Project

Download or clone the SpiceKart project.

Step 2 — Open the Project

Open the project folder in:

- VS Code
- Sublime Text
- Notepad++
- Any HTML-supported IDE

Step 3 — Open "index.html"

Simply open:

index.html

in your web browser.

Step 4 — Start Ordering 🍽️

Open Website
     ↓
Browse Food
     ↓
Add to Cart
     ↓
Checkout
     ↓
Place Order

---

🌐 Browser Compatibility

SpiceKart works with modern browsers such as:

Browser| Support
🌐 Google Chrome| ✅
🦊 Firefox| ✅
🧭 Microsoft Edge| ✅
🍎 Safari| ✅
📱 Mobile Browsers| ✅

---

📌 Important Note

This project is a frontend demonstration project.

The following features are simulated using JavaScript:

- Login
- Payment
- Order placement
- Order tracking
- Favorites
- Cart management

There is currently no backend database or real payment gateway connected.

---

🔮 Future Improvements

Possible future upgrades include:

┌──────────────────────────────────────┐
│          Future Enhancements         │
├──────────────────────────────────────┤
│ 🔐 Real User Authentication          │
│ 🗄️ Database Integration              │
│ 💳 Online Payment Gateway            │
│ 📍 Live Delivery Tracking            │
│ 👨‍🍳 Restaurant/Admin Dashboard       │
│ 📦 Order History                     │
│ 🔔 Order Notifications               │
│ 🧾 Digital Invoice                  │
│ ⭐ User Review Submission             │
│ 🌙 Dark Mode                         │
│ 📱 Progressive Web App               │
└──────────────────────────────────────┘

---

👩‍💻 Project Information

┌─────────────────────────────────────┐
│          🍽️ SPICEKART               │
├─────────────────────────────────────┤
│ Project Type : Food Ordering System │
│ Frontend     : HTML + CSS + JS      │
│ Design       : Responsive           │
│ Status       : Completed            │
└─────────────────────────────────────┘

---

❤️ Why SpiceKart?

SpiceKart is designed to provide a simple and attractive food-ordering experience.

«"Good food. Simple ordering. Happy customers." 🍽️»

---

📜 License

This project is created for educational and project demonstration purposes.

You are free to modify and improve the project for learning purposes.

---

⭐ Show Your Support

If you like this project:

⭐ Star the repository
🍴 Fork the project
💻 Improve the code
📢 Share it with others

---

<div align="center">🍽️ SpiceKart

[ Delicious Food • Easy Ordering • Happy Customers ]

Made with ❤️ using HTML • CSS • JavaScript

</div>