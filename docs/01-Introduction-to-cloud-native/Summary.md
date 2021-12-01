## 1.8 总结

* 云是一种 IT 基础设施，以商品的形式提供计算、存储和网络资源。用户只为实际使用的资源付费。
* 云原生应用程序是专为云端运行的应用而设计的高度分布式系统。
* 云服务商以不同的抽象级别提供服务：基础设施即服务（IaaS）、容器即服务（CaaS）、平台即服务（PaaS）、功能即服务（FaaS）或软件即服务（SaaS）。
* 云原生应用程序具有水平可扩展性、松散耦合性和高度内聚性，具有故障恢复能力、可管理性和可观察性。
* 云原生开发由自动化、持续交付和 DevOps 支持。云原生是一种文化，支持不同角色之间的协作，以共同交付业务价值。
* 现代企业采用云原生技术开发快速交付的软件，可根据需求动态缩放，且始终可用，在优化成本的同时具有故障恢复能力。
* 容器可以用作计算单元来设计云原生系统。他们比虚拟机更轻量，并提供可移植性、不变性和灵活性。如：Docker。
* 专用平台提供管理容器的服务，而无需直接处理底层。它们提供容器编排、集群管理、网络服务和调度。如：Kubernetes。
* 无服务器模式是一种云服务商管理服务器和后端函数的模式，而开发人员只需关注业务逻辑。后端函数在每次使用时计费，以实现成本优化。如：Google Functions。
* 微服务架构可以用于开发云原生应用程序，但并不是必须的。云原生与微服务不完全相同。
* 要设计云原生应用程序，您可以使用 `基于服务` 的架构，其要素是：服务和交互。服务可以进一步分为：应用程序服务（无状态）和数据服务（有状态）。