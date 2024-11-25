#                       🌾🚜 **Farmer_Management_System** 🚜🌾


Welcome to **Farmer_Management_System**, a comprehensive **Database Management System (DBMS)** designed to help farmers efficiently manage their farm operations. This web-based application, built using **Python** and **Flask**, allows farmers to manage resources, track activities, and interact with stakeholders—all through a robust and user-friendly interface. The system is powered by a relational database to store and organize farming data.

---

## 🌟 **Features** 🌟

- 🌱 **Database-Driven Management**: Organize and manage farm resources, activities, and stakeholder interactions in a relational database (MySQL).
- 🌍 **Web Interface**: Access the application through a modern and intuitive **Flask** web interface.
- 🔒 **User Authentication**: Secure login and account management using **Flask-Login** to protect user data and access.
- 📊 **Resource and Activity Tracking**: Efficiently track crops, equipment, and tasks through a well-structured database schema.
- 📂 **Database Integration**: Uses SQL queries and relationships to connect farm data, manage transactions, and generate reports.
- 🧑‍🤝‍🧑 **Stakeholder Interaction**: Record and manage communications and transactions with suppliers, buyers, and other stakeholders.

---

## 🛠️ **Installation** 🛠️

Follow these steps to set up **Farmer System** on your local machine:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Pseudo-Sid26/Farmer_Management_System.git
    cd farmer-system
    ```

2. **Set up XAMPP for Database**:
   - Install **XAMPP** (includes MySQL and Apache) from [XAMPP](https://www.apachefriends.org/index.html).
   - Start **Apache** and **MySQL** services in the **XAMPP Control Panel**.
   - Open **phpMyAdmin** at [http://localhost/phpmyadmin](http://localhost/phpmyadmin).
   - Create a new database, e.g., `farmer_system_db`.
   - Import the `farmers.sql` script (found in the repository) into the database to set up the schema and tables.

3. **Install dependencies**:
    ```bash
    Flask
    Flask-SQLAlchemy
    Flask-Login
    Werkzeug

    ```

4. **Set up environment variables** (optional):
   - Create a `.env` file in the root directory to configure database connections and other settings:
     ```dotenv
     DATABASE_URI=mysql://username:password@localhost/farmer_system_db
     ```

5. **Run the Flask application**:
    ```bash
    python main.py
    ```

---

## ⚙️ **Database Structure** ⚙️

The **Farmer System** is powered by a relational database schema. Here's a brief overview of the key entities and relationships:

- **Farmers**: Stores information about farmer users, including login credentials and personal details.
- **Resources**: Tracks farm resources such as crops, tools, equipment, and fertilizers.
- **Activities**: Records all farming activities (e.g., planting, harvesting) and links them to specific resources and dates.
- **Stakeholders**: Maintains details about suppliers, buyers, and other partners the farmer interacts with.
- **Transactions**: Logs transactions between the farmer and stakeholders (sales, purchases, etc.).

The relationships between tables ensure data consistency and enable efficient querying, reporting, and management of farm operations.

---

## 🚀 **Usage** 🚀

1. **Login/Register**: Start by creating a farmer account or logging in if you already have one.
2. **Add Resources**: Use the interface to add and manage resources like crops, equipment, and fertilizers.
3. **Track Activities**: Record farming activities such as planting, harvesting, and maintenance.
4. **Manage Stakeholders**: Keep track of suppliers, customers, and other important stakeholders you interact with.

---

## 🗂️ **Project Structure** 🗂️

farmer-system/│ 
├── farmers.sql # SQL script to set up the database schema and tables 
├── main.py # Main Flask application file 
├── static/ # Static files (CSS, JavaScript, images) 
│ └── styles.css # Styling for the web interface 
   ├── templates/ # HTML templates for frontend views │ 
   └── index.html # Main HTML interface  
├── README.md # Project README file 
└── .env # Environment variables for database and configuration(if required)



---

## 🧰 **Tech Stack** 🧰

- **Backend**: Python, Flask, Flask-SQLAlchemy
- **Database**: MySQL (used with XAMPP for local hosting)
- **Frontend**: HTML, CSS, JavaScript
- **User Authentication**: Flask-Login for secure login and session management
- **SQL Queries**: Used to interact with the database, handle CRUD operations, and generate reports.

---

## 🌍 **Future Enhancements** 🌍

- 🔄 **Advanced Reporting**: Implement more advanced reporting features, such as resource utilization analysis and crop yield forecasting.
- 🌐 **Multi-Farm Management**: Extend the system to allow management of multiple farms by the same user.
- 📱 **Mobile Integration**: Create a mobile app to access and manage farm operations on the go.
- 💬 **Stakeholder Communication**: Implement messaging features to communicate directly with stakeholders within the system.

---

## Contributors
- Siddhesh Chavan, siddhesh.22210162@viit.ac.in 
- Sujit Giri, sujit.22210293@viit.ac.in 
- Shreya Keripale, shreya.22211616@viit.ac.in 
- Vanshika Khiyani, vanshika.22211207@viit.ac.in


---

Thank you for checking out **Farmer Management System**! 🌾 Let's simplify farm management with technology! 🚜💡

