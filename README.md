from web3 import Web3

# 连接到以太坊节点
w3 = Web3(Web3.HTTPProvider('https://mainnet.infura.io/<your Infura API key>'))

# 打印最新的块号
print(w3.eth.blockNumber)

# 打印当前gas价格
print(w3.eth.gasPrice)

# 打印默认账户的余额
print(w3.eth.getBalance('0x0000000000000000000000000000000000000000'))
