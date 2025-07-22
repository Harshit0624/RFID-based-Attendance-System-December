# RFID Attendance System

An RFID-based attendance system that automates the process of recording and managing attendance using RFID tags and a microcontroller. Ideal for schools, colleges, or workplaces where a streamlined, contactless method of tracking attendance is needed.

---

## 📌 Features

- ✅ Contactless RFID card-based authentication
- 📅 Automatic timestamp logging
- 💾 Attendance data saved to local storage / cloud / database (customizable)
- 🔒 Secure and unique tag identification
- 📊 Export attendance reports (CSV/Excel support optional)

---

## 🛠️ Tech Stack

| Component        | Description                                     |
|------------------|-------------------------------------------------|
| **Microcontroller** | Arduino Uno / NodeMCU / Raspberry Pi         |
| **RFID Module**     | RC522 or similar                              |
| **RFID Tags**       | 13.56 MHz passive RFID cards                  |
| **Database**        | MySQL / Firebase / Google Sheets (optional)  |
| **Interface**       | LCD display / Serial Monitor / Web Dashboard |
| **Language**        | C++ / Python / HTML (for UI dashboard)       |

---

## ⚙️ How It Works

1. Each student/employee is issued a unique RFID tag.
2. When scanned, the RFID module sends the tag’s UID to the microcontroller.
3. The UID is matched against the stored records.
4. If valid, attendance is logged with a timestamp.
5. Data is stored locally or pushed to a cloud/database service.

---

## 🚀 Getting Started

### Hardware Requirements

- Arduino Uno or compatible board
- RFID Reader (RC522)
- RFID Cards/Tags
- Jumper wires
- Breadboard
- LCD Display (optional)

### Software Requirements

- Arduino IDE / PlatformIO
- USB Drivers for microcontroller
- MySQL / Firebase setup (if using database)
- Python (if using Raspberry Pi)

### Wiring Diagram

> 📷 *(Insert image or diagram here)*

---

## 🙋‍♂️ Author

**Harshit Gupta**  
📧 [harshitgupta0624@gmail.com]  
🔗 [LinkedIn](https://www.linkedin.com/in/harshit-gupta-687558263/)  

---

