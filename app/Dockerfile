FROM python:3.7.3-alpine
COPY . /app
RUN pip install -r /app/requirements.txt
EXPOSE 8000
CMD python /app/main.py
