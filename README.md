# SnapClass
### AI-Powered Smart Attendance Management System

SnapClass is an AI-based classroom attendance system that automates attendance using **Face Recognition** and **Voice Recognition**. It provides separate dashboards for teachers and students, making attendance management fast, accurate, and paperless.

## Live Demo

**Application:**- https://snapclass-main21.streamlit.app/

##  Features

### Teacher Portal

- Secure teacher registration and login
- Create and manage multiple subjects
- Take attendance using classroom photos
- Take attendance using students' voices
- Review attendance before saving
- View attendance history and reports
- Monitor total classes and enrolled students for every subject

<br>

### 📷 Teacher Dashboard

<img width="782" height="655" alt="image" src="https://github.com/user-attachments/assets/b6ce481b-9936-4da4-b91b-42bf3f269f01" />

---

### 👩‍🎓 Student Portal

- Face Recognition based login
- Automatic student registration for new users
- Optional voice enrollment during registration
- Enroll in subjects using subject code
- View enrolled subjects
- Track attendance statistics
- Unenroll from subjects anytime

<br>

### 📷 Student Dashboard

<!-- INSERT IMAGE HERE -->
<img width="1001" height="840" alt="image" src="https://github.com/user-attachments/assets/c4603c97-284a-4c1d-92d3-859592b14296" />

---

## 🤖 AI Features

### 🧑 Face Recognition Attendance

- Detects multiple faces from classroom images
- Generates facial embeddings using **dlib**
- Recognizes registered students using an **SVM classifier**
- Marks attendance automatically
- Supports multiple classroom images for higher accuracy

<br>

### 📷 Face Attendance

<img width="770" height="779" alt="image" src="https://github.com/user-attachments/assets/bda41489-4589-4e29-9e76-a53d8961874b" />


---

### 🎤 Voice Recognition Attendance

- Students can register their voice profile
- Teacher records classroom audio
- AI identifies speakers using voice embeddings
- Automatically marks present students

<br>

### 📷 Voice Attendance

<img width="539" height="345" alt="image" src="https://github.com/user-attachments/assets/005514c7-9757-45e6-81a6-3850cf8ee284" />


---

### ✅ Attendance Review

Before saving attendance, teachers can review the generated attendance sheet and either confirm or discard the results.

<br>

### 📷 Attendance Preview

<img width="1129" height="695" alt="image" src="https://github.com/user-attachments/assets/d259769d-58ab-4ee8-8597-9c6bc446249c" />


---

### 📊 Attendance Records

Teachers can view attendance history for every class session, including:

- Date & Time
- Subject
- Attendance Summary

<br>

### 📷 Attendance Records

<img width="1600" height="1361" alt="image" src="https://github.com/user-attachments/assets/9310e86f-71d0-47a8-81b9-ef0733e73632" />


---

## 🏗️ Tech Stack

### Frontend

- Streamlit

### Backend

- Python

### Database

- Supabase

### AI & Machine Learning

- dlib
- face_recognition_models
- scikit-learn (SVM)
- Resemblyzer
- Librosa
- NumPy

---

## 📂 Project Structure

```text
SnapClass/
│── src/
│   ├── components/
│   ├── database/
│   ├── pipelines/
│   ├── screens/
│   └── ui/
│
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/SnapClass.git
cd SnapClass
```

### Create a virtual environment

```bash
python -m venv venv
```

### Activate it

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Configure Supabase

Create a `.streamlit/secrets.toml` file:

```toml
SUPABASE_URL="YOUR_SUPABASE_URL"
SUPABASE_KEY="YOUR_SUPABASE_KEY"
```

### Run the application

```bash
streamlit run app.py
```

---

## 🚀 Future Improvements

- Attendance analytics dashboard
- Email notifications
- Attendance export (CSV/PDF)

---

## 👩‍💻 Author

**Anjali Gupta**

Built with ❤️ using AI, Machine Learning, and Streamlit.
