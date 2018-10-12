FROM ubuntu:18.04

RUN apt-get update && \
    apt-get install -y guile-2.2 guile-2.2-dev guile-2.2-doc guile-2.2-libs guile-json && \
    rm -rf /var/lib/apt/lists/*

ADD guile /root/.guile

CMD ["guile"]

