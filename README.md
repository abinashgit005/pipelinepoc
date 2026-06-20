# pipelinepoc
build-to-deploy

Push and pull images : [reference link](https://docs.cloud.google.com/artifact-registry/docs/docker/pushing-and-pulling)

```bash
gcloud auth configure-docker us-west1-docker.pkg.dev
```

```text
**LOCATION** is the regional or multi-regional location of the repository where the image is stored.

**PROJECT-ID** is your Google Cloud console project ID. If your project ID contains a colon (:), see Domain-scoped projects.

**REPOSITORY** is the name of the repository where the image is stored.

**IMAGE** is the image's name. It can be different than the image's local name.
```