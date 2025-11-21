🎓 Student Attendance App

This is a simple and clean Android app I built to make attendance tracking easier for teachers.
Instead of writing everything on paper or juggling messy Excel sheets, this app lets you manage classes, add students, and mark attendance — all from your phone.

I built it using modern Android components and focused on keeping the UI smooth, fast, and easy to use.

📌 What this app can do

Create and manage multiple classes

Add students manually or import them using a CSV file

Mark attendance date-wise with a single tap

Store everything locally using SQLite

Download attendance reports in CSV format

Works completely offline

This is basically a small but fully functional attendance management system you can run on any Android device.

🧰 Tech Used

Java/Kotlin (depending on your project code)

SQLite + DBHelper for local storage

RecyclerView + Adapters for smooth lists

XML UI with Material components

Built on Android Studio

📁 Project Structure
Student-Attendance-App/
│── app/
│   ├── java/
│   │    ├── activities/
│   │    ├── adapters/
│   │    ├── database/
│   │    └── models/
│   ├── res/
│   │    ├── layout/
│   │    ├── drawable/
│   │    └── values/
│   └── AndroidManifest.xml
│
└── README.md

🚀 How to Run It
1️⃣ Clone the repo
git clone https://github.com/YOUR-USERNAME/Student-Attendance-App.git

2️⃣ Open it in Android Studio

Just open the folder → let Android Studio build it.

3️⃣ Run on an emulator or device

Hit the Run button and you're good to go.

📥 CSV Import Format

If you want to bulk add students, use a CSV like this:

roll_number,name
01,John Doe
02,Jane Smith
03,Riya Sharma


The app will read it automatically and add everyone.
