FROM centos:centos7.7.1908

RUN yum -y update && yum clean all

RUN curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -o miniconda3.sh && \
    chmod +x miniconda3.sh && \
    bash miniconda3.sh && \
    ./miniconda3.sh -b 