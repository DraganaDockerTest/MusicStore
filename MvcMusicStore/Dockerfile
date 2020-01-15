FROM microsoft/aspnet:latest
ARG source
WORKDIR /inetpub/wwwroot
COPY ${source:-obj/Docker/publish} .
