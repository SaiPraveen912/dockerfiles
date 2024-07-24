ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG COURSE=DevOps
ARG TRAINER=Praveen
ENV Duration=120HRS
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}, duration is: ${Duration}}"
CMD ["sleep", "60"]