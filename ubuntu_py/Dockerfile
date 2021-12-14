FROM ubuntu
WORKDIR /code
RUN apt update \
    && apt install -y python3 \
    && apt install -y python3-pip \
    && ln -sf python3 /usr/bin/python \
    && pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
# docker build -t duanchanghe/ubuntu_py .
# docker push duanchanghe/ubuntu_py:latest
