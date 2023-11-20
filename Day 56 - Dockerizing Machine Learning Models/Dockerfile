FROM python:3.9
RUN mkdir /app
WORKDIR /app
COPY . .
RUN pip install --no-cache-dir --upgrade -r requirements.txt
WORKDIR /app
EXPOSE 3000
CMD ["python", "script.py"]