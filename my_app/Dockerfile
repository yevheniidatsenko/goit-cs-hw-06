FROM python:3.12-slim

WORKDIR /my_app

COPY . /my_app/

RUN pip install --no-cache-dir -r /my_app/requirements.txt

EXPOSE 3000
EXPOSE 6000

CMD ["python", "main.py"]