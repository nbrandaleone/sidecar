# Use the Go v1.13 image for the base.
FROM golang:1.13

# Copy the proxy code to the container.
COPY main.go .

# Run the proxy on container startup.
ENTRYPOINT [ "go" ]
CMD [ "run", "main.go" ]

# Expose the proxy port.
EXPOSE 8000
