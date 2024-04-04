CONTRIBUTING.md # Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-upf-pfcpiface_1.4.0_amd64.rock docker-daemon:sdcore-upf-pfcpiface:1.4.0
docker run sdcore-upf-pfcpiface:1.4.0
```
