# 什么是RPC节点?

RPC（远程过程调用）节点运行与[验证者](https://docs.solanalabs.com/what-is-a-validator)相同的软件，但它不参与共识过程。技术上，您可以运行 RPC 程序并允许您的节点作为共识节点进行投票，但强烈建议不要这样做，因为您的节点将无法同时高效地完成这两项任务。

运行 RPC 节点在集群的目的是完全不同的。RPC 节点响应关于区块链的请求，并允许 RPC 节点的用户提交新的交易以包含在区块中。

例如，一个网站可能会请求将代币从钱包 A 转移到钱包 B（在获得钱包 A 的许可的情况下）。该网站需要使用钱包 A 签署交易，然后将其发送到 RPC 节点以提交给领导者。因此，您可以将运行 RPC 节点视为提供其他人使用的 API 的类似工程任务。

RPC 节点的用户通常是开发者，因此这个选项可能需要对 Solana 有更深入的技术理解。为了更好地理解 RPC 节点的操作，您需要熟悉不同的 RPC 调用。您可以在这里找到 [RPC API](https://solana.com/docs/rpc/http)。
