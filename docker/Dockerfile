ARG SUPERSET_VERSION=4.0.2

FROM apache/superset:${SUPERSET_VERSION}
COPY requirements.txt .

USER root

RUN set -ex; \
    apt-get update; \
    pip install -r requirements.txt; \
    rm -rf /var/lib/apt/lists/* requirements.txt

USER superset

