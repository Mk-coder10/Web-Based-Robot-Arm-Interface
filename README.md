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
| `screenshots/`     | Optional UI image previews         |

---

## 🛠 Setup Instructions

[robot_arm.zip](https://github.com/user-attachments/files/21556542/robot_arm.zip)
