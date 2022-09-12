# to build a new image with the opentelemetry javaagent included:
# Download the opentelemetry-javaagent.jar from https://github.com/open-telemetry/opentelemetry-java-instrumentation/releases/latest/download/opentelemetry-javaagent.jar
#  and copy the file into this folder
# Make sure that the application was built, so that image
#  dev.local/serverless-workflow-newsletter-subscription-flow:1.0-SNAPSHOT exists
# Then run below command from inside this folder
# podman build -t dev.local/serverless-workflow-newsletter-subscription-flow:1.0-SNAPSHOT .
# Repeat the same for the serverless-workflow-newsletter-subscription-flow image
#
FROM quay.io/uegozi/serverless-workflow-newsletter-subscription-flow:1.0-SNAPSHOT
COPY opentelemetry-javaagent.jar ./tmp/opentelemetry-javaagent.jar