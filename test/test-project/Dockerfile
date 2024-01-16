FROM verdaccio/verdaccio:latest

# Set the container name
ENV container_name='verdaccio'

# Expose the port
EXPOSE 4873

# Mount the configuration volume
VOLUME /verdaccio/conf

CMD ["chown -R 100:101 /opt/verdaccio"]
