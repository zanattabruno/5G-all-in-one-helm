FROM zanattabruno/free5gc-base:v3.1.1 AS builder
FROM towards5gs/free5gc-n3iwf:v3.1.1

# Set working dir
WORKDIR /free5gc/n3iwf
RUN mkdir -p config/ config/TLS/

# Copy executable and default certs
COPY --from=builder /free5gc/config/TLS/n3iwf.pem ./config/TLS/
COPY --from=builder /free5gc/config/TLS/n3iwf.key ./config/TLS/