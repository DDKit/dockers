FROM ubuntu
WORKDIR /code
RUN apt update \
    && apt install -y python3 \
    && apt install -y python3-pip \
    && ln -sf python3 /usr/bin/python \
    && pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
RUN apt install -y mysql-server \
    && apt install -y libmysqlclient-dev \
    && apt install -y libmariadb-dev
# docker build -t duanchanghe/ubuntu_py .
# docker push duanchanghe/ubuntu_py:latest
