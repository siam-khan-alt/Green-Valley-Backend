# Green Valley Backend

Construction cost/progress/profitability management platform — backend (Django + DRF + PostgreSQL).

## Setup
1. Clone repo
2. python3 -m venv venv && source venv/bin/activate
3. pip install -r requirements.txt
4. Copy .env.example to .env and fill in values
5. python manage.py migrate
6. python manage.py createsuperuser
7. python manage.py runserver