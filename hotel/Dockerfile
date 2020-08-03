FROM python:3.6
ENV PYTHONUNBUFFERED 1
RUN mkdir /hotel
WORKDIR /hotel
COPY requirement.txt /hotel/
RUN pip install -r requirement.txt
COPY . /hotel/
CMD python3 manage.py runserver 0.0.0.0:8000 