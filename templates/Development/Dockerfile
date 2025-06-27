# 1. Use an existing Python image
FROM python:latest

# 2. Set the working directory inside the container
WORKDIR /app

# 3. Install the project dependencies
RUN pip install --no-cache-dir -r requirements.txt

# 4. Copy the the app files inside the container
COPY . .

# 5. Set environment variables
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

# 6. Define the command to run the app
CMD ["python", "app.py"]