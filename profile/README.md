## Welcome to Open Data Hub :wave:

Open Data Hub (ODH) is an open source project that provides open source AI tools for running large and distributed AI workloads on the OpenShift Container Platform. Currently, the Open Data Hub project provides open source tools for distributed AI and Machine Learning (ML) workflows, Jupyter Notebook development environment and monitoring. The Open Data Hub project roadmap offers a view on new tools and integration the project developers are planning to add.  

Included in the Open Data Hub core deployment are several open source components, which can be individually enabled. They include:

- Jupyter Notebooks
- ODH Dashboard
- Data Science Pipelines Operator
- Model Mesh Serving

For further information refer to the [architecture](https://opendatahub.io/docs/architecture.html) and [release notes](https://opendatahub.io/docs/roadmap/release-notes.html).

### Special Interest Groups and Working Groups

**Open Data Hub (ODH)** adopted an organization and governance model to foster transparent decision making and innovation. The project is organized into Special Interest Groups (SIG) and Working Groups (WG). The table below offers an overview of the current structure. For more information, read the [Governance](https://github.com/opendatahub-io/opendatahub-community/blob/main/governance.md) section, or the individual SIG/WG links:

|     | Name                                                                                                                  | Chairs                                                                        | Scope                                                                                              | Repositories                                                                                                                                                                                                                                                                                                                                                                                     |
| --- | --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| SIG | [ML Dev Experience](https://github.com/opendatahub-io/opendatahub-community/tree/main/sig-ml-developer-experience)    | - Jay Koehler<br>- Kyle Walker<br>- Erwan Granger<br>- Romeo Kienzler         | End-to-end experience for a data scientist, a data analyst or an application developer             | [sig-ml-developer-experience](https://github.com/opendatahub-io/sig-ml-developer-experience)<br>[odh-dashboard](https://github.com/opendatahub-io/odh-dashboard)<br> [notebooks](https://github.com/opendatahub-io/notebooks) |
| SIG | [ML Ops](https://github.com/opendatahub-io/opendatahub-community/tree/main/sig-ml-ops)                                | - Prasanth Anbalagan<br>- Anish Asthana<br>- Nick Hill<br>- Giulio Frasca     | Services and APIs responsible for providing ML Ops capabilities to users of the Open Data Hub      | [modelmesh-serving](https://github.com/opendatahub-io/modelmesh-serving)<br>[odh-model-controller](https://github.com/opendatahub-io/odh-model-controller)<br>[rest-proxy](https://github.com/opendatahub-io/rest-proxy)<br>[modelmesh](https://github.com/opendatahub-io/modelmesh)<br>[modelmesh-runtime-adapter](https://github.com/opendatahub-io/modelmesh-runtime-adapter)<br>[data-science-pipelines-operator](https://github.com/opendatahub-io/data-science-pipelines-operator)<br>[data-science-pipelines](https://github.com/opendatahub-io/data-science-pipelines) |
| SIG | [Platform](https://github.com/opendatahub-io/opendatahub-community/tree/main/sig-platform)                            | - Taneem Ibrahim<br>- Landon LaSmith<br>- Vaishinavi Hire<br>- Gabe Goodheart | ODH operator, odh-core components, ecosystem integration, authentication, and monitoring           | [opendatahub-operator](https://github.com/opendatahub-io/opendatahub-operator)<br>[odh-manifests](https://github.com/opendatahub-io/odh-manifests) |
| WG  | [Distributed Workloads](https://github.com/opendatahub-io/opendatahub-community/tree/main/wg-distributed-workloads)   | - Anish Asthana<br>- Michael Clifford<br>- Mustafa Eyceoz                     | Easy and user-friendly access to distributed workloads and workload orchestration on Open Data Hub | [distributed-workloads](https://github.com/opendatahub-io/distributed-workloads) |
| WG  | [On-prem](https://github.com/opendatahub-io/opendatahub-community/tree/main/wg-on-prem)                               | - Landon LaSmith<br>- JooHo Lee<br>- Vaishnavi Hire                           | Guidance for on premises deployments of Open Data Hub                                              |      |
| WG  | [Explainable AI](https://github.com/opendatahub-io/opendatahub-community/tree/main/wg-xai)                            | - Rebecca Whitworth<br>- Tommaso Teofili<br>- Rui Vieira<br>- Rob Geada       | Explainability framework for ODH developers                                                        | [trustyai-explainability](https://github.com/trustyai-explainability/trustyai-explainability)    |

##
---
## Important Links

**Contribution Guidelines**:
[https://github.com/opendatahub-io/opendatahub-community/blob/master/contributing.md](https://github.com/opendatahub-io/opendatahub-community/blob/master/contributing.md)

**Roadmap**:
[https://opendatahub.io/docs/roadmap/future.html](https://opendatahub.io/docs/roadmap/future.html)

**Getting Started**:
[https://opendatahub.io/docs/getting-started/quick-installation.html](https://opendatahub.io/docs/getting-started/quick-installation.html)

##

### Repositories

**Core**
- [opendatahub-operator](https://github.com/opendatahub-io/opendatahub-operator): A repository that helps to deploy, monitor and manage the lifecycle of Kubeflow. Built using the Operator Framework which offers an open source toolkit to build, test, package operators and manage the lifecycle of operators.
- [odh-dashboard](https://github.com/opendatahub-io/odh-dashboard): A dashboard for Open Data Hub components. Shows what's installed and what's available for installation, as well as, links to component UIs and links to component documentation.
- [odh-manifests](https://github.com/opendatahub-io/odh-manifests): A repository for Open Data Hub components Kustomize manifests.
- [odh-notebook-controller](https://github.com/opendatahub-io/kubeflow/tree/master/components/odh-notebook-controller): This repository contains the code for the Open Data Hub notebook controller with support for OAuth authentication.
- [data-science-pipelines](https://github.com/opendatahub-io/data-science-pipelines): Project bringing Kubeflow Pipelines and Tekton together. The current code allows you run Kubeflow Pipelines with Tekton backend end to end.
- [modelmesh](https://github.com/opendatahub-io/modelmesh): Distributed Model Serving Framework.
  - [modelmesh-runtime-adapter](https://github.com/opendatahub-io/modelmesh-runtime-adapter): Unified runtime-adapter image of the sidecar containers which run in the modelmesh pods
  - [rest-proxy](https://github.com/opendatahub-io/rest-proxy): KServe V2 Protocol Rest API Implementation Proxy.
  - [modelmesh-serving](https://github.com/opendatahub-io/modelmesh-serving): The Controller for managing ModelMesh, a general-purpose model serving management/routing layer.

**Utilities**
- [odh-s2i-project-cookiecutter](https://github.com/opendatahub-io/odh-s2i-project-cookiecutter):  A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.
- [notebooks](https://github.com/opendatahub-io/notebooks): These images were created to be used with Open Data Hub (ODH) using the ODH Notebook Controller as the launcher.
- [s2i-lab-elyra](https://github.com/opendatahub-io/s2i-lab-elyra): JupyterHub enabled image deploying JupyterLab with Elyra.
- [odh-images](https://github.com/opendatahub-io/odh-images):Source files for building container images that have been customized for Open Data Hub deployment.
- [manifests](https://github.com/opendatahub-io/manifests): A repository for Kustomize manifests.

**Test**
- [openshift-test-kit](https://github.com/opendatahub-io/openshift-test-kit): Repos for helper module used with the Peak test framework.
- [peak](https://github.com/opendatahub-io/peak): This test runner is based on the radanalyticsio openshift-test-kit repository.

**Templates**
- [odh-template-sig](https://github.com/opendatahub-io/odh-template-sig): Repository template for Open Data Hub Special Interest Groups.
- [odh-s2i-project-simple](https://github.com/opendatahub-io/odh-s2i-project-simple): Simple, unstructured, and unopinionated project for data science that is deployable as an OpenShift s2i Application.
- [odh-s2i-project-cds](https://github.com/opendatahub-io/odh-s2i-project-cds): A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.

**Contribution**
- [opendatahub-community](https://github.com/opendatahub-io/opendatahub-community): This is the starting point for joining and contributing to the Open Data Hub community.

**Other**
- [opendatahub.io](https://github.com/opendatahub-io/opendatahub.io): Contains webpage source code for [https://opendatahub.io](https://opendatahub.io)
- [architecture-decision-records](https://github.com/opendatahub-io/architecture-decision-records): Documentation of architectural decisions used to help current and future contributors to understand the reasons for doing things a certain way.
- [sig-ml-developer-experience](https://github.com/opendatahub-io/sig-ml-developer-experience): Open Data Hub Special Interest Groups.
- [opendatahub.io-redirects](https://github.com/opendatahub-io/opendatahub.io-redirects): Example Jekyll website using GitLab Pages.
- [odh-landscape](https://github.com/opendatahub-io/odh-landscape): Interactive map of ODH services.
- [landscapeapp](https://github.com/opendatahub-io/landscapeapp): Landscape generation application.

**Archived**
- data-engineering-and-machine-learning-workshop
- Fraud-Detection-with-Business-Workflows-Tutorial
- odh-model-controller
