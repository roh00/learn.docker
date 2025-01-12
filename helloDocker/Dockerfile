FROM python:3.9-slim

WORKDIR /app

COPY . /app/

RUN pip install --no-cache -r requirements.txt

EXPOSE 8080

CMD [ "uvicorn" , "app:app", "--host", "0.0.0.0" ,"--port", "8080"]
#uvicorn app_name:app --host 0.0.0.0 --port 8000
