# SERVERLESS

A harmless exploration into the world of serverless functions and distributed computing. The overarching goal of this project is to practice configuring and deploying OpenFaas to kubernetes clusters hosted with DO. One tangible objective is to deploy a **CRUD API** out of *serverless functions*. 

## Resources:

### 1. Kubernetes: 
1. [Kubernetes Quickstart](https://www.digitalocean.com/docs/kubernetes/quickstart/)

2. [How To Run Serverless Functions Using OpenFaaS on DigitalOcean Kubernetes](https://www.digitalocean.com/community/tutorials/how-to-run-serverless-functions-using-openfaas-on-digitalocean-kubernetes)

3. [Building a Kubernetes cluster on DigitalOcean to host websites and backend services](http://agilesnowball.com/2019/05/30/kubernetes-on-digitalocean.html)

4. [GitHub Repo for ingress-nginix](https://github.com/kubernetes/ingress-nginx/tree/master/charts/ingress-nginx)

5. [How To Set Up an Nginx Ingress on DigitalOcean Kubernetes Using Helm](https://www.digitalocean.com/community/tutorials/how-to-set-up-an-nginx-ingress-on-digitalocean-kubernetes-using-helm)

6. [Deprecated Kubernetes APIs](https://kubernetes.io/blog/2019/07/18/api-deprecations-in-1-16/)

## Local Requirements:

- Kubernetes API: On macOS, install using homebrew from the command line: `brew install kubectl`.




------


## Next-steps:

- remove one-click install versions of NGINX Ingress controller (currently DO is showing two??).
- properly install NGINX ingress conroller using helm, and point A NAME resources towards appropriate cluster nodes.

