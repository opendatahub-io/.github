## Welcome to Open Data Hub :wave:

Welcome to Open Data Hub (ODH), an exciting open source project that provides AI tools for running large and distributed AI workloads on the OpenShift Container Platform. Our mission is to empower users with powerful and accessible AI and Machine Learning (ML) capabilities. Whether you're a data scientist, a data analyst, or an application developer, ODH has something for you.

### What's Included in Open Data Hub

The Open Data Hub core deployment consists of several open source components that can be individually enabled based on your needs. Here are some of the key components:

- **Jupyter Notebooks:** *A powerful development environment for interactive and collaborative data science.*
- **ODH Dashboard:** *A convenient dashboard that provides an overview of installed components, available installations, and links to component UIs and documentation.*
- **Data Science Pipelines Operator:** *A tool for building and orchestrating end-to-end data science workflows.*
- **Model Mesh Serving:** *A distributed model serving framework for managing and routing machine learning models.*

For more detailed information about our architecture and recent updates, please refer to our [architecture](https://opendatahub.io/docs/architecture.html) and [release notes](https://opendatahub.io/docs/roadmap/release-notes.html).

<p align="center">
  <img width="60%" src="https://opendatahub.io/assets/img/pages/arch/figure-1.png">
</p>


### Special Interest Groups and Working Groups

To foster transparent decision making and innovation, Open Data Hub has adopted an organization and governance model. We are organized into Special Interest Groups (SIG) and Working Groups (WG). Here's an overview of our current structure:

|                | SIG Platform                                              | SIG ML Dev Experience                                        | SIG ML Ops                                                                                                  |
| -------------- | --------------------------------------------------------- | ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------- |
| *Scope*          | ODH operator, odh-core components, ecosystem integration, authentication, and monitoring   | End-to-end experience for data scientists, analysts, and developers | Services and APIs for ML Ops capabilities in Open Data Hub                                                   |
| *Chairs*         | Taneem Ibrahim,<br>Landon LaSmith,<br>Vaishinavi Hire,<br>Gabe Goodheart | Jay Koehler,<br>Kyle Walker,<br>Erwan Granger,<br>Romeo Kienzler       | Prasanth Anbalagan,<br>Anish Asthana,<br>Nick Hill,<br>Giulio Frasca                                                   |
| *Working Groups* | #wg-custom-notebook-images,<br>#wg-distributed-workloads,<br>#wg-notebook-controller,<br>#wg-odh-rearchitecture,<br>#wg-on-prem | #wg-opendatahubio-website,<br>#wg-ux-ui-end-to-end-design,<br>#wg-workbench-images | #wg-ai-explainability,<br>#wg-model-serving,<br>#wg-pipelines                                                        |
| *Repositories*   | [opendatahub-operator](https://github.com/opendatahub-io/opendatahub-operator),<br>[odh-manifests](https://github.com/opendatahub-io/odh-manifests) | [sig-ml-developer-experience](https://github.com/opendatahub-io/sig-ml-developer-experience),<br>[odh-dashboard](https://github.com/opendatahub-io/odh-dashboard),<br>[notebooks](https://github.com/opendatahub-io/notebooks) | [modelmesh-serving](https://github.com/opendatahub-io/modelmesh-serving),<br>[odh-model-controller](https://github.com/opendatahub-io/odh-model-controller),<br>[rest-proxy](https://github.com/opendatahub-io/rest-proxy),<br>[modelmesh](https://github.com/opendatahub-io/modelmesh),<br>[modelmesh-runtime-adapter](https://github.com/opendatahub-io/modelmesh-runtime-adapter),<br>[data-science-pipelines-operator](https://github.com/opendatahub-io/data-science-pipelines-operator),<br>[data-science-pipelines](https://github.com/opendatahub-io/data-science-pipelines) |

For more detailed information about our organization, governance, and the work being done in each SIG and WG, please check out our [Governance](https://github.com/opendatahub-io/opendatahub-community/blob/main/governance.md) section and explore the individual SIG/WG links.

---

## Important Links

Here are some important links to get you started and engaged with the Open Data Hub community:

- **Contribution Guidelines**: Learn how to contribute to the project and become an active member of our community by reading our [contribution guidelines](https://github.com/opendatahub-io/opendatahub-community/blob/master/contributing.md).
- **Roadmap**: Discover our future plans and upcoming features by exploring our [roadmap](https://opendatahub.io/docs/roadmap/future.html).
- **Getting Started**: Get started quickly with Open Data Hub by following our [quick installation guide](https://opendatahub.io/docs/getting-started/quick-installation.html).

### Repositories

Explore our repositories to access various components, utilities, tests, templates, and more:

**Core**:
- [opendatahub-operator](https://github.com/opendatahub-io/opendatahub-operator): Deploy, monitor, and manage the lifecycle of Kubeflow using the Operator Framework.
- [odh-dashboard](https://github.com/opendatahub-io/odh-dashboard): A dashboard for Open Data Hub components, providing easy access to UIs and documentation.
- [odh-manifests](https://github.com/opendatahub-io/odh-manifests): Kustomize manifests for Open Data Hub components.
- [odh-notebook-controller](https://github.com/opendatahub-io/kubeflow/tree/master/components/odh-notebook-controller): Code for the Open Data Hub notebook controller with OAuth authentication support.
- [data-science-pipelines](https://github.com/opendatahub-io/data-science-pipelines): Integration of Kubeflow Pipelines with Tekton for end-to-end data science workflows.
- [modelmesh](https://github.com/opendatahub-io/modelmesh) and related repositories: Distributed Model Serving Framework.

**Utilities**:
- [odh-s2i-project-cookiecutter](https://github.com/opendatahub-io/odh-s2i-project-cookiecutter): Standardized project structure for data science work.
- [notebooks](https://github.com/opendatahub-io/notebooks): Images for use with the ODH Notebook Controller.
- [s2i-lab-elyra](https://github.com/opendatahub-io/s2i-lab-elyra): JupyterLab with Elyra enabled for JupyterHub deployments.
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
