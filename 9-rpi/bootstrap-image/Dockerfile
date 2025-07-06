ARG BASE=quay.io/almalinuxorg/almalinux-bootc:9

FROM $BASE

COPY 10-bootc-growpart.cfg /etc/cloud.cfg.d/
RUN \
  dnf install -y cloud-init cloud-utils-growpart &&\
  systemctl enable cloud-init
