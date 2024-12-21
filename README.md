This repository demonstrates an issue with Dockerfile optimization. The original Dockerfile uses a large base image and doesn't specify Python versions, leading to a bloated image and potential inconsistencies. The optimized version addresses these problems, resulting in a smaller and faster image.

**Original Dockerfile:** Uses a large base image (ubuntu:latest) and doesn't specify Python version.

**Optimized Dockerfile:** Uses a smaller base image (python:3.9-slim-buster) and specifies the Python version for consistency.