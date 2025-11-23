FROM kong/kong-gateway:3.12

USER root

# (Optional: add config/templates/plugins here)
# COPY kong.conf /etc/kong/kong.conf

USER kong

ENTRYPOINT ["/entrypoint.sh"]
CMD ["kong", "docker-start"]
