FROM node:10.14.1-alpine
WORKDIR /book
RUN npm install -g gitbook-cli \
    && gitbook init
RUN gitbook fetch 3.0.0 \
    && gitbook uninstall 3.2.3
RUN apk add --no-cache bash
# docker build -t duanchanghe/gitbook .
# docker push duanchanghe/gitbook:latest
