# django-simple-polling-system

## Getting Started

### Prerequisites

- Python 3.x
- Django 3.x

1. **Clone the Repository:**
    ```
    git clone git@github.com:RichieMuga/django-simple-polling-system.git
    ```

2. **Create a Virtual Environment:**
    ```
    python -m venv venv
    ```

3. **Activate the Virtual Environment:**
    - On Windows:
        ```
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```
        source venv/bin/activate
        ```

4. **Install Dependencies:**
    ```
    pip install -r requirements.txt
    ```

5. **Run Migrations:**
    ```
    cd pollingsite
    python manage.py migrate
    ```

6. **Create a Superuser (Optional):**
    ```
    python manage.py createsuperuser
    ```

7. **Run the Development Server:**
    ```
    python manage.py runserver
    ```

8. **Access the App:**
    Open your web browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to access on the browser.
