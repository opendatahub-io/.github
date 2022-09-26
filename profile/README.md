### Welcome to Open Data Hub
Open Data Hub (ODH) is an open source project based on Kubeflow that provides open source AI tools for running large and distributed AI workloads on OpenShift Container Platform. Currently, the Open Data Hub project provides open source tools for data storage, distributed AI and Machine Learning (ML) workflows, Jupyter Notebook development environment and monitoring.

#### Benefits of Open Data Hub

ODH is a meta-project that integrates open source projects into a practical solution. It aims to foster collaboration between communities, vendors, user-enterprises, and academics following open source best practices. The open source community can experiment and develop intelligent applications without incurring high costs and having to master the complexity of modern machine learning and artificial intelligence software stacks.

**Contribution Guidelines**:
[https://github.com/opendatahub-io/opendatahub-community/blob/master/contributing.md](https://github.com/opendatahub-io/opendatahub-community/blob/master/contributing.md)

**Release notes**:
[https://opendatahub.io/docs/roadmap/release-notes.html](https://opendatahub.io/docs/roadmap/release-notes.html)

**Roadmap**:
[https://opendatahub.io/docs/roadmap/future.html](https://opendatahub.io/docs/roadmap/future.html)

**Getting Started**:
[https://opendatahub.io/docs/getting-started/quick-installation.html](https://opendatahub.io/docs/getting-started/quick-installation.html)

##

### Repositories

- **Core Repositories**
  * [odh-manifests](https://github.com/opendatahub-io/odh-manifests): A repository for Open Data Hub components Kustomize manifests.
  * [opendatahub-operator](https://github.com/opendatahub-io/opendatahub-operator): A repository that helps to deploy, monitor and manage the lifecycle of Kubeflow. Built using the Operator Framework which offers an open source toolkit to build, test, package operators and manage the lifecycle of operators.
  * [odh-dashboard](https://github.com/opendatahub-io/odh-dashboard): A dashboard for Open Data Hub components. Shows what's installed and what's available for installation, as well as, links to component UIs and links to component documentation.
  * [odh-notebook-controller](https://github.com/opendatahub-io/kubeflow/tree/master/components/odh-notebook-controller): This repository contains the code for the Open Data Hub notebook controller with support for OAuth authentication
  * [ml-pipelines](https://github.com/opendatahub-io/data-science-pipelines): Project bringing Kubeflow Pipelines and Tekton together. The current code allows you run Kubeflow Pipelines with Tekton backend end to end.
  * [ModelMesh Serving](https://github.com/opendatahub-io/modelmesh-serving): The Controller for managing ModelMesh, a general-purpose model serving management/routing layer.
  * [opendatahub.io](https://github.com/opendatahub-io/opendatahub.io): Contains the webpage source code for [https://opendatahub.io](https://opendatahub.io)
  * [opendatahub-community](https://github.com/opendatahub-io/opendatahub-community): This is the starting point for joining and contributing to the Open Data Hub community.

- **Tools**
  * Additional components and manifests contributed by ODH community members in our Open Data Hub Contrib organization [opendatahub-io-contrib](https://github.com/opendatahub-io-contrib)
  * [manifests](https://github.com/opendatahub-io/manifests): The Kubeflow Manifests repository is organized under three (3) main directories, which include manifests for installing: `apps`,  `common`, `contrib`


- **Utilities**
  * [s2i-lab-elyra](https://github.com/opendatahub-io/s2i-lab-elyra): This image contains Elyra and all the dependencies and configurations needed to run as a part of OpenDataHub's JupyterHub Environment.
  * [jupyterhub-odh](https://github.com/opendatahub-io/jupyterhub-odh): This repository contains an example of a customised deployment of JupyterHub for OpenShift, which uses the same OpenShift cluster as the deployment is running in, as the authentication provider.
  * [jupyterhub-singleuser-profiles](https://github.com/opendatahub-io/jupyterhub-singleuser-profiles): This library helps to manage and configure singleuser JupyterHub servers deployed by KubeSpawner.

- **Template Repositories**
  * [odh-template-sig](https://github.com/opendatahub-io/odh-template-sig) Repository template for Open Data Hub Special Interest Groups.

- **Backup Repos**
  * [landscapeapp](https://github.com/opendatahub-io/landscapeapp): The landscapeapp is an upstream NPM module that supports building interactive landscape websites such as the CNCF Cloud Native Landscape and the LF Artificial Intelligence Landscape.
