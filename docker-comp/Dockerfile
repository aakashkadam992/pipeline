FROM tiangolo/uwsgi-nginx-flask:flask
COPY . /app
WORKDIR /app
RUN pip install Flask
RUN pip install flask-mysql
ENTRYPOINT ["python"]
CMD ["app.py"]
