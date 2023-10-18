FROM python 
COPY requirements-train.txt .
RUN pip install -r requirements-train.txt
COPY main-train.py .
RUN main-train.py
