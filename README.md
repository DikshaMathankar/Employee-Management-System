# Employee Management System

A Java Swing desktop application for managing employee records with MySQL database.

## 🚀 Quick Start

### 1. Setup Database
Open **MySQL Workbench** and run:
```bash
File → Open SQL Script → setup_database.sql → Execute
```

### 2. Run Application
Double-click **`run.bat`**

### 3. Login
- Username: `admin`
- Password: `admin123`

---

## 📋 Features

✅ Add new employees  
✅ View all employees  
✅ Update employee details  
✅ Delete employees  
✅ Search by Employee ID  
✅ Print employee table  

---

## ⚙️ Configuration

**Database:** MySQL  
**Host:** localhost:3306  
**Username:** root  
**Password:** root  
**Database Name:** employeemanagementsystem  

---

## 📁 Project Structure

```
├── src/                    # Java source files
├── build/classes/          # Compiled files
├── lib/                    # Dependencies (2 JARs)
├── run.bat                 # Run application
├── setup_database.sql      # Database setup
└── USER_GUIDE.md          # Detailed guide
```

---

## 📖 Documentation

- **USER_GUIDE.md** - Complete usage instructions
- **setup_database.sql** - Database setup script

---

## 🛠️ Requirements

- Java 17 or higher
- MySQL 5.7 or higher
- Windows OS

---

## 🎯 Usage

1. **Add Employee** - Enter details, auto-generates Employee ID
2. **View Employees** - See all records, search, print
3. **Update Employee** - Select ID, modify fields
4. **Remove Employee** - Select ID, delete record

---

## ⚡ Troubleshooting

**Can't connect to database?**
- Ensure MySQL is running
- Run setup_database.sql

**Can't login?**
- Default: admin/admin123
- Check database has login table

---

## 📞 Support

For issues, check **USER_GUIDE.md** troubleshooting section.

---

**Built with:** Java Swing + MySQL + JDBC
