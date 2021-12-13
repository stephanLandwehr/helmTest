# Helm chart for example go openshift app

## how to start it:

1. helm template go-test-buildConfig helm-buildConfig --output-dir deploy-helm-buildConfig
2. It might be nessecary to delete the first two lines of all created files
3. oc apply -f deployHelmBuildConfig/go-test-buildConfig/templates
