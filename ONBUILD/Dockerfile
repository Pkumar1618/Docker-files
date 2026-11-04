# ONBUILD is used to trigger few instructions at build when a user is using our image.

FROM almalinux:9

RUN dnf install nginx 

RUN rm /usr/share/nginx/html/index.html

# This onbuild instruction runs only, when any user uses your image
ONBUILD COPY index.html /usr/share/nginx/html/index.html
    
CMD ["nginx", "-g", "daemon off;"]