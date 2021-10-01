# Panter-Airdrop
## Airdropping Stacks assets into a Btc address owner

Procedure:
1) Someone wants to allocate some stx as a gift or airdrop to an owner of a Bitcoin address, let's say Satoshi. 
2) He creates a stx contract by calling Panter-Airdrop with a balance of his favorite stx gift or airdrop amount. 
3) The created contract balance is only redeemable to the special Btc address owner defined by airdropper. 
4) The Btc address owner, say Satoshi, in a time that he likes can come and claim his allocated stx assets that someone gave him. 
5) The claim is performed by calling the created Panter-Airdrop contract and inserting his Btc txid and his favorite stx address. 
6) If his txid is verified to be after the claiming Btc block height (in the claiming interval) then the contract stx balance should be unloaded into his given stx address. 
7) Finally the stx asset is airdropped to the Btc owned individual's stx address. 

Fee adjustment: A fair commission could be inserted into panter airdrop contract fee. Let's say 2 stx tx fees, 1 sent to Satoshi-pegged address and 1 to devs address. 
