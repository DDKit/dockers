FROM alpine
WORKDIR /web
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.tuna.tsinghua.edu.cn/g' /etc/apk/repositories \
    && apk update \
    && apk add --no-cache python3 py3-pip \
    && ln -sf python3 /usr/bin/python
# docker build -t duanchanghe/alpine_py .
# docker push duanchanghe/alpine_py:latest
