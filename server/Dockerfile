FROM python:3.6

RUN mkdir -p /opt/dhcp
COPY requirements.txt /tmp/requirements.txt
RUN pip install -r /tmp/requirements.txt
COPY . /opt/dhcp/.
WORKDIR /opt/dhcp
CMD python main.py
