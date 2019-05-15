# Deploying to GCR

Read First: [https://cloud.google.com/container-registry/docs/pushing-and-pulling][1]

`docker build -f Dockerfile.{name} -t gcr.io/{project}/{name} .`

`docker push gcr.io/{project}/{name}`

[1]: https://cloud.google.com/container-registry/docs/pushing-and-pulling