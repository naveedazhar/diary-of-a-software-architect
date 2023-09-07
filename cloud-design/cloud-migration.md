# Cloud Migration

The Seven Common Migration Strategies (7 R’s)

* Rehost (“lift and shift”)
  * Move applications to AWS without changes. In large-scale, legacy migrations, organizations are looking to move quickly to meet business objectives.
  * Applications may become easier to re-architect once they are already running in the cloud. This happens because the hard part, which is migrating the application, data, and traffic, has already been accomplished.
* Replatform (“lift, tinker and shift”)
  * You are making a few cloud optimizations in order to achieve some tangible benefit without changing the core architecture of the application.
  * Replatforming Tools
    1. Amazon Relational Database Service (RDS) for relational databases – AWS manages the database application for you, so you can focus on the application of the database itself
    2. AWS Elastic Beanstalk – a fully managed platform where you can simply deploy your code, and AWS will handle scaling, load balancing, monitoring, database and compute provisioning for you
* Repurchase (“drop and shop”)
  * Move from perpetual licenses to a software-as-a-service model. For workloads that can easily be upgraded to newer versions, this strategy might allow a feature set upgrade and smoother implementation.
  * For example, you will discontinue using your local VPN solution and instead purchase a commercial VPN software from AWS Marketplace such as OpenVPN for AWS.
* Refactor / Re-architect
  * Re-imagine how the application is architected and developed using cloud-native features.
  * Typically, this is driven by a strong business need to add features, scale, or performance that would otherwise be difficult to achieve in the application’s existing environment.
  * This migration strategy is often the most expensive solution.
* **Relocate**
  * Basically, this migration strategy is the act of relocating your proprietary virtualization platform from your on-premises network to the cloud. This is perfect if the existing license of your on-premises platform is supported in the cloud and you want to maintain a low to medium operational complexity in managing your infrastructure. You have to assess both the cost and the operational efficiency gains first via technology replatform against the required effort to re-platform or re-architect your stack while considering migration deadlines. For example: if your on-premises servers are running in a VMWare vSphere platform, you can consider relocating your virtualized servers to AWS using the VMWare Cloud on AWS service.
* Retire
  * Identify IT assets that are no longer useful and can be turned off. This will help boost your business case and direct your attention towards maintaining the resources that are widely used.
* Retain
  * Retain portions of your IT portfolio if there are some applications that are not ready to be migrated and will produce more benefits when kept on-premises, or you are not ready to prioritize an application that was recently upgraded and then make changes to it again.

![7 common migration strategies - 7 Rs SAP-C02](https://td-mainsite-cdn.tutorialsdojo.com/wp-content/uploads/2019/05/7-common-migration-strategies-7-Rs-SAP-C02.png)

* The following strategies are arranged in increasing order of complexity — this means that the time and cost required to enact the migration will be proportional to the increase, but will provide greater opportunity for optimization
  * Retire(simplest) < Retain < Relocate < Rehost < Repurchase < Replatform < Re-architect/Refactor (most complex)
* Consider a phased approach to migrating applications, prioritizing business functionality in the first phase, rather than attempting to do it all in one step.
