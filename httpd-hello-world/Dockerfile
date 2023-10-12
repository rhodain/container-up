FROM ubi9-minimal:latest
RUN ls /etc/pki/entitlement
RUN  find /etc/rhsm*
RUN microdnf update
COPY ./public_html/ /app

