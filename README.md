# DataSChain
基于Hyperledger Fabric联盟链和IPFS实现具体业务场景下多参与方之间的安全数据共享，用户下载数据可以验证数据完整性，项目适合用作毕设学习，二次开发。
The implemented code comprises three fundamental components:

1. hyperledger-fabric-contract-java-dataShare: This module constitutes the chain code, uploaded to  Hyperledger Fabric.
2. QKsysytem: Representing the data sharing system, this component serves as an intuitive interface enabling users to visualize and manage operations effectively.
3. io.jboot: As the data transfer system, this module ensures secure and encrypted transmission of data among nodes within the network.

| Dependencies       | Version  |
| ------------------ | -------- |
| Go                 | 1.18.3   |
| Hyperledger Fabric | 2.4.1    |
| Docker Engine      | 1.23.2   |
| Docker-compose     | 20.10.14 |
| IPFS               | 0.17.0   |
| MySQL              | 5.7      |
| Redis              | 5.0.10   |
| jdk                | 1.8      |

You can log in to the system as the following users:

| Account | Password |
| ------- | -------- |
| admin   | 123123   |
| test    | 123456   |
