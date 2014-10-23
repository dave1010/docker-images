FROM jolicode/base
MAINTAINER Joel Wurtz <jwurtz@jolicode.com>

# Add HHVM Repository
RUN wget -O - http://dl.hhvm.com/conf/hhvm.gpg.key | apt-key add -
RUN echo deb http://dl.hhvm.com/ubuntu precise main | tee /etc/apt/sources.list.d/hhvm.list

# Install deps
RUN apt-get update && apt-get install -y hhvm

