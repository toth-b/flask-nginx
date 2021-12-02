FROM python:3.9-bullseye

# Set the working directory
WORKDIR /app

# Copy the content of the current working directory
ADD . /app

# Install dependencies
RUN pip install -r requirements.txt

# Run the command to start uWSGI
CMD [ "uwsgi", "app.ini" ]
