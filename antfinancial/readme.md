# AntFinancial

- Ant Financial is an active user of the Tekton project. As of now, we use Tekton to run tens of thousands different pipelineRun every day.
- We are building a cloud native BUILD/CI system based on Tekton.
- We build a grpc service to manage the lifecycle of BUILD/CI objects such as pipelineRun instances, pod logs and etc. 
- We build and deploy a group of agents to pull those BUILD/CI objects and submit them to Tekton for execution and record their corresponding status.