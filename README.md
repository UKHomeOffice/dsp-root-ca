# Digital Services Platform Public CA certificates

This repository contains Root and Intermediate CA certificates for DSP platform.


## How to install

### Alpine Linux

```bash
apk add ca-certificates curl
curl -s https://raw.githubusercontent.com/UKHomeOffice/dsp-root-ca/master/root-ca.pem > /usr/local/share/ca-certificates/dsp_root_ca.crt
curl -s https://raw.githubusercontent.com/UKHomeOffice/dsp-root-ca/master/intermediate-ca.pem > /usr/local/share/ca-certificates/dsp_intermediate_ca.crt
update-ca-certificates
```

