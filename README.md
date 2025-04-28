 ## 🐦 Django TweetNest

A social media web app that replicates basic functionality of Twitter, built using Django.

### Tech Stack:
- Python
- Django
- SQLite (default database)

### Features:
- User authentication (Sign up, Login, Logout)
- Post tweets (280 character limit)
- View and delete your own tweets
- View tweets from all users


### How to Use:
1. **Sign Up**: Create a new account by registering with a username and password.
2. **Login**: Log in to access the dashboard and manage your tweets.
3. **Post a Tweet**: Once logged in, you can post tweets up to 280 characters.
4. **View Tweets**: You can view tweets from all users in the feed.


---

## 🚀 How to Run Locally

### Requirements:
- Python 3.x
- Django 3.x or higher

### Steps to Run:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/sathwikradarapu/Django-TweetNest.git
    cd Django-TweetNest
    ```

2. **Create a virtual environment:**

    ```bash
    python3 -m venv venv
    ```

3. **Activate the virtual environment:**

    - For Windows:

      ```bash
      venv\Scripts\activate
      ```

    - For macOS/Linux:

      ```bash
      source venv/bin/activate
      ```

4. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

5. **Apply migrations:**

    ```bash
    python manage.py migrate
    ```

6. **Create a superuser to access the Django admin panel:**

    ```bash
    python manage.py createsuperuser
    ```

7. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

8. Visit [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser to access the application.

---

## 🧑‍💻 Project Structure

Django-TweetNest/ ├── tweetnest/ # Main Django app directory │ ├── migrations/ # Database migrations │ ├── static/ # Static files like CSS, JavaScript, and images │ ├── templates/ # HTML templates │ ├── admin.py # Admin panel configurations │ ├── apps.py # App configuration │ ├── models.py # Database models (User, Tweet, etc.) │ ├── views.py # Views for handling requests and rendering templates │ └── urls.py # URL configurations ├── manage.py # Django management script ├── requirements.txt # Dependencies for the project ├── README.md # Project information and setup instructions ├── db.sqlite3 # SQLite database (generated after migration) └── .gitignore # Git ignore file to avoid pushing unnecessary

