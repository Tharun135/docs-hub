# Kubernetes Intro
Pods, Deployments, Services, ConfigMaps/Secrets.
```yaml
apiVersion: apps/v1
kind: Deployment
metadata: { name: web }
spec:
  replicas: 2
  selector: { matchLabels: { app: web } }
  template:
    metadata: { labels: { app: web } }
    spec:
      containers:
      - name: web
        image: nginx:1.27
        ports: [{ containerPort: 80 }]
```
