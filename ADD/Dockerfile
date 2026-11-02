# ADD also does same as copy, but it has extra capabilities
# ADD has some additional capabilities.
# Extract local .tar archives automatically.
# Download files from HTTP/HTTPS URLs with limitations
# Git repository support with limitations
# Simplicity and More features

FROM almalinux:9

RUN dnf install nginx -y

RUN rm -rf /usr/share/nginx/html/index.html

ADD https://raw.githubusercontent.com/Pkumar1618/3-tier-architecture/refs/heads/main/readme.MD /usr/share/nginx/html/index.html

CMD ["nginx", "-g", "daemon off;"]