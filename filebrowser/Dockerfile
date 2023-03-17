FROM filebrowser/filebrowser

RUN mkdir /config
COPY filebrowser.json /config

ENTRYPOINT [ "/filebrowser", "-c", "/config/filebrowser.json" ]