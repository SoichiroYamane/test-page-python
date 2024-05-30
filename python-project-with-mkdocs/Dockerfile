FROM python:3-buster

WORKDIR /app

RUN apt-get update

RUN apt-get install -y vim less
RUN pip install --upgrade pip
RUN pip install --upgrade setuptools

RUN python -m pip install poetry

RUN pip install -U \
  mkdocs \
  mkdocs-autorefs \
  mkdocs-material \
  mkdocs-markmap \
  mkdocs-material-extensions \
  mkdocstrings \
  mkdocstrings-python \
  plantuml-markdown \
  fontawesome-markdown \
  mdx_unimoji \
  python-markdown-math \
  pymdown-extensions

