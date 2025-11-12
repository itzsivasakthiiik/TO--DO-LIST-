
## ⚙️ Installation and Setup

### 1️⃣ Clone the Repository
bash
git clone https://github.com/<your-username>/Django-To-Do-list-with-user-authentication.git
cd Django-To-Do-list-with-user-authentication
2️⃣ Create a Virtual Environment
bash
Copy code
python -m venv venv
venv\Scripts\activate
3️⃣ Install Dependencies
Using Pipenv:

bash
Copy code
pip install pipenv
pipenv install
or using pip:

bash
Copy code
pip install django
4️⃣ Apply Database Migrations
bash
Copy code
python manage.py migrate
5️⃣ (Optional) Create a Superuser
bash
Copy code
python manage.py createsuperuser
6️⃣ Run the Development Server
bash
Copy code
python manage.py runserver
Visit the app in your browser:
👉 http://127.0.0.1:8000/

![DEMO](../master/Django%20To%20Do%20List%20App.jpg)
