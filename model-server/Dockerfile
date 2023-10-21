FROM python
COPY requirements-server.txt .
RUN pip install -r requirements-server.txt
COPY main-server.py .
CMD ["flask", "--app", "main-server". "run", "--host=0.0.0.0"]
