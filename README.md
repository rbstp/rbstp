```yaml
apiVersion: v1
kind: Developer
metadata:
  name: rbstp
  labels:
    environment: production
    role: devops-engineer
spec:
  containers:
  - name: daily-work
    image: devops/engineer:latest
    ports:
    - containerPort: 22
    - containerPort: 443
    env:
    - name: MINDSET
      value: "automate-everything"
    - name: COFFEE_LEVEL
      value: "critical"
```
