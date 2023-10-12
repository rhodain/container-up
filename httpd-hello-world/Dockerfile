FROM ubi9-minimal:latest
RUN ls /etc/pki/entitlement
RUN  ls -lR /etc/rhsm*
RUN microdnf update
COPY ./public_html/ /app

