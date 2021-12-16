FROM python:3.11.0a3-alpine3.15

# RUN virtualenv /env

# ENV VIRTUAL_ENV /env
# ENV PATH /env/bin:$PATH
ENV PORT 8080

COPY app /cache/app

RUN pip install -r /cache/app/requirements.txt

WORKDIR /cache/app
CMD ["python", "main.py"]
