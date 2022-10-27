# asciidoctor image
FROM asciidoctor/docker-asciidoctor
# pandoc core image
FROM pandoc/core

LABEL "version"="1.0"

# Setup entrypoint
COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
