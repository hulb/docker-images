From python:3.10.4-alpine3.16

COPY requirements.txt requirements.txt

RUN apk add --no-cache gcc musl-dev python3-dev
RUN pip install -r requirements.txt
