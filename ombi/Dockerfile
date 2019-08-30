FROM linuxserver/ombi

# MOFIFY DATA PATH
RUN sed -i "s|config|data|g" /etc/services.d/ombi/run

VOLUME [ "/data" ]