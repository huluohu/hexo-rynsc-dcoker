FROM centos/nodejs-12-centos7:latest
MAINTAINER huluohu huluohu@huluohu.com

RUN echo "Begin install dependences of hexo build & deploy... "
RUN npm install -g hexo
RUN npm install --unsafe-perm=true --allow-root

USER root
RUN yum install rsync
RUN echo "End installed dependences of hexo build & deploy... "

