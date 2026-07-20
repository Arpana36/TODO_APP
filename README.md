# 📝 To-Do App

A simple and efficient **To-Do application** built with **Python (Flask)** and **HTML/CSS**.  
This project demonstrates CRUD operations, dynamic content rendering, and clean project structure — ideal for learning and showcasing web development skills.

---------------------------------------------------

## 🚀 Features
- Add new tasks
- Mark tasks as complete/incomplete
- Delete tasks
- Responsive UI with clean layout
- Persistent storage using SQLite 

---------------------------------------------------

## 📂 Project Structure
TODO_APP/
|-- run.py      #Entry point
|
|-- app/        #core application logic
|     |
|     |-- __init__.py
|     |-- models.py
|     |-- route/              #Route handlers
|     |     |-- __init__.py
|     |     |-- auth.py
|     |     |__ task.py
|     |
|     |-- templates/          #Html templates
|     |       |-- base.html
|     |       |-- login.html
|     |       |-- register.html
|     |       |__ tasks.html
|     |
|     |__ static/               #Stylesheets
|            |-- css/
|                 |__ style.css
|
|-- forms.py               #Form definitions
|-- requirements.txt       #Dependencies
|
|-- screenshots/          #app screenshots(add_task,home,login,complete_delete)
|
|-- LICENSE
|-- .gitignore
|__ README.md              #Documentation


---------------------------------------------------

## ⚙️ Tech Stack
- **Backend:** Python, Flask  
- **Frontend:** HTML, CSS, Jinja2  
- **Database:** SQLite  
- **Auth:** Flask-WTF, Werkzeug security  

---------------------------------------------------

## ▶️ Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/todo-app.git
   cd todo-app
 
2. Install dependencies

  open in bash
  pip install -r requirements.txt
  
  
3. Run the app

 python run.py

4. Open in browser


  http://127.0.0.1:5000/


----------------------------------------------------------

📸 Screenshots
 ### Login page
 ![login page](app/routes/screenshots/login.png)

 ![home page](app/routes/screenshots/home.png)

 ![add task](app/routes/screenshots/add_task.png)

 ![delete task](app/routes/screenshots/delete.png)

-----------------------------------------------------------

📌 Future Improvements
 1. Deploy on Heroku/Render

 2. Add dark mode UI

3. Add Register page

-----------------------------------------------------------

📄 License
Licensed under the MIT License.

-----------------------------------------------------------

## 👤 Author

**Arpana**  
Diploma in Computer Science Engineering (2025)  
Actively seeking **junior web developer** 

- 💻 Skills: Python, Flask, HTML, CSS, GitHub  
 - 📧 Contact: arpana324252@gmail.com