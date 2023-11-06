# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY score_possibilities.c .
# Compile the C program
RUN gcc -o score_possibilities score_possibilities.c
# Set the command to run when the container starts
CMD ["./score_possibilities"]