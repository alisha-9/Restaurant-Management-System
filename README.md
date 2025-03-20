# 🍔 Restaurant Order Management System

A Java-based application that manages restaurant orders, allows users to add items to an order, generates a receipt, and saves order details to a MySQL database. This system uses **AWT (Abstract Window Toolkit)** for the user interface and **JDBC** for database connectivity.

---

## 📚 **Features**

✅ **Menu Management**
- Predefined menu items (e.g., Burger, Pizza).
- Option to fetch menu items dynamically from the database (optional improvement).

✅ **Order Management**
- Add items to the current order.
- View order details with real-time updates.
- Clear order functionality (optional enhancement).

✅ **Database Integration**
- Saves order data (item name, quantity, and total price) to a MySQL database.

✅ **Receipt Generation**
- Generates a receipt with a summary of the order.
- Displays the receipt in a dialog box and prints it to the console.

✅ **Error Handling**
- Error messages are displayed in a dialog box if any issues occur.

---

## 🛠️ **Technologies Used**

- **Java** (Core Java, AWT)
- **JDBC** (Java Database Connectivity)
- **MySQL** (Database to store orders and menu items)

---

## 🗂️ **Project Structure**


---

## ⚙️ **Setup and Installation**

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/RestaurantOrderManagement.git
cd RestaurantOrderManagement

private static final String DB_URL = "jdbc:mysql://localhost:3306/restaurant_order";
private static final String USER = "root";  // Your MySQL username
private static final String PASSWORD = "";  // Your MySQL password


javac RestaurantOrderFrame.java
java RestaurantOrderFrame



