from postgres:9.6
MAINTAINER Anton Goroshkin <neobht@sibsau.ru>
RUN localedef -i ru_RU -c -f UTF-8 -A /usr/share/locale/locale.alias ru_RU.UTF-8
ENV LANG ru_RU.utf8

RUN set -eux; \
    apt-get update; \
    apt-get install -y --no-install-recommends pgactivity; \
    rm -rf /var/lib/apt/lists/*



