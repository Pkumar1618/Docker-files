# An ENTRYPOINT allows you to configure a container that will run as an executable.
# 1. CMD can be overridden at runtime
# 2. You can't override ENTRYPOINT like CMD. If you try to do it will go and append to the        entrypoint command
# 3. for better results and best practices. CMD can provide args to ENTRYPOINT, So you can mention default args through CMD and you can override them at run time..

FROM almalinux:9

# CMD ["ping", "google.com"]

CMD ["google.com"]

ENTRYPOINT ["ping"]