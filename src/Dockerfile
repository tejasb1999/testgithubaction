# Use the official Python 3.12.3 image from Docker Hub
FROM python:3.12.10-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any necessary dependencies
# In your case, there may be none, but you can include them here if needed (e.g., requirements.txt)
RUN pip install -r requirements.txt

# Command to run your Python script (or replace with the entry point to your application)
CMD ["python", "src/math_operations.py"]
