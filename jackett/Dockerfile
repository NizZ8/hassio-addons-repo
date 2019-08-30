FROM linuxserver/jackett

# MOFIFY DATA PATH
RUN sed -i "s|config|data|g" /etc/services.d/jackett/run

VOLUME [ "/data" ]