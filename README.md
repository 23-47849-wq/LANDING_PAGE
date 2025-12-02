This is a fully functional educational platform demo that mimics core Google Classroom features:

Teacher & student role authentication

Create and manage assignments, modules, and quizzes

File upload and submission system

Grading and late submission tracking

Quiz system (multiple-choice)

People management (add/remove students)

Responsive UI with modals and sidebar navigation

All data is persisted in the browser's localStorage, so no backend is required.

🧑‍🏫 Roles & Login Credentials
Role	Username	Password	Notes
Teacher	teacher	12345	Full access to create content and grade submissions
Student	louisana	pass123	Preloaded sample student
📂 Pages & Features
🏠 Stream
Recent activity feed (assignments, modules, submissions)

Shows latest submissions from students

📚 Classwork
List of assignments with due dates

Open/View submissions (teacher)

Submit assignments (student)

📦 Modules
Learning modules with attached files

Upload modules as a teacher

Submit module work as a student

📝 Quizzes
Multiple-choice quiz system

Take quizzes (students)

View results and scores (teacher)

📊 Grades
Student view: personal grades for assignments, modules, quizzes

Teacher view: all students' grades in one place

👥 People
Manage student accounts

Add/remove students

Show credentials and login as any student

🧑‍🏫 Teacher (sidebar link appears when logged in as teacher)
Quick overview of assignments

Direct links to submissions

🛠️ How to Use
Open index.html in any modern browser.

Log in as teacher / 12345 to:

Create assignments, modules, quizzes

Add students

Grade submissions

Log in as a student (or create one in People page) to:

Submit assignments and modules

Take quizzes

View personal grades

Switch between pages using the sidebar navigation.

📦 Local Storage Keys
The app uses the following localStorage keys to persist data:

Key	Purpose
c_wr_accounts_v4	User accounts (teacher/student)
c_wr_students_v4	Student list (name, ID)
c_wr_assign_v4	Assignments and submissions
c_wr_modules_v4	Modules and submissions
c_wr_quiz_v4	Quizzes and attempts
c_wr_role_v4	Current logged-in user role
🔧 Development Notes
Built with vanilla HTML, CSS, and JavaScript

No external dependencies

Uses Base64 data URLs for file storage (limited to ~5MB)

All modals close by clicking the backdrop

Responsive design (sidebar hides on mobile)

🧹 Reset Demo
Click “Reset Demo” in the sidebar to:

Clear all demo data (students, assignments, modules, quizzes)

Restore only the default teacher account (teacher / 12345)

📄 File Structure
Only one file:

index.html — Contains all HTML, CSS, and JavaScript

🧪 Sample Data Included
On first load, the app creates:

1 sample student (Louisana Mallari)

1 sample assignment (Business Plan Outline)

1 sample module (Introduction to ICT)

1 sample quiz (Week 1 Quiz)

📱 Responsive Design
Sidebar hides on screens ≤ 900px wide

Modals adjust to screen size

Mobile-friendly buttons and inputs

✅ Browser Compatibility
Works in modern browsers with JavaScript enabled:

Chrome, Firefox, Edge, Safari

📌 Disclaimer
This is a front‑only demo:

File uploads are stored in localStorage as Base64 strings

Not suitable for production use

No server, no real database, no security beyond local storage

👤 Author
Werlyn Dee Ramos — Google Classroom Modules Demo
