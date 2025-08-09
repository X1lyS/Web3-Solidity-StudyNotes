# 前置准备

Solidity在线编译器
- https://remix.ethereum.org/
<img width="2825" height="1237" alt="image" src="https://github.com/user-attachments/assets/755b6897-6361-4792-aae0-55e015c8570d" />

# 编写程序

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.21;
contract HelloWeb3{
    string public X1ly_S = "Hello Web3!";
}
```

- // SPDX-License-Identifier: MIT

这是版权声明注释，声明该合约为MIT。

MIT是一种宽松的开源许可证类型，允许他人自由使用、修改、分发代码，但需保留原始许可证声明和版权信息。MIT 许可证对商业应用友好，是智能合约常用的许可证之一

如果不写这一行的话，编译器会发出警告！推荐写，因为明确的许可证可避免法律风险，如未经授权的使用。

- pragma solidity ^0.8.21;

声明源文件所使用的 Solidity 版本，”^”表示源文件允许的编译器版本范围在`0.8.21`~`0.9.0`

- contract HelloWeb3{

contract关键字声明智能合约HelloWeb3

- string public   X1ly_S= ”Hello Web3!";

声明string public 变量 X1ly_S

# 编译部署合约

1. 编译

<img width="2752" height="1536" alt="image" src="https://github.com/user-attachments/assets/ea7c3be3-bc4a-45b1-920f-d9c6f577d12d" />

2. 部署
<img width="2270" height="1598" alt="image" src="https://github.com/user-attachments/assets/180417eb-ca36-4dd1-9175-155cfbfa61e5" />

