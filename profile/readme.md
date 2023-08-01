# CloudGeometry
[CloudGeometry](https://cloudgeometry.io/) is a hands-on, technical services consultancy and cloud platform integrator. We work with our clients to design, build, implement, and operate full stack cloud solutions. Our clients rely on us to address their business and platform infrastructure challenges. We deliver  on their business critical needs by combining components from open source cloud native technologies and cloud service provider offerings.

Each engagement is as unique as the business problems it targets. Because our expert teams work with these common components again and again, we can quickly assemble and adapt well-engineered toolchains and architectures that work well with your systems.

The solutions we develop for our clients are curated from the portfolio of open source projects[^oss_management]. cataloged here. Where appropriate, we publish the learnings from our engagements to give back to the open source communities from which they were drawn. This includes templates, code snippets, tools, and in many cases, contributions of fresh code to the Upstream open source project where they came from.


### Application Runtime
- [Kubernetes](https://github.com/kubernetes/kubernetes) Production-Grade Container Scheduling and Management.
- [Minikube](https://github.com/kubernetes/minikube) Run Kubernetes locally.
- [Istio](https://github.com/istio/istio) Connect, secure, control, and observe services. 
- [Envoy](https://github.com/envoyproxy/envoy) Cloud-native high-performance edge/middle/service proxy.


### CI/CD & GitOps

- [ArgoCD](https://github.com/argoproj/argo-cd) Declarative continuous deployment for Kubernetes. 
- [ArgoCD operator](https://github.com/argoproj-labs/argocd-operator) A Kubernetes operator for managing Argo CD clusters. 
- [ArgoCD Vault plugin](https://github.com/argoproj-labs/argocd-vault-plugin) An Argo CD plugin to retrieve secrets from Secret Management tools and inject them into Kubernetes secrets
- [Atlantis](https://github.com/runatlantis/atlantis) Terraform Pull Request Automation.


### Artifacts Management
- [Harbor](https://github.com/goharbor/harbor) An open source trusted cloud native registry project that stores, signs, and scans content.
- [Nexus](https://github.com/sonatype/nexus-public) Sonatype Nexus Repository Manager; Open-source codebase mirror.


### App Monitoring
- [Grafana](https://github.com/grafana/grafana) The open and composable observability and data visualization platform. 
- [Prometheus](https://github.com/prometheus/prometheus) The Prometheus monitoring system and time series database. 
- [Grafana dashboards Kubernetes](https://github.com/dotdc/grafana-dashboards-kubernetes) A set of modern Grafana dashboards for Kubernetes. 


### Log Aggregation
- [ElastAlert](https://github.com/Yelp/elastalert) Easy & Flexible Alerting With ElasticSearch.
- [Elastic](https://github.com/elastic/elasticsearch) Free and Open, Distributed, RESTful Search Engine.
- [Kibana](https://github.com/elastic/kibana) Your window into the Elastic Stack.
- [Logstash](https://github.com/elastic/logstash) Transport and process your logs, events, or other data.
- [Loki](https://github.com/grafana/loki) Like Prometheus, but for logs. 

### DevSecOps
- [Vault](https://github.com/hashicorp/vault) A tool for secrets management, encryption as a service, and privileged access management.
- [DriftCtl](https://github.com/snyk/driftctl) Detect, track and alert on infrastructure drift.
- [KubeBench](https://github.com/aquasecurity/kube-bench) Checks whether Kubernetes is deployed according to security best practices as defined in the CIS Kubernetes Benchmark.
- [Kyverno](https://github.com/kyverno/kyverno) Kubernetes Native Policy Management.
- [SonarQube](https://github.com/SonarSource/sonarqube) Continuous Inspection.
- [Paralus](https://github.com/paralus/paralus) All-in-one Kubernetes access manager.
- [Prowler](https://github.com/prowler-cloud/prowler) Security tool for AWS, Azure and GCP to perform Cloud Security best practices assessments
- [Tfsec](https://github.com/aquasecurity/tfsec) Security scanner for your Terraform code 
- [Trivy](https://github.com/aquasecurity/trivy) Find vulnerabilities, misconfigurations, secrets, SBOM in containers, Kubernetes, code repositories, clouds and more.
- [Trivy Operator](https://github.com/aquasecurity/trivy-operator) Kubernetes-native security toolkit.
- [Starboard exporter](https://github.com/giantswarm/starboard-exporter) A standalone exporter for vulnerability reports and other CRs created by Trivy Operator (formerly Starboard). 


### Cost Monitoring & Spend Optimization 
- [Cloud Intelligence Dashboard](https://github.com/aws-samples/aws-cudos-framework-deployment) Command Line Interface tool for Cloud Intelligence Dashboards deployment.
- [Opencost](https://github.com/opencost/opencost) Cross-cloud cost allocation models for Kubernetes workloads.
- [Resoto](https://github.com/someengineering/resoto) creates an inventory of your cloud, provides deep visibility, and reacts to changes in your infrastructure.
- [Terratag](https://github.com/env0/terratag) Terratag is a CLI tool that enables users of Terraform to automatically create and maintain tags across their entire set of AWS, Azure, and GCP resources.
- [CloudCustodian](https://github.com/cloud-custodian/cloud-custodian) Rules engine for cloud security, cost optimization, and governance, DSL in yaml for policies to query, filter, and take actions on resources.


### Modernization
- [Terraform](https://github.com/hashicorp/terraform) enables you to safely and predictably create, change, and improve infrastructure. 
- [Terragrunt](https://github.com/gruntwork-io/terragrunt) is a thin wrapper for Terraform that provides extra tools for working with multiple Terraform modules.
- [Terraform provider AWS](https://github.com/hashicorp/terraform-provider-aws) Terraform AWS provider.
- [Terraform provider Harbor](https://github.com/goharbor/terraform-provider-harbor) A Terraform provider for Harbor. 
- [CloudMapper](https://github.com/duo-labs/cloudmapper) helps you analyze your Amazon Web Services (AWS) environments.
- [EKS Cluster Upgrade](https://github.com/aws-samples/eks-cluster-upgrade) Automated Amazon EKS cluster upgrade.
- [EKS best practices](https://github.com/aws/aws-eks-best-practices) A best practices guide for day 2 operations, including operational excellence, security, reliability, performance efficiency, and cost optimization. 
- [Kong](https://github.com/Kong/kong) The Cloud-Native API Gateway.
- [KubeNT](https://github.com/doitintl/kube-no-trouble) Easily check your clusters for use of deprecated API.
- [Kustomize](https://github.com/kubernetes-sigs/kustomize) Customization of kubernetes YAML configurations.
- [Leverage](https://github.com/binbashar/leverage) CLI intended to orchestrate Leverage Reference Architecture for AWS.
- [Terraformer](https://github.com/GoogleCloudPlatform/terraformer) CLI tool to generate terraform files from existing infrastructure (reverse Terraform).

### Platform engineering
- [Kubefirst](https://github.com/kubefirst/kubefirst) The Kubefirst Open Source Platform . 
- [Kubefirst gitops template](https://github.com/kubefirst/gitops-template) A template of gitops infrastucture for consumption by kubefirst users. 
- [Otomi](https://github.com/redkubes/otomi-core) Self-hosted PaaS for Kubernetes.


[^oss_management]: [Our approach to OSS management](https://github.com/CloudGeometry/.github/blob/main/profile/oss_management.md)
