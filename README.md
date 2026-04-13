# OfficeEase 🏢

OfficeEase is a Django-based web application designed to manage office-related tasks, courses, and accounts with multi-language support.

---

## 🛠️ Technologies Used

### Core Framework & Libraries
- **Django**: High-level Python Web framework.
- **django-modeltranslation**: For translating dynamic content in the database.
- **Font Awesome**: Used for UI icons.

### Project Modules
- **`accounts/`**: Manages user authentication, profiles, and account-related logic.
- **`courses/`**: Handles course management, including modules, lessons, and quizzes.
- **`core/`**: Contains core project logic and shared components.

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have Python installed on your system. You can check this by running:
```bash
python --version
```

### 2. Setting Up a Virtual Environment (Recommended)
It is highly recommended to use a virtual environment to isolate project dependencies.

**On Windows:**
```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
.\venv\Scripts\activate
```


### 3. Install Dependencies
Once the virtual environment is activated, install the required libraries:
```bash
pip install -r requirements.txt
```

---

## 🖥️ Running the Project

To start the development server, run the following command:

```bash
python manage.py runserver
```

The application will be available at `http://127.0.0.1:8000/`.

---

## 🌍 Translations

The project supports multiple languages (English, French, Hindi, Burmese). If you make changes to translation files (`.po` files), you must compile them for the changes to take effect.

### Compile Translation Messages
```bash
python manage.py compilemessages
```

> [!NOTE]
> You may need to have `gettext` installed on your system to use translation commands.

---

## 📂 Project Structure
- `my_project/`: Main project configuration (settings, URLs).
- `locale/`: Translation files for different languages.
- `static/`: Global static assets (CSS, JS, Images).
- `templates/`: Global HTML templates.
