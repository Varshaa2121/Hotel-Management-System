# 🏨 Hotel Management System

## 📌 About the Project
The **Hotel Management System** is a simple **web-based application** developed using **PHP and MySQL**.  
The frontend uses **HTML, CSS, JavaScript (jQuery & AJAX), and Bootstrap**, built using a free template from **StartBootstrap – Creative**.

This system helps hotels manage:
- Room categories  
- Room details  
- Bookings  
- Guest check-ins and check-outs  
- Overall room availability  

It contains two interfaces:  
- **Admin Side** – for staff to manage hotel operations  
- **Guest Side** – for visitors to browse rooms and make bookings  

---

## 🧩 Features

### 🔐 Admin Side
- **Category Page:** Manage room categories  
- **Rooms Page:** Add/manage hotel rooms  
- **Settings Page:** Update system title, images, and details  
- **Check-in Page:** Manage guest check-ins  
- **Checkout Page:** Update check-in data and process check-outs  
- **Booked Page:** View and confirm guest bookings  

### 👤 Guest Side
- **Home Page:** Landing page of the hotel  
- **Rooms Page:** Shows available rooms based on date selection  
- **About Page:** Hotel details and information  

---

## 🔑 Default Admin Access
- **Username:** admin  
- **Password:** admin123  

---

## 🚀 How to Run / Install

### **1. Download the Project**
- Click **Code → Download ZIP**, then extract it  
**OR**  
- Clone via Git:
```
git clone <repository-url>
```

### **2. Set Up Local Web Server**
Install **XAMPP / WAMP / Laragon** (supports PHP & MySQL).  
Start these from the control panel:
- Apache  
- MySQL  

### **3. Create a Database**
1. Open:  
   ```
   http://localhost/phpmyadmin
   ```  
2. Click **New**  
3. Create a database (example name):  
   ```
   hotel_db
   ```

### **4. Import SQL File**
1. Go to the `database/` folder in the project  
2. Find `hotel_db.sql`  
3. In phpMyAdmin:
   - Open the created database  
   - Click **Import**  
   - Select the SQL file  
   - Click **Go**  

### **5. Move Project to htdocs**
Copy the project folder to:
```
C:\xampp\htdocs\hotel-management-system
```

### **6. Run the Project**
#### Guest Side:
```
http://localhost/hotel-management-system/
```

#### Admin Panel:
```
http://localhost/hotel-management-system/admin/
```
