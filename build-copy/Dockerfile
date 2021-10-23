FROM nginx:latest
LABEL maintainer 'Dácio Lima - Cod'

ARG FLASK=flaskapp

ENV FLASK=${FLASK}

RUN echo '<h1>Sem conteudo</h1>' > /usr/share/nginx/html/conteudo.html

COPY *.html /usr/share/nginx/html