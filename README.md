# Install JABAS root certificate

You can install the JABAS root certificate with this command on Linux:

```bash
sudo mkdir -p /usr/local/share/ca-certificates/ && \
    curl -L https://raw.githubusercontent.com/jabasai/bootstrap/refs/heads/main/jabas.ca.crt | sudo tee /usr/local/share/ca-certificates/jabas-ca.crt && \
    sudo update-ca-certificates
```
