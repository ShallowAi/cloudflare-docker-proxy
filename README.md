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

```
  docker.swai.top
  quay.swai.top "https://quay.io",
  gcr.swai.top "https://gcr.io",
  k8s-gcr.swai.top "https://k8s.gcr.io",
  k8s.swai.top "https://registry.k8s.io",
  ghcr.swai.top "https://ghcr.io",
  cloudsmith.swai.top "https://docker.cloudsmith.io",
  ecr.swai.top https://public.ecr.aws
```