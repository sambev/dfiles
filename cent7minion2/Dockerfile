FROM ch3ll/rand_images:samt-cent7

MAINTAINER Sam Beveridge

ADD minion /etc/salt/minion

ENTRYPOINT ["salt-minion", "-l", "debug"]
