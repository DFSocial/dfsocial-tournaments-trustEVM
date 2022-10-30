# SuperGaming Smart Contract

It allows the storage of the data (sponsors, gamers & scores) for all the tournaments organised inside DFSocial Gaming platform, as well as make posible all the payments (entries payments, rewards distribution, token burns, team fees, buybacks & liquidity additions).

This contract is not deployed and must be updated before its deployment. It requires the existence of a TrustEVM's DEX in order to:
- Make swaps: selling and buying $DFSG (against $USDT and native chain token [$EOS])
- Add liquidity to the pool $DFSG / $EOS
- Get the current price of $DFSG


# StakingDFSG_TrustEVM Smart Contract

Stake $DFSG, earn $DFSG.

This contract is not deployed and must be updated before its deployment. It requires the token address of $DFSG token in TrustEVM chain.

- %APY = Current number of stakers
- Min. amount to stake = 25,000 $DFSG
- Lock period = 1 month
- Claiming the rewards is available anytime.

# BridgeDFSG_TrustEVM Smart Contract

Used to convert $DFSG in BNB Chain to $DFSG in TrustEVM Chain.

This contract is not deployed and must be updated before its deployment. 
It requires the token address of $DFSG in TrustEVM Chain.

- bDFS = $DFSG in BNB Chain
- DFSG = $DFSG in TrustEVM CHain

There is a 5% bonus for those brinding in a early phase.
