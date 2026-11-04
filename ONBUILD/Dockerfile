# ONBUILD is used to trigger few instructions at build when a user is using our image.

FROM almalinux:9

RUN dnf install nginx -y

RUN rm -f /usr/share/nginx/html/index.html

# This onbuild instruction runs only, when any user uses your image
ONBUILD COPY index.html /usr/share/nginx/html/index.html

# ONBUILD RUN echo "ONBUILD instruction executed"

CMD ["nginx", "-g", "daemon off;"]