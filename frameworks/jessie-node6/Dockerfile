FROM node:6.12.2-slim

MAINTAINER Wojciech Sielski <wsielski@team.mobile.de>

RUN cd /usr/local/bin/ && curl -O https://raw.githubusercontent.com/eBayClassifiedsGroup/PanteraS/master/frameworks/start.sh
RUN chmod +x /usr/local/bin/start.sh

ENV IMAGE panteras/jessie-node6
ENV HOME  /
WORKDIR /

ENTRYPOINT ["/usr/local/bin/start.sh"]

