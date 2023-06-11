# Use the official MongoDB image as the base image
FROM mongo:latest

# Copy the MongoDB configuration file to the container
COPY mongod.conf /etc/mongod.conf

# Expose the MongoDB port
EXPOSE 27017

# Start the MongoDB service when the container starts
CMD ["mongod", "--config", "/etc/mongod.conf"]
