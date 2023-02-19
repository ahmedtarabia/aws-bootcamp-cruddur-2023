FROM python:3.10-slim-buster

# Inside Container
# Make a new folder inside the container
WORKDIR /backend-flask

# Outside Container -> Inside Container
# This contains the libraries we want to install to run the app
COPY requirements.txt requirements.txt

# Inside Container
# This will install the python libraries used for the app.
RUN pip3 install -r requirements.txt

# Outside Container -> Inside Container
# . means everything in the current directory. 
# . 1st period - /backend-flask (outside container)
# . 2nd period - /backend-flask (inside container)
COPY . .

# Set environment variables (envars)
# Inside container and will remain there when container is running.
ENV FLASK_ENV=development

EXPOSE ${PORT}

# CMD - command: 
# python3 -m flask run --host=0.0.0.0 --port=4567
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]