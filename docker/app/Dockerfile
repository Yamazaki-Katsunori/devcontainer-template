FROM arm64v8/amazonlinux:2023

# TODO : 各言語用の追加パッケージなどを記述する
RUN yum update -y && \
    yum install -y \
        git \
        tar \
        gzip \
        unzip \
        zip \
        awscli \
        shadow-utils && \
    yum clean all

WORKDIR /workspace
