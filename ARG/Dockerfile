ARG version
FROM lamalinux:${version:-9}
ENV  COURSE ="DevOps" \
     DURATION="120HRS" \
ARG TRAINER="Siva"
ENV TRAINER=$TRAINER
RUN echo "Hi, Cource is : ${COURSE}, duration is: ${DURATION}, trainer is : ${TRAINER} , version ${version}" 
CMD ["sleep", "1000"]