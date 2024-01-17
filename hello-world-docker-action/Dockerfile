# Use the alpine:3.10 base image
FROM alpine:3.10
# Copy entrypoint.sh to the container
COPY entrypoint.sh /entrypoint.sh
# Make entrypoint.sh executable
RUN chmod +x entrypoint.sh
# Execute entrypoint.sh when the container starts
ENTRYPOINT ["/entrypoint.sh"]
