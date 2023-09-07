# Infrastructure as Code

Sometimes referred to as IaC, this section refers to the techniques and tools used to define infrastructure, typically in a markup language like YAML or JSON. Infrastructure as code allows DevOps Engineers to use the same workflows used by software developers to version, roll back, and otherwise manage changes.

The term Infrastructure as Code encompasses everything from bootstrapping to configuration to orchestration, and it is considered a best practice in the industry to manage all infrastructure as code. This technique precipitated the explosion in system complexity seen in modern DevOps organizations.

Infrastructure as Code (IaC) is the managing and provisioning of infrastructure through code instead of through manual processes.

With IaC, configuration files are created that contain your infrastructure specifications, which makes it easier to edit and distribute configurations. It also ensures that you provision the same environment every time. By codifying and documenting your configuration specifications, IaC aids [configuration management](https://www.redhat.com/en/topics/automation/what-is-configuration-management) and helps you to avoid undocumented, ad-hoc configuration changes.

Version control is an important part of IaC, and your configuration files should be under source control just like any other software source code file. Deploying your infrastructure as code also means that you can divide your [infrastructure](https://www.ansible.com/use-cases/infrastructure) into modular components that can then be combined in different ways through automation.

Automating [infrastructure provisioning](https://www.redhat.com/en/topics/automation/what-is-provisioning) with IaC means that developers don’t need to manually provision and manage servers, operating systems, storage, and other infrastructure components each time they develop or deploy an application. Codifying your infrastructure gives you a template to follow for provisioning, and although this can still be accomplished manually, an automation tool, such as [Red Hat® Ansible® Automation Platform](https://www.redhat.com/en/technologies/management/ansible), can do it for you.&#x20;

### Declarative vs. imperative approaches to IaC <a href="#declarative-vs-imperative-approach" id="declarative-vs-imperative-approach"></a>

There are 2 ways to approach IaC: declarative or imperative.&#x20;

A declarative approach defines the desired state of the system, including what resources you need and any properties they should have, and an IaC tool will configure it for you.&#x20;

A declarative approach also keeps a list of the current state of your system objects, which makes taking down the infrastructure simpler to manage.

An imperative approach instead defines the specific commands needed to achieve the desired configuration, and those commands then need to be executed in the correct order.&#x20;

Many IaC tools use a declarative approach and will automatically provision the desired infrastructure. If you make changes to the desired state, a declarative IaC tool will apply those changes for you. An imperative tool will require you to figure out how those changes should be applied.

IaC tools are often able to operate in both approaches, but tend to prefer one approach over the other.

### Benefits of IaC <a href="#benefits-of-iac" id="benefits-of-iac"></a>

Provisioning infrastructure has historically been a time consuming and costly manual process. Now infrastructure management has moved away from physical hardware in data centers, though this still may be a component for your organization, to [virtualization](https://www.redhat.com/en/topics/virtualization/what-is-virtualization), [containers](https://www.redhat.com/en/topics/containers/whats-a-linux-container), and [cloud computing](https://www.redhat.com/en/topics/cloud).&#x20;

With cloud computing, the number of infrastructure components has grown, more applications are being released to production on a daily basis, and infrastructure needs to be able to be spun up, scaled, and taken down frequently. Without an IaC practice in place, it becomes increasingly difficult to manage the scale of today’s infrastructure.

IaC can help your organization manage IT infrastructure needs while also improving consistency and reducing errors and manual configuration.

**Benefits:**

* Cost reduction
* Increase in speed of deployments
* Reduce errors&#x20;
* Improve infrastructure consistency
* Eliminate configuration drift

### IaC tools <a href="#iac-tools" id="iac-tools"></a>

Server automation and configuration management tools can often be used to achieve IaC. There are also solutions specifically for IaC.&#x20;

**These are a few popular choices:**

* Chef
* Puppet
* Red Hat Ansible Automation Platform
* Saltstack
* [Terraform](https://www.redhat.com/en/topics/automation/ansible-vs-terraform)&#x20;
* AWS CloudFormation

Ansible Automation Platform can be used to provision operating systems and network devices, deploy applications, and manage configuration.

### Why does IaC matter for DevOps? <a href="#iac-for-devops" id="iac-for-devops"></a>

IaC is an important part of implementing [DevOps](https://www.redhat.com/en/topics/devops) practices and [continuous integration/continuous delivery](https://www.redhat.com/en/topics/devops/what-is-ci-cd) (CI/CD). IaC takes away the majority of provisioning work from developers, who can execute a script to have their infrastructure ready to go. &#x20;

That way, application deployments aren’t held up waiting for the infrastructure, and sysadmins aren’t managing time-consuming manual processes.&#x20;

CI/CD relies on ongoing [automation](https://www.redhat.com/en/topics/automation) and continuous monitoring throughout the [application life cycle](https://www.redhat.com/en/topics/devops/what-is-application-lifecycle-management-alm), from integration and testing to delivery and deployment.&#x20;

In order for an environment to be automated it needs to be consistent. [Automating application deployments ](https://www.redhat.com/en/topics/automation/what-is-deployment-automation)doesn’t work when the development team deploys applications or configures environments one way and the operations teams deploys and configures another way.

Aligning development and operations teams through a DevOps approach leads to fewer errors, manual deployments, and inconsistencies.&#x20;

IaC helps you to align development and operations because both teams can use the same description of the application deployment, supporting a DevOps approach.

The same deployment process should be used for every environment, including your production environment. IaC generates the same environment every time it is used.

IaC also removes the need to maintain individual deployment environments with unique configurations that can’t be reproduced automatically and ensures that the production environment will be consistent.

DevOps best practices are also applied to infrastructure in IaC. Infrastructure can go through the same CI/CD pipeline as an application does during software development, applying the same testing and version control to the infrastructure code.

### Free Content

[WatchWhat is Infrastructure as Code?](https://www.youtube.com/watch?v=zWw2wuiKd5o)

[WatchWhat is Infrastructure as Code? Difference of Infrastructure as Code Tools](https://www.youtube.com/watch?v=POPP2WTJ8es)

[WatchVideo introduction to infrastructure as code](https://www.youtube.com/watch?v=zWw2wuiKd5o)

[ReadGUIs, CLI, APIs: Learn Basic Terms of Infrastructure-as-Code](https://thenewstack.io/guis-cli-apis-learn-basic-terms-of-infrastructure-as-code/)

[ReadWhat is infrastructure as code](https://roadmap.sh/\(https://www.redhat.com/en/topics/automation/what-is-infrastructure-as-code-iac)
