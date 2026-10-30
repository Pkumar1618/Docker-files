# used to let the users know what are the ports this container will open when it runs.. EXPOSE instruction will not effect functionality it will only gives information
# The EXPOSE instruction doesn't actually publish the port.

FROM almalinux:9

RUN dnf install nginx -y

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]