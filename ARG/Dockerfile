ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG COURSE=DevOps
ARG TRAINER=Praveen
ARG Duration=120HRS
ENV Duration=${Duration}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}, duration is: ${Duration}}"
CMD ["sleep", "60"]