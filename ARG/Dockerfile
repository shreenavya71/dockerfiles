ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG course=Docker
ARG trainer=sivakumar
ENV duration=120hrs
RUN echo "course is : ${course}, trainer is : ${trainer}, duration is : ${duration}"
CMD [ "cat /etc/*release" ]