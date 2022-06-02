FROM bash:latest

ENV TRIGGER_REBUILD=1

RUN bash -c "for i in $(seq -s " " 1 600); do echo "$i"; sleep 1; done"
