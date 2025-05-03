# 🌍 Travel Nexus

**Travel Nexus** (formerly *Venture Vista*) is a full-stack travel booking platform designed for seamless user experience in exploring, booking, and managing travel destinations. This project was built as a collaborative group effort, simulating real-world application development and deployment.

---

## 👥 Contributors

- **[Sachin Dumbre]** – Frontend development, database integration, UI/UX enhancement.
- **[Vedashree rajwade & Tanvi Joil]** – Backend logic, phpMyAdmin DB design, payment processing implementation.


---

## 🚀 Features

### 🧾 User Authentication
- Signup/Login system with session management.
- Validation and security checks.

🎥 **Login Demo**  
[📹 Watch Video](https://github.com/user-attachments/assets/ab0279fc-421b-4ed1-972a-2ce96cad7dfa)
) 

---

### 🗃️ Database Integration
- MySQL database managed via **phpMyAdmin**.
- Tables: `users`, `destinations`, `bookings`, `payments`.

🎥 **Database Storage Demo**  
[📹 Watch Video]((https://github.com/user-attachments/assets/d7a3844d-0caf-470d-97ec-122686452346))

---

### 🧭 Tour Discovery & Booking
- Filterable list of travel destinations.
- View destination info, prices, and images.
- Book Now → saves to `bookings` table.

---

### 💳 Payment Simulation
- Simulated checkout process.
- Records stored in `payments` table with status “Paid”.

🎥 **Payment Process Demo**  
[📹 Watch Video]((https://github.com/user-attachments/assets/cf70afda-a0f2-42aa-8590-c4cfd44ff87f)
)

---

**Payment Details Saved in Database**
[Screenshot-((https://github.com/user-attachments/assets/e4efee54-f839-4802-9f7a-c08b662734a4))

---

### 📄 Booking Summary & Receipt
- View past bookings.
- Option to generate/download receipt.

---

## 🛠️ Tech Stack

| Area       | Tech Used                           |
|------------|-------------------------------------|
| Frontend   | HTML, CSS, JavaScript, Tailwind CSS |
| Backend    | PHP                                 |
| Database   | MySQL via phpMyAdmin                |
| Tools      | XAMPP / LAMP Stack                  |

---

## 🧱 Database Tables

- **`users`**: Stores login credentials.
- **`destinations`**: Info on travel packages.
- **`bookings`**: Tracks bookings made by users.
- **`payments`**: Records payment status and details.

---

## 🔄 Flow of Operation

1. User logs in or signs up.
2. Browses and selects a destination.
3. Booking is saved in DB.
4. Payment is made (simulated) and marked as “Paid”.
5. Booking confirmation and receipt are displayed.

---

## 🔧 Setup Instructions

1. Clone the repository  
   ```bash
   git clone https://github.com/Veda25-03/Travel-Nexus.git
