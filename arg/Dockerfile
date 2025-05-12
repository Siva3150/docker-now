ARG version 
# FROM almalinux:${version:-9}
FROM almalinux:${version}
ARG course="Devops with AWS" \
    duration="120hrs"
ENV duration=$duration
RUN echo "course: $course, duration: $duration"
CMD ["sleep", "100"]