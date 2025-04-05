# 📝 Word Counter App using Django

A simple yet functional web application built with Django that takes user-submitted text and counts the frequency of each word. Designed to demonstrate core Django functionality and text processing capabilities.

---

# 🌟 Features

- ✍️ Users can input any block of text.
- 🔢 The app calculates and displays:
  - Total word count
  - Frequency of each unique word
- ⚠️ Includes input validation and error handling.
- 📱 Responsive and clean UI.

---

# 🛠️ Tech Stack

- **Frontend**: HTML, CSS (Bootstrap)
- **Backend**: Python, Django
- **Database**: SQLite (default)

---

# 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sayali-2004/word-counter-django.git
   cd word-counter-django
2. **Create and activate virtual environment (recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
4. **Run migrations**
   ```bash
   python manage.py migrate
5. **Run the development server**
   ```bash
   python manage.py runserver

---

# 📁 Project Structure
word-counter-django/
├── wordcounter/           # Django app
│   ├── templates/
│   │   └── index.html     # Main UI template
│   └── views.py           # Word counting logic
├── wordcounter_project/   # Django project
├── manage.py
└── requirements.txt

---

#🎯 Use Cases

1. Basic NLP/text-processing demonstration
2. Django learning project
3. Useful utility for counting word frequency

