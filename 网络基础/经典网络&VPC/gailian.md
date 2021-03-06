## 1、VPC是什么？（私有网络）
VPC（Virtual Private Cloud）是公有云上自定义的逻辑隔离网络空间，与用户在数据中心运行的传统网络相似，托管在VPC内的是用户在私有云上的服务资源，如云主机、负载均衡、云数据库等。用户可以自定义网段划分、IP地址和路由策略等，并通过安全组和网络ACL等实现多层安全防护。同时也可以通过V**或专线连通VPC与用户的数据中心，灵活部署混合云

<br><br>

## 2、经典网络（基础网络）和VPC区别
经典网络：公有云上所有用户共享公共网络资源池，用户之间未做逻辑隔离。用户的内网IP由系统统一分配，相同的内网IP无法分配给不同用户。<br><br>

VPC：是在公有云上为用户建立一块逻辑隔离的虚拟网络空间。在VPC内，用户可以自由定义网段划分、IP地址和路由策略，安全可提供网络ACL及安全组的访问控制，因此，VPC有更高的灵活性和安全性。 经典网络和VPC的架构对比图：

<img src="https://blog-10039692.file.myqcloud.com/1488462386955_6778_1488462387211.png">
