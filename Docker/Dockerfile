FROM python:3.10.6
ENV PYTHONUNBUFFERED=1
WORKDIR /usr/src/app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
EXPOSE 8000
CMD ["python3","manage.py","runserver","0.0.0.0:8000"]