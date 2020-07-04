# CI/CD

Code change -> Push to GitHub -> Pipe line starts -> Build docker image -> Deploy to Kubernetes

- Cluster (a set of VMS called nodes)
  - Namespaces
    - Deployments
      - Pods

<!-- Load Balancers -->

            service
               |
               |
          ------------
          |     |     |
        Pod  Pod    Pod
