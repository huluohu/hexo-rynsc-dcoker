FROM centos:latest
MAINTAINER huluohu huluohu@huluohu.com
RUN  mkdir /xmrig
WORKDIR /xmrig
VOLUME ["/xmrig","/xmrig"]
ENTRYPOINT ["nohup ./xmrig >> ./xmrig.log 2>&1"]
