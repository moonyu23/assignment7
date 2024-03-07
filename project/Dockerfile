FROM ubuntu:latest
RUN mkdir -p /structure && chmod 777 /structure
USER sync
RUN touch /structure/sync-work
USER nobody
RUN touch /structure/nobody-work
USER root
RUN useradd collin -u 5000