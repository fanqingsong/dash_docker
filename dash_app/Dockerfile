FROM python:3.9-slim

RUN mkdir -p /home/project/dash_app
WORKDIR /home/project/dash_app
COPY requirements.txt /home/project/dash_app
RUN pip install --no-cache-dir -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple


COPY . /home/project/dash_app

