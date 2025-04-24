# 🏋️‍♂️ Fitness Tracker Website

A responsive web application built with Flask that enables users to monitor their fitness activities, set goals, and track progress over time.

## 🚀 Features

- **User Authentication**: Secure registration and login system to protect user data.
- **Activity Logging**: Record workouts with details like type, duration, and calories burned.
- **Progress Dashboard**: Visualize fitness progress through interactive charts and summaries.
- **Goal Setting**: Define personal fitness goals and monitor achievements.
- **Responsive Design**: Seamless experience across desktops, tablets, and mobile devices.

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Flask
- **Database**: MySQL
- **Styling**: Custom CSS

## 📁 Project Structure

```
 Fitness-Tracker-Website/
├── app.py
├── config.py
├── forms.py
├── models.py
├── routes.py
├── requirements.txt
├── static/
│   └── style.css
├── templates/
│   ├── base.html
│   ├── dashboard.html
│   ├── login.html
│   └── register.html
└── README.md
```

## ⚙️ Installation

### Prerequisites

- Python 3.x
- MySQL Server
- pip (Python package installer)

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/123yogin/Fitness-Tracker-Website.git
   cd Fitness-Tracker-Website
   ```

2. **Create a virtual environment**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Configure the MySQL database**:

   - Create a MySQL database (e.g., `fitness_tracker`).
   - Update the `config.py` file with your MySQL credentials:

     ```python
     app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql+pymysql://username:password@localhost/fitness_tracker'
     ```

5. **Initialize the database**:

   ```bash
   flask shell
   >>> from app import db
   >>> db.create_all()
   >>> exit()
   ```

6. **Run the application**:

   ```bash
   flask run
   ```

   Access the app at `http://localhost:5000`.

## 🖼️ Screenshots

[Screenshot (45)](https://github.com/user-attachments/assets/e30299eb-7ec3-4652-9d00-37356abf77fd) 
[Screenshot (44)](https://github.com/user-attachments/assets/a14f2fa5-85a1-4765-b6aa-65153af0876b) 
[Screenshot (43)](https://github.com/user-attachments/assets/62ab7df9-d034-4f4c-9649-26c0cb868d9c)
[Screenshot (42)](https://github.com/user-attachments/assets/8d6d2aad-354f-4752-81a4-a5cff4dd647e) 

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 📬 Contact!


For questions or feedback, please open an issue or contact [123yogin](https://github.com/123yogin) at [Email](mailto:parmaryogin04@gmail.com).
