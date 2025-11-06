# Why Is CI still Doing Your Promotions? 

Date and Time: 2025-11-08 10:10–10:40

As teams move from traditional CI/CD pipelines to GitOps tools like Argo CD, they often hit a common roadblock: how do you manage promotions across dev, staging, and production? Tools like Argo CD and Flux often leave a gap when it comes to multi-stage promotions. What used to be a simple approval click now involves juggling image tags, config changes, and pull requests across multiple repos. This shift often creates confusion, adds manual steps, and breaks the developer workflow.

Tools like 'GitOps Promoter' by Argo offer a promising approach to this problem, but are still in their experimental phase, limiting their readiness for production. Other enterprise solutions offer robust features but come with licensing costs, which can be a barrier for teams.

In this talk, we’ll explore Kargo, a Kubernetes-native OSS tool for automating multi-stage promotions, and compare it with GitOps Promoter. We’ll walk through their design choices, strengths, and tradeoffs with a live demo so users can see how each tool handles this and choose the approach that best fits their GitOps workflow, without ever relying on custom scripts.
