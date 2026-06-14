# kubectl get human/yuxiao -o yaml

```yaml
apiVersion: humans/v1
kind: Human

metadata:
  name: Yuxiao Wang
  alias: Sayaka-4987
  region: westus
  namespace: production
  deletionGracePeriodSeconds: unpredictable

spec:
  focus:
    - distributed systems
    - reliability
    - failure modes

  stack:
    - C#
    - .NET
    - Kubernetes
    - Istio
    - Helm
    - Azure DevOps

  interests:
    - ACGN
    - games
    - board games
    - outdoors
    - fitness

  probes:
    readiness:
      requires:
        - caffeine
    liveness:
      requires:
        - sleep

  restartPolicy: Always

status:
  phase: Running
  lastUpdated: continually

  endpoints:
    blog: https://sayaka-4987.github.io/
    linkedin: https://www.linkedin.com/in/yuxiao-wang-042460245/
```
