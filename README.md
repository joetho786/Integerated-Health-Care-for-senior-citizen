# Integerated-Health-Care-for-senior-citizen
## Steps to setup backend server
- Clone the repo by using the command ```git clone https://github.com/joetho786/Integerated-Health-Care-for-senior-citizen.git```
- cd into the medicare directory
- Do ```pipenv shell```
- ```pipenv install```
- Now makemigrations using ```python manage.py makemigrations```
- ```python manage.py migrate```
- Create SuperUser account for admin privileges ``` python manage.py createsuperuser```
- To run server ```python manage.py runserver```
