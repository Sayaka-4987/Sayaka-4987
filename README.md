# kubectl get human yuxiao -o yaml

```yaml
apiVersion: humans/v1
kind: Human
metadata:
  name: "Yuxiao Wang"
  aliases:
    - "Sayaka-4987"

spec:
  role: Software Engineer
  org: Microsoft Azure OpenAI
  pronouns: she/her

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
    - Azure

  interests:
    - ACGN
    - games
    - board games
    - outdoors
    - fitness

status:
  phase: Running
  conditions:
    - type: ProductionExposure
      # Frequent incidents
      status: "True"
    - type: Stability
      # Works under normal conditions
      status: "MostlyStable" 

  lastUpdated: continually

endpoints:
  blog: https://sayaka-4987.github.io/
  linkedin: https://www.linkedin.com/in/yuxiao-wang-042460245/
```
