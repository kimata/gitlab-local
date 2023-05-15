FROM gitlab/gitlab-ee:15.10.7-ee.0

COPY local-ca.crt /usr/local/share/ca-certificates/
RUN update-ca-certificates
