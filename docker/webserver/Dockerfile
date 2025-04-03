FROM arm64v8/amazonlinux:2023

# TODO : [カスタマイズ箇所]利用したいwebサーバーをインストールを記述する
# デフォルトをnginxにしているが、apacheなどに変更することも可能
RUN yum update -y && \
    yum install -y nginx tar gzip && \
    yum clean all

WORKDIR /workspace

CMD ["nginx", "-g", "daemon off;"]
