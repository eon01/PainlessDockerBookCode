FROM busybox
RUN busybox wget http://url_to_python_executable && busybox wget http://url_to_code
RUN chmod +x /python3.2-static
ENTRYPOINT ["/python3.2-static", "/app.py"]
