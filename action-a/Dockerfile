FROM debian:9.5-slim

LABEL com.github.actions.name="Code Climate Action"
LABEL com.github.actions.description="Publish code coverage to Code Climate"
LABEL com.github.actions.icon="code"
LABEL com.github.actions.color="gray-dark"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]