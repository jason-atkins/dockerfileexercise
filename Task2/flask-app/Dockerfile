# Use Python 3.7 as a base image

# Copy contents into image
 
# install pip dependencies from requirements file
 
# Expose correct port

# Create an entrypoint

FROM python:3.7

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

EXPOSE 5000

ENV YOUR_NAME="Name from Dockerfile"

ENTRYPOINT ["python", "app.py"]
