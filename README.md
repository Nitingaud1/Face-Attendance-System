# Face Recognition Attendance System

This project implements a face recognition-based attendance system using OpenCV, Streamlit, and K-Nearest Neighbors (KNN) for classification. The system captures facial data, trains a model, and recognizes faces in real time to mark attendance.

---

## Features
- **Face Data Collection:** Collect and store facial data using the `add_face.py` script.
- **Real-Time Face Recognition:** Recognize faces and mark attendance with `test.py`.
- **Streamlit Dashboard:** View and analyze attendance records in a user-friendly interface using `app.py`.
- **CSV Attendance Logs:** Attendance data is saved in CSV format for easy access.

---

## Project Structure
- **`add_face.py`**: Script to collect and save facial data.
- **`app.py`**: Streamlit-based application for monitoring attendance.
- **`test.py`**: Script for real-time face recognition and attendance marking.
- **`data/`**: Directory to store facial data (`faces_data.pkl`) and names (`names.pkl`).
- **`Attendance/`**: Directory to store attendance records in CSV format.
- **`background.png`**: Background image for the real-time face recognition UI.

---

## Prerequisites
- Python 3.8 or higher
- Libraries:
  - OpenCV
  - Streamlit
  - NumPy
  - Pandas
  - Scikit-learn
  - pywin32 (Windows only)

---

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/face-recognition-attendance.git
   cd face-recognition-attendance
