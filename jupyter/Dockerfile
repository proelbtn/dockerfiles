FROM jupyter/datascience-notebook

USER root

RUN apt update && \
    apt install -y fonts-noto fonts-ipafont fonts-ipaexfont fonts-vlgothic fonts-mplus && \
    rm -rf /var/lib/apt/lists/*

RUN pip install beautifulsoup4

USER jovyan
