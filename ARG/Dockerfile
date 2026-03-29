# ARG provide variabls to the image and this can be 1st instruction in a special to supply the version to base image
ARG version
FROM almalinux:${version:-8}
ARG COURSE="Docker" \
      TRAINER="SivaKumar" \
      DURATION="150"  \
      AUTHER="joindevops"
RUN echo "Trainer is: ${TRAINER}"
CMD [ "sleep", "200" ]      