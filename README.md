# Fie3wall

### Problem Statement
Nowadays, we are hearing a lot of cases about token transfers getting transferred to the wrong account. This may happen due to negligence or some kind of malware that changes the address while we are transferring tokens. This problem is increasing day by day and once the funds are transferred. The transaction cannot be reversed.

Therefore, it is vital to have a middleware which can be used to make secure transactions. I aim to provide users with a seamless solution to transfer ERC20 tokens between accounts across different chains/networks while maintaining control over their funds.

### Solution
- Fir3wall is an added security layer designed to enhance the safety of cross chain asset transfer. It supports support transfer of ERC20 tokens from one network to another.
- If tokens are delivered to the wrong address, users may quickly undo transactions.
- It functions by using a smart contract to store funds until the designated recipient claims them. The sender has the option to reverse the transaction and get their tokens back if the recipient doesn't pick up the tokens or if they realise they sent tokens to the wrong or unanticipated address.
- The receiver can claim the funds and bridge them to another network by paying the desired gas fees and completing the bridging of tokens from one chain to another safely


### Axelar Scan Link
https://testnet.axelarscan.io/gmp/0x3e38c27c76e4eb2fb96d79454caff21fd07882ebeb382ff9fe1db3ebd2a51b04:48

### My experience with Axelar
1. The cross chain transfer of ERC20 was way easier than I imagined. The folks working at Axelar have nailed it.
2. The documentation/examples were very good. I also watched the tutorials on the Axelar youtube channel and they were easy to execute and the explanation was really well

### Use Cases
- Can be easily implemented on top of existing wallets / Dapps

### Future Plans
- NFT integration
- Build and intuitive interface