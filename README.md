# Use the official Python image
FROM python:3.10-slim

# Set the working directory
WORKDIR /app

# Copy app file into the container
COPY app.py .

# Command to run the app
CMD ["python", "app.py"]






print("Hello from inside a Docker container!")
