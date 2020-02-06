# external-prometheus-k8s-service-monitors
Additional configuration for https://github.com/sbelectronics/octoprint-prometheus or any other scrapable prometheus endpoint to be monitored by a k8s cluster deployed with the stock manifests from https://github.com/carlosedp/cluster-monitoring

## Use

Modify the subsets configuration to include ips and ports of external prometheus endpoints you want to monitor

kubectl apply -f prometheus-external-servicemonitor.yaml
