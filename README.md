### Virtual environment
```
python -m venv venv
```
```
venv\Scripts\Activate
```
### Python requirements
```
cd <my-webapp>
```
```
pip install -r requirements.txt
```
### Postgres
```
psql -U postgres
```
```
CREATE DATABASE <database_name> WITH OWNER postgres;
```
#### .env
```
DATABASE_URL=postgresql://postgres:<password>@localhost:5432/<database_name>
```
### Migrate the data
```
python manage.py migrate
```
### React Frontend
```
cd frontend
```
```
npm install
```
### Run the app
```
cd ..
```
```
python manage.py runserver
```