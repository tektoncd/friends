# Alibaba

- Alibaba is a heavy user of the Tekton project, but not only for CI/CD framework.
- In Alibaba, there are tons of "middleware" services which are used to serve this company's E-business.
- All of these services are stateful apps and managed by CRD + Controller, basically "nightmare" for deploy.
- Alibaba now use Tekton to deliver these services across multiple clouds, automatically and seamlessly.
- We implemented Canary Analysis + Progressive Deployment based on Tekton, deliver with strategy and confidence.
- We are committed to encourage the use of Tekton in Alibaba for more use cases, including CI/CD framework and SRE.
- Yes, now our SRE team use Tekton to deploy kubelet, containerd etc to the 10000 nodes cluster in Alibaba.