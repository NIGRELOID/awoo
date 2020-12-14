FROM "debian:sid-slim"

EXPOSE 22/tcp

RUN apt-get --yes update
RUN apt-get --yes install endlessh
CMD /usr/bin/endlessh -v -p 22