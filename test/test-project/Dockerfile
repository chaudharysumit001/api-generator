FROM verdaccio/verdaccio:latest

# Set the container name
ENV container_name='verdaccio'

# Expose the port
EXPOSE 4873

# Mount the configuration volume
VOLUME /verdaccio/conf

CMD [ "chown -R verdaccio:verdaccio /verdaccio &&\
exec guso verdaccio:verdacio  $APPDIR/bin/verdaccio --config /verdaccio/conf/config.yaml --listen $PROTOCOL://0.0.0.0:${PORT}" ]