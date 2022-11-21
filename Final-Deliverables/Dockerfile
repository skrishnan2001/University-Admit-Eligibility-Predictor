FROM python:3.8-slim-buster

RUN mkdir /app

WORKDIR /app

COPY . /app

RUN pip install --trusted-host pypi.python.org -r requirements.txt

EXPOSE 8501

CMD ["streamlit", "run", "app.py"]
