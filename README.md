# 🚌 Bus Schedule Management System (C# WinForms)

A desktop-based **Bus Schedule Management System** built using **C# WinForms** and **Guna.UI2** for modern and visually appealing UI components. The system allows admins or staff to manage buses, routes, timings, and passenger bookings through an intuitive interface.

---

## ✨ Features

- **Add/Edit/Delete Buses**
- **Manage Bus Routes and Timings**
- **Passenger Booking System**
- **Search Bus by Route or Time**
- **View Daily Schedules**
- **Modern UI with Guna2 Components**
- **Data Persistence** using local files or database (as per your setup)

---

## 🛠️ Technologies Used

- **C#**
- **.NET Framework**
- **WinForms (Windows Forms)**
- **Guna.UI2.WinForms** (for enhanced UI controls)
- **Microsoft SQL Server / Local File Storage**
- **Visual Studio**

---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/aabr2612/mini-bus-system
## ⚙️ Setup Instructions

2. **Open in Visual Studio**
   - Launch Visual Studio.
   - Open the `.sln` file located in the root directory of the project.

3. **Restore NuGet Packages**
   - Ensure all required NuGet packages are installed.
   - The project uses the **Guna.UI2.WinForms** package for enhanced UI controls.
   - To install manually, open the **Package Manager Console** and run:
     ```bash
     Install-Package Guna.UI2.WinForms
     ```

4. **Configure Database**
   - If you're using SQL Server:
     - Update your connection string in `App.config` or `Settings.settings` file.
     - Ensure your database is created and accessible.

5. **Build and Run**
   - Press `F5` or click on the **Start** button in Visual Studio to build and run the application.

---

## 🧭 How to Use

1. Launch the application.
2. Use the navigation menu to manage:
   - **Buses**: Add/edit bus names and IDs.
   - **Routes**: Add routes, stops, and distances.
   - **Schedule**: Add departure/arrival times.
   - **Bookings**: Register passenger information and assign buses.
3. View reports, search buses, or edit schedules easily.

---

## 📌 Conclusion

This project helped me learn and apply concepts like **event-driven programming**, **Windows Forms**, and **UI design using Guna2 components** in **C#**.  
It’s a useful application for managing bus operations in a small to mid-scale transport system.
