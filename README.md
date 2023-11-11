Installation:
```angular2html
pip install -r requirements.txt
```

Create database:
```angular2html
python manage.py migrate
```

Generate fake database or default 10 blogs:
```angular2html
python.exe .\manage.py fake_blogs --num=your_number

python.exe .\manage.py fake_blogs
```

Run doker:
```angular2html
docker run -p 6379:6379 redis
```

Run server:
```angular2html
python.exe manage.py runserver
```