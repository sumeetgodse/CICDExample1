FROM python:3.6.4-alpine
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 5000
ENV FLASK_APP weather.py
CMD ["flask", "run", "--host=0.0.0.0"]
