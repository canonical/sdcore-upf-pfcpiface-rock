# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-upf-pfcpiface_2.0.1_amd64.rock docker-daemon:sdcore-upf-pfcpiface:2.0.1
docker run sdcore-upf-pfcpiface:2.0.1
```
