FROM python: latest
LABEL MAINTAINER="melkin sj ‹melkin.mel@gmail.com›"
WORKDIR /usr/src/app
# Copy and install dependencies
COPY requirements.txt
RUN pip install -r requirements.txt
# Copy application code
COPY app-py •
# Expose the application port
EXPOSE 80
# Set the default command
CMD ["python", "app-py"]