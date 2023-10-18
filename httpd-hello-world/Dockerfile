FROM ubi9:latest
RUN chmod -R 611 /etc/pki/entitlement
RUN ls -lR /etc/pki/entitlement
RUN  ls -lR /etc/rhsm*
RUN  ls -lR /run/secrets/rhsm
RUN  dnf update
COPY ./public_html/ /app

