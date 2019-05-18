FROM debian

LABEL app="FirstCommit"
ENV MURILO="LINDO"

RUN apt update && apt install -y stress && apt clean

CMD stress --cpu 1 --vm-bytes 64M --vm 1
