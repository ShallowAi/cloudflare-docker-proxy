# cloudflare-docker-proxy

![deploy](https://github.com/ciiiii/cloudflare-docker-proxy/actions/workflows/deploy.yaml/badge.svg)

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/ciiiii/cloudflare-docker-proxy)

> If you're looking for proxy for helm, maybe you can try [cloudflare-helm-proxy](https://github.com/ciiiii/cloudflare-helm-proxy).

## Deploy

1. fork this project
2. modify the link of the above button to your fork url
3. click the button, you will be redirected to the deploy page

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/ciiiii/cloudflare-docker-proxy)

## Usage

```shell
# docker pull hello-world:latest
docker pull docker.swai.top/hello-world:latest
# docker pull quay.io/kubernetes-ingress-controller/nginx-ingress-controller:latest
docker pull quay.swai.top/kubernetes-ingress-controller/nginx-ingress-controller:latest
# docker pull gcr.io/distroless:latest
docker pull gcr.swai.top/distroless
# docker pull k8s.gcr.io/sig-storage/csi-provisioner:latest
docker pull k8s-gcr.swai.top/sig-storage/csi-provisioner:latest
# docker pull registry.k8s.io/pause:latest
docker pull k8s.swai.top/pause:latest
# docker pull ghcr.io/shallowai/php-fpm:main
docker pull ghcr.swai.top/shallowai/php-fpm:main
# docker pull docker.cloudsmith.io/OWNER/REGISTRY/IMAGE_NAME:TAG
docker pull cloudsmith.swai.top/OWNER/REGISTRY/IMAGE_NAME:TAG
# docker pull public.ecr.aws/docker/library/alpine:latest
docker pull ecr.swai.top/docker/library/alpine:latest
```