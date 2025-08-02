# Robot Arm Control Panel using PHP and MySQL

A simple web-based robot arm control interface that allows users to control six servo motors using sliders. Users can save, load, and delete motor positions ("poses") stored in a MySQL database.

---

## 🚀 Features

- Control 6 motors using interactive sliders (range: 0–180°)
- Save current motor positions to the database
- View all saved poses in a dynamic table
- Load or delete specific poses
- Reset sliders to default (90°)

---

## 🧰 Technologies Used

- PHP (backend logic)
- MySQL (database)
- HTML / CSS (user interface)
- JavaScript (fetch API for AJAX)
- XAMPP (Apache & MySQL)

---

## 📂 Folder Structure

| File               | Purpose                            |
|--------------------|------------------------------------|
| `index.php`        | Main UI with sliders and controls  |
| `api.php`          | Handles all save/load/delete APIs  |
| `arm_positions.sql`| MySQL export of the table structure |

---

## 🛠 Setup Instructions

[robot_arm.zip](https://github.com/user-attachments/files/21556542/robot_arm.zip)


2. **Start Apache and MySQL** using the XAMPP control panel.

3. **Set up the database:**
- Visit: `http://localhost/phpmyadmin`
- Create a database named `robot_arm`
- Go to the **Import** tab and select `arm_positions.sql`

4. **Launch the web interface:**
http://localhost/robot-arm-control-panel/index.php


---

## 🗃 Database Table Structure

Table name: `arm_positions`

| Column  | Type     | Description                   |
|---------|----------|-------------------------------|
| id      | INT      | Primary Key, Auto Increment   |
| motor1  | INT      | Position of motor 1           |
| motor2  | INT      | Position of motor 2           |
| motor3  | INT      | Position of motor 3           |
| motor4  | INT      | Position of motor 4           |
| motor5  | INT      | Position of motor 5           |
| motor6  | INT      | Position of motor 6           |
| status  | TINYINT  | Reserved for execution state  |

---

## 🖼 Screenshot

<img width="704" height="463" alt="image" src="https://github.com/user-attachments/assets/ae39c3c1-15ef-4cfe-905c-f37150fbf577" />

---

## 📌 Notes

- Tested on modern browsers (Chrome)
- Requires XAMPP or equivalent server stack
- Designed for local environment, not hosted deployment

---

## 📁 License

This project is open-source and free to use for educational or development purposes.

