FROM hyperledger/fabric-baseimage:latest
RUN rm -rf /opt/go
COPY --chown=500:500 go /opt/go
ENV GOCACHE=/opt/gopath/.cache/go-build
