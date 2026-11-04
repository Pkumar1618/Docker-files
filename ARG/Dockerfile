# ARG is used to set the variables at build time onnly, not inside the container
# ARG vs ENV
# ---------
# 1. ENV variables can be accessed in image build time and container both.
# 2. ARG is only accessed at the time of image creation.
# 3. You can use ARG instruction before FROM in one special case i.e to supply version to the base image.
# 4. ARG instruction before FROM is only valid until FROM, it cant be accessed after FROM

# How can I access ARG values inside container?
# You can set arg value to env variable

# ENV var-name=$var-name

FROM almalinux:9

ARG course="DevOps with Aws" \
    duration="120hrs" \
    trianer="Jhon"
RUN echo "course: $course, duration: $duration, trianer: $trianer"
CMD ["sleep","100"] 
