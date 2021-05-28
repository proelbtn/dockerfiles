FROM jupyter/datascience-notebook

USER root

# ref: 
RUN apt update && \
    apt install -y fonts-noto fonts-ipafont fonts-ipaexfont fonts-vlgothic fonts-mplus && \
    rm -rf /var/lib/apt/lists/*

USER jovyan
