FROM ubi9:latest
RUN rm /etc/rhsm-host
RUN ls /etc/pki/entitlement
RUN  ls -lR /etc/rhsm*
RUN  ls -lR /run/secrets/rhsm
RUN  dnf update
COPY ./public_html/ /app

