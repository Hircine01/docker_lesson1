FROM python:3.12.8-alpine3.20

WORKDIR /app

ENV PYTHONONBUFFERED=1

RUN pip install --upgrade pip

COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt


COPY . .


CMD ["python", "app.py"]