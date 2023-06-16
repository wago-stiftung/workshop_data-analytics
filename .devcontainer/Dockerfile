FROM jupyter/minimal-notebook:python-3.10

ENV JUPYTER_TOKEN="makeathon"

# install packages
COPY requirements.txt ./
RUN pip install -r requirements.txt

WORKDIR /makeathon