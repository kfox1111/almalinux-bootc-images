ARG BASE=quay.io/almalinuxorg/almalinux-bootc:9

FROM $BASE

RUN \
  dnf install -y cloud-init cloud-utils-growpart &&\
  systemctl enable cloud-init
