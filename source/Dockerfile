# official docker python image
FROM python:3.11-slim-bookworm  

# set working directory
WORKDIR /app  

# Copy the current directory contents into the container at /app
COPY . /app

# Install dependencies
RUN pip install flake8 pyfakefs

# Run app.py 
CMD ["python", "/app/todo.py"]
