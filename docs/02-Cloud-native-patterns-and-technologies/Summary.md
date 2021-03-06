## 2.6 总结

* 构建云原生应用程序的良好起点是 `十五要素` 方法论。它确定了开发原则，以提供跨执行环境的最大可移植性，适合部署在云平台，方便扩展，保证开发和生产环境之间的一致性，并可实现持续交付。
* Spring 是一个套件，它提供了构建现代应用的所有常用功能。核心是 Spring 框架，提供的应用程序上下文，在整个生命周期中管理 bean 和属性。
* Spring Boot 为加快云原生开发奠定了基础。可快速构建生产就绪的应用程序，包括嵌入式服务器、自动配置、监控和容器化等功能。
* Docker 是一种创建容器的技术。我们将 Spring 应用程序封装为容器，可跨环境移植，并对其运行时依赖关系有更多的控制。
* 容器镜像是轻量级的可执行包，其中包含了在内部运行应用程序所需的所有内容。Spring Boot 应用程序可以使用 Cloud Native Buildpacks 打包为镜像。
* 通常在云原生系统中，您需要处理多个容器，管理如此复杂的系统需要一种方法。Kubernetes 提供了以下功能：协调、安排和管理容器。
* Kubernetes Pod 是最小的部署单位。Kubernetes Deployment 描述如何从容器镜像开始，将应用程序实例创建为 Pod。Kubernetes Service 允许您在集群外部公开应用程序端点。


