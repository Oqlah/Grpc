FROM python
WORKDIR /app
COPY ./app.py /app/app.py
COPY ./requirements.txt /app/requirements.txt
RUN pip install -r requirements.txt
EXPOSE 8080
CMD ["python", "app.py"]
