# Kubernetes with Artifactory challenge
This repository hold the details for the JFrog Kubernetes with Artifactory challenge

## The challenge
You are challenged to setup the following
1. Get trial for [Artifactory cloud](https://jfrog.com/artifactory/free-trial/)
2. Configure [Artifactory as your helm repository](https://www.jfrog.com/confluence/display/RTF/Helm+Chart+Repositories) (local, remote and virtual repositories are needed)
3. Deploy the public [wordpress helm chart](https://hub.helm.sh/charts/stable/wordpress) using Artifactory as the helm repository (the remote will pull the official chart)
   
## Extra credit
1. Setup a simple web page application (use static html or any other technology you want)
2. Package the web application into a Docker image
3. Setup [Artifactory as your Docker registry](https://www.jfrog.com/confluence/display/RTF/Docker+Registry)
4. Push Docker image to Artifactory
5. Create a simple [Helm Chart](https://docs.bitnami.com/kubernetes/how-to/create-your-first-helm-chart/) that deploys your Docker image to Kubernetes
6. Build and push Helm chart to Artifactory
7. Deploy your web page application to Kubernetes using Helm
