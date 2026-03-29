# ARG provide variabls to the image and this can be 1st instruction in a special to supply the version to base image
ARG version
# This version can't be accessed as a variable or anything after FROM instruction.
FROM almalinux:${version:-8}
ARG COURSE="Docker" \
      TRAINER="SivaKumar" \
      DURATION="150"  \
      AUTHER="joindevops"
RUN echo "Trainer is: ${TRAINER}, version is: ${version} "
CMD [ "sleep", "200" ]      

#Arg variables can't be accessed inside container, they are accessible only at the time of image building. ENV variables can be accessed in container.