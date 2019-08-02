# Alibaba

- Alibaba is an active user of the Tekton project. The use case goes beyond CI/CD framework.
- In Alibaba, thousands of "middleware" services are being used to support worldscale e-commerce and cloud business.
- All of these services are stateful apps, which is supposed be "nightmare" to manage, managed effortlessly by Operators + CRD.
- Alibaba now uses Tekton to continuously deliver these services across hybrid clouds.
- We implemented Canary Analysis + Progressive Deployment based on Tekton, deliver with strategy and confidence.
- We are dedicated to encouraging using Tekton across teams in a broader world, including testing and SRE teams.
- Not so surprisingly, our SRE team uses Tekton to deploy kubelet, containerd, etc. to the 10k+ nodes cluster in Alibaba.
