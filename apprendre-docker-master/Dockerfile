FROM python:3.12.4-slim
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
EXPOSE 80
ENV NOM coca
CMD ["python", "app.py"]
