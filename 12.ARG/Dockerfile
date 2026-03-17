# ARG version
# FROM almalinux:${version}

# ARG version
# FROM almalinux:${version}
# ARG COURSE
# ARG TRAINER
# RUN echo "Course is:${COURSE} TRAINER is: ${TRAINER}"
# CMD { "sleep","100" }


# ARG version
# FROM almalinux:${version:-9}
# ARG COURSE
# ARG TRAINER
# RUN echo "Course is:${COURSE} TRAINER is: ${TRAINER}"
# CMD { "sleep","100" }


ARG version
FROM almalinux:${version:-8}
ARG COURSE=DevSecOps
ARG TRAINER=LingaRao
ARG Duration=120HRS
RUN echo "Course is:${COURSE} TRAINER is: ${TRAINER}, Duration is:${Duration}"
CMD { "sleep","100" }