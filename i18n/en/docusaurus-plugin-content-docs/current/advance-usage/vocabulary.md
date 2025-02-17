---
sidebar_position: 9
keywords: [名词解释]
description: Privacy Computing Terminology Explained
displayed_sidebar: lensonsSidebar
---

# Terminology explanation
| Chinese | English | Abbreviation | Description |
|---|---|---|---|
| 隐私信息检索 | Private Information Retrieval | PIR | 也称匿踪查询，是安全多方计算中非常实用的一门技术与应用，可以用来保护用户的查询隐私，进而也可以保护用户的查询结果。其目标是保证用户向数据源方提交查询请求时，在查询信息不被感知与泄漏的前提下完成查询。即对于数据源方来说，只知道有查询到来，但是不知道真正的查询条件、也就不知道对方查了什么。 |
| 隐私集合求交 | Private Set Intersection | PSI | 参与双方在不泄露任何额外信息的情况下，得到双方持有数据的交集。在这里，额外的信息指的是除了双方的数据交集以外的任何信息。 |
| 衍生数据 | Derived Data || 联邦学习、多方安全计算中使用的数据表存在多方（不同的物理位置），所以需要将多方多数据表进行数据求交，一次对齐 ID 或特征，衍生数据是多方将数据进行求交、对齐、以及特征拉取后生成的虚拟的融合数据集。 |
| 不经意传输 | Oblivious Transfer | OT | 一种密码学协议，实现了发送方将潜在的许多信息中的一个传递给接收方，但是对接收方所接收的信息保持未知。 |
|  | XGBoost | | 是一个优化的分布式梯度增强库，旨在实现高效，灵活和便携。 |
| 安全多方计算 | Secure Multi-party Computation | MPC | 针对无可信第三方的情况下，如何安全地计算一个约定函数的问题。安全多方计算是电子选举、门限签名以及电子拍卖等诸多应用得以实施的密码学基础。 |
| 同态加密 | Homomorphic Encryption | HE | 同态加密是基于数学难题的计算复杂性理论的密码学技术。对经过同态加密的数据进行处理得到一个输出，将这一输出进行解密，其结果与用同一方法处理未加密的原始数据得到的输出结果是一样的。 |
| 全同态加密 | Fully Homomorphic Encryption | FHE | 如果一个加密函数同时满足加法同态和乘法同态，称为全同态加密。 |
| 零知识证明 | Zero-knowledge Proof | ZKP | 由S.Goldwasser、S.Micali及C.Rackoff在20世纪80年代初提出的。它指的是证明者能够在不向验证者提供任何有用的信息的情况下，使验证者相信某个论断是正确的。 |
| 可信执行环境 | Trusted Execution Environment | TEE | 基于硬件安全的 CPU 实现了基于内存隔离的安全计算，可在保证计算效率的前提下完成隐私保护的计算。 |
| 差分隐私 | Differential Privacy | DP | 由Dwork等人提出的一种保护隐私的数据共享方法，可以实现仅分享描述数据的一些统计特征，而不能反推单一记录的内容，其主要思想是添加扰动或噪声。 |
