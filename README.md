# external-prometheus-k8s-config
Additional configuration for https://github.com/sbelectronics/octoprint-prometheus or any other scrapable prometheus endpoint if your k8s environment is deployed with the stock manifests from https://github.com/carlosedp/cluster-monitoring

## Use

Modify the subsets configuration to include ips and ports of external prometheus endpoints you want to monitor

kubectl apply -f prometheus-external-servicemonitor.yaml
