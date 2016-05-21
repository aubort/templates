FROM cloud9/workspace
MAINTAINER Pascal Aubort

ADD ./files/workspace /home/ubuntu/workspace

RUN chmod -R g+w /home/ubuntu/workspace && \
    chown -R ubuntu:ubuntu /home/ubuntu/workspace
    
# Install packages.
# For more details, check out this page: https://www.polymer-project.org/1.0/docs/tools/polymer-cli
RUN \
    npm install -g bower && \
    npm install -g polymer-cli