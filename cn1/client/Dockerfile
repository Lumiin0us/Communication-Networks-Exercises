FROM python:3.10.11
WORKDIR /client
COPY . /client
RUN pip install --upgrade pip cython six && \
    pip install -r requirements.txt

EXPOSE 61616
CMD ["python3", "client.py"]