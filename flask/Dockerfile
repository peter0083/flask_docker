# dockerfile for flask app + uWSGI container
# contains a list of instructions for docker to execute to build out the container.
FROM python:3.7.2-stretch

# set the working directory to /app
WORKDIR /app

# copy the current directory contents into the container at /app
ADD . /app

# install the dependencies
RUN  pip install -r requirements.txt

# run the command to start uWSGI
CMD ["uwsgi", "app.ini"]