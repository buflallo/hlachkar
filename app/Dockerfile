# Use an official lightweight Python image
FROM python:3.11-slim

# Set working directory inside the container
WORKDIR /app

# Copy the current directory contents into the container
COPY app.py .

# Install Flask
RUN pip install flask

# Expose port 8080
EXPOSE 8080

# Command to run the app
CMD ["python", "app.py"]

