#  Technical Event Management System

A console-based **Event Equipment Management System** developed using **Python 3**.
This application simulates an event equipment booking workflow where users can browse items, place orders, and track order status, while admins manage vendors and update orders.

---

##  Features

###  User Module
- User Registration  
- User Login  
- Browse available event equipment  
- Add items to cart  
- Checkout (**Cash / UPI**)  
- View order status  
- Session-based cart handling  

### Admin Module
- Secure Admin Login  
- Add new vendors  
- Remove vendors (with validation check)  
- Update order status:
  - Approved  
  - Shipped  
  - Delivered  
  - Cancelled  

---

##  Technologies Used

- **Python 3**
- **JSON** (for persistent user storage)
- File Handling
- Datetime Module
- Lists & Dictionaries (Data simulation)

---
## Default Admin Credentials

Username: admin
Password: admin123

## System Workflow

1. User registers and logs in  
2. User browses available equipment  
3. Items are added to cart  
4. Checkout is completed  
5. Admin updates order status  
6. User checks updated order status  

## Data Storage

- User credentials are stored in `users.json`  
- Orders, vendors, and items are stored in memory (runtime only)  



