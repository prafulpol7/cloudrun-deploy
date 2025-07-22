# cloudrun-deploy — Cloud Run Hello World Sample

This sample shows how to deploy a Hello World application to Cloud Run.

For more details on how to work with this sample read the [Google Cloud Run Node.js Samples](https://github.com/GoogleCloudPlatform/nodejs-docs-samples).

## Local Development

### `npm run e2e-test`

```sh
export SERVICE_NAME=helloworld
export CONTAINER_IMAGE=gcr.io/${GOOGLE_CLOUD_PROJECT}/helloworld
npm run e2e-test

