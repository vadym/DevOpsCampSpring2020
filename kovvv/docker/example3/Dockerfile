FROM python:2.7
RUN pip install Flask
COPY ./hello-world.py /
ENV FLASK_APP=hello-world.py
EXPOSE 5000

CMD flask run --host=0.0.0.0 --port=5000
