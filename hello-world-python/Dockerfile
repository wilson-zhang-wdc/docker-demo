# 1. docker build --no-cache -t hello-world -f hello-world-python/Dockerfile .
# 2. docker run hello-world

# Use the official Python image as the base image
FROM python:3

# Set the working directory inside the container
WORKDIR /app

# Copy the python file into the container at /app
COPY ./hello-world-python/app.py /app

# Run the command to execute the "app.py" file when the container starts
CMD ["python", "app.py"]
