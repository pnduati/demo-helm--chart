Simple Helm Chart
This helm chart deploys nginx with Pod disruption budget, horizontal pod autoscaler and pod security policy enabled also injecting environment variables into the container runtime.

How To Install

1. Clone the repo - https://github.com/pnduati/demo-helm--chart
2. helm install chart --name demo-helm ./demo-helm-chart
