FROM python:3.10-slim

WORKDIR /skillradar

COPY . .

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8080

ENV FLASK_RUN_HOST=0.0.0.0
ENV FLASK_RUN_PORT=8080

CMD ["python", "app.py"]
