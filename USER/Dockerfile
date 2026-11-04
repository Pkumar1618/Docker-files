# for security you should not run containers using root user, it must be on normal user. Atleast last instruction should USER <some-username>

FROM almalinux:9

RUN dnf install nginx -y

RUN useradd expense
USER expense
CMD ["sleep", "100"]