# IBM Bluemix Schematics Service On-boarding
An on-boarding kit for the IBM Bluemix Schematics service.

# Introduction
Modern cloud infrastructure ranges from bare metal servers, to virtual machines, to containers, to managed services, to SaaS, to PaaS, and beyond.  Many times that infrastructure spans multiple data centers, companies, products, and regions around the world. Modern infrastructure is cloud native and global scale.

IBM Cloud Schematics gives architects, developers, and operators the ability to define and manage their modern cloud infrastructure as a single unit, across any number of environments, in an automated and repeatable fashion. In traditional operations developers and operators provision infrastructure and services using multiple and fragmented components and tools in a manual and repetitive manner which severely limits reproducibility, transparency, and codification. This obscures the “how” and “why” of infrastructure choices and changes which limits usage, delays time to value, and impedes ecosystem expansion.

IBM Cloud Schematics uses HashiCorp's [Terraform](https://www.terraform.io/) under the hood. Schematic Modules and Configurations are written in [HashiCorp Configuration Language](https://www.terraform.io/docs/configuration/syntax.html).

IBM Cloud Schematics allows users to define their infrastructure in files that can be checked into source control, which enables versioning, commit messages that can reveal the reason behind a change, an audit trail to determine who changed what and when, and collaboration, review, and transparency when working on infrastructure as a team.

IBM Cloud Schematics gives IBM a way to offer infrastructure building blocks to its customers, as well as complete and prescriptive solutions. Customers can more quickly build solutions for the platform, understand how to build those solutions, and better grasp how the platform products and offerings can be put together to create solutions.

IBM Cloud Schematics further enables teams and companies to build up a library of componentry that can be reused again and again to net the same results.  From tiny building blocks to complete solutions. Need a hadoop cluster? There is a module to do that, just plug in your variables! This allows cross-team and cross-organization code reuse and ensures that the company is working to solve problems as a unit and solving them in the best way possible.

# Terminology
- IBM Cloud Schematics - The service overlay that enables teams to more easily and safely take advantage of Terraform with IBM Bluemix.
- [Infrastructure as code (IaC)](https://en.wikipedia.org/wiki/Infrastructure_as_Code) - which encapsulates all cloud resources. These can be any IaaS component such as baremetal servers, virtual machines, containers, load balancers, software defined networking components, etc; SaaS offerings such as watson services, message hub (message queue), etc; or PaaS offerings such as D(ata)B(ase)aaS, functions as a service (OpenWhisk), etc.
- [Terraform](https://www.terraform.io/) - The underlying IaC engine used by IBM Cloud Schematics.
- [Configurations](https://www.terraform.io/docs/configuration/index.html) - A collection of Terraform files which defines the infrastructure as code.
- [Modules](https://www.terraform.io/docs/modules/index.html) - A special reusable configuration that is often used as a building block that encapsulates a certain functionality. Used in both configurations and by other modules. A configuration or module can include _N_ modules.
- [Configuration Management](https://www.terraform.io/intro/vs/chef-puppet.html) - tools that install and manage software on any number of resources (baremetal and virtual servers, containers, etc)

# Early Access
Currently the service itself is not available (as of April 06 2017). Early access involves using [Terraform](https://www.terraform.io/)

# Sponsor Users
IBM Cloud Schematics will invite users to become sponsor users which are partners which we intend to work closely with to help solve their problems with our product. This will involve hands on observation and working sessions with development/operation teams. A more in-depth presentation and discussion will explain the details of what it means to be a sponsor user.

## Communication and Collaboration
- [Slack](https://ibm-blueprint-service.slack.com/signup)
- [GitHub](https://github.com/)
- Email

## Support & Feedback Loops
- 2-hr on-boarding session (day one)
- 2-hr follow-up working session (day three)
- Ongoing collaboration via Slack, Email, GitHub
- Bi-monthly 1-hr sync sessions (every two weeks)
