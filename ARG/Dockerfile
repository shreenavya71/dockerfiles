ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG course=Docker
ARG trainer=sivakumar
ARG duration=120hrs
ENV duration=${duration}
RUN echo "course is : ${course}, trainer is : ${trainer}, duration is : ${duration}"
CMD [ "cat /etc/*release" ]