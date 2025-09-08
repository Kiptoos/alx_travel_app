# alx_travel_app (flattened layout for checker)

- Swagger at `/swagger/`
- App at `/api/listings/`

## Setup
```
python -m venv venv && source venv/bin/activate
pip install -r requirement.txt
cp .env.example .env  # edit credentials
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
