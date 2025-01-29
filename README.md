# OAI RAN Central Unit (CU) ROCK

Container image for the OAI RAN Central Unit (CU).

## Usage

```console
docker pull ghcr.io/canonical/oai-ran-cu:2.2.0
docker run -it ghcr.io/canonical/oai-ran-cu:2.2.0
```

## To tag image
```console
sudo rockcraft.skopeo --insecure-policy copy \
    oci-archive:"${rock_file}" \
    docker-daemon:"docker.io/<your-dockerhub-username>/${image_name}:${version}"
```