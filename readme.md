Enable the Cloud Build, Cloud Run, Container Registry, and Resource Manager APIs.
also enable https://cloud.google.com/build/docs/deploying-builds/deploy-appengine

gcloud app create --> call this to create app engine
gcloud builds submit --config build.yaml --> call this to trigger build

key files
 build.yaml --> all the build step
 pom.xml --> has the plugin to copy from angular dist folder



