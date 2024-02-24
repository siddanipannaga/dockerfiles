FROM almalinux:8
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRANER
RUN echo "Course: ${COURSE},Trainer: ${TRANER}"
ENV COURSE=${COURSE}
ENV TRANER=${TRANER}
CMD ["sleep","100"]