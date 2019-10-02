FROM python:alpine

WORKDIR /src
ADD . .
RUN pip install -r requirement.txt
EXPOSE 5000

CMD ["python","app.py"]
