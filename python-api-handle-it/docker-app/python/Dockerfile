FROM python:3

WORKDIR /usr/src/app

RUN pip3 install Flask

ENV FLASK_APP="main"

CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]