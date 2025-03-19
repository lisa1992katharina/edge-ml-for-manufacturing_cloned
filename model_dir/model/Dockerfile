FROM python:3.12.3
RUN apt-get update -y \
sudo apt-get install gcc python3-dev
RUN python -m pip install --no-cache-dir --upgrade pip \
&& python -m pip install -U setuptools \
python3-dev \       
build-essential \       
liblz4-dev \       
&& apt-get clean
