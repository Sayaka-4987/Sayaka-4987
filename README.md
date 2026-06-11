# kubectl get human/yuxiao -o yaml

```yaml
apiVersion: humans/v1
kind: Human

metadata:
  name: "Yuxiao Wang"
  aliases:
    - "Sayaka-4987"
  deletionGracePeriodSeconds: unpredictable

spec:
  org: Microsoft Azure OpenAI
  role: Software Engineer
  pronouns: she/her

  restartPolicy: Always

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

status:
  phase: Running
  lastUpdated: continually

endpoints:
  blog: https://sayaka-4987.github.io/
  linkedin: https://www.linkedin.com/in/yuxiao-wang-042460245/
```
