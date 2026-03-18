FROM almalinux:9
#CMD ["ping", "google.com"]
RUN dnf install git -y
RUN useradd siva

USER siva
ENTRYPOINT ["ping"]
CMD ["google.com"]

