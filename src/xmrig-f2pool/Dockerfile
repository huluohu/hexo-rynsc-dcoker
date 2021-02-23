FROM centos:latest
MAINTAINER huluohu huluohu@huluohu.com
RUN  mkdir /xmrigdir && touch xmrig.log
WORKDIR /xmrigdir
COPY xmrig/* /xmrigdir/
ENTRYPOINT ["/xmrigdir/xmrig"]
