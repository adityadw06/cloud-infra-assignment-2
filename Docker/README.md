# cloud-infra-assignment-2

# Docker-Hub URL: 
https://hub.docker.com/r/adityadw/hellopython


# GCP Docker URL & Details
https://console.cloud.google.com/logs/query;query=resource.type%3D%22cloud_run_revision%22%0Aresource.labels.service_name%3D%22hellopython%22%0Aresource.labels.revision_name%3D%22hellopython-00002-dek%22;cursorTimestamp=2021-09-30T17:53:14.595156507Z?project=genuine-grid-327615

resource.type="cloud_run_revision"
resource.labels.service_name="hellopython"
resource.labels.revision_name="hellopython-00002-dek"

# GCP Kubernetes Engine URL
https://console.cloud.google.com/kubernetes/service/us-central1-a/adityadwkubernetescluste/default/nginx-1-service/logs?project=genuine-grid-327615


Reference: https://stackoverflow.com/questions/66920645/exec-format-error-when-running-containers-build-with-apple-m1-chip-arm-based
(to build docker image from m1 mac)