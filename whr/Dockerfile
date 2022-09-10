FROM python:bullseye

ADD src/whr930.py /

RUN apt-get install usbutils

RUN pip install pyserial
RUN pip install paho-mqtt

CMD [ "python", "./whr930.py" ]