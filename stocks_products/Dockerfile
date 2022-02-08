FROM python:3.7

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt && \
    python manage.py migrate

CMD ["python", "manage.py", "runserver"]