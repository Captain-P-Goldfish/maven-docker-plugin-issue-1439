FROM openjdk:11.0.9.1-jre-slim

ENV TARGETDIR=/opt/app

WORKDIR ${TARGETDIR}

# Copy the freshly built artifact
COPY maven/ ${TARGETDIR}

ENTRYPOINT java -cp maven-docker-plugin-issue-1439.jar de.captaingoldfish.docker.issue.Hello

