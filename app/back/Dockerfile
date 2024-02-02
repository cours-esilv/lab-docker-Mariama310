FROM python:3
WORKDIR /app
COPY . .
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 8080
ENV NAME World
CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0", "--port=8080"]
#mm