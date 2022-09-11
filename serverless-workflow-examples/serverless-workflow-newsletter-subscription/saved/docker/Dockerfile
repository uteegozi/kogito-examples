# to build a new image with the opentelemetry javaagent included:
# Download the opentelemetry-javaagent.jar from https://github.com/open-telemetry/opentelemetry-java-instrumentation/releases/latest/download/opentelemetry-javaagent.jar
#  and copy the file into this folder where the Dockerfile resides
# Build the application with -Pknative profile
# Then run below command from inside folder if this Dockerfile
# podman build -t dev.local/serverless-workflow-newsletter-subscription-flow:1.1 .
FROM dev.local/serverless-workflow-newsletter-subscription-flow:1.0-SNAPSHOT
COPY opentelemetry-javaagent.jar ./tmp/opentelemetry-javaagent.jar