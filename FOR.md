# FOR REMOVING OP_CODE FILTERS

## Arguments For Reduced OP_CODE Filters In Bitcoin Node Implementations


### Statment: As shown above knots already filters monetary txs coinjoins and sub sat fees. You can add any filter you want to your node, because it doesn't require consensus. Therefore a government can filter whatever they want, luckily it would fail because Bitcoin is designed to be censorship resistant.

  Bullet: You could argue that a coinjoin is not an actual monetary use-case between 2 people transacting.   Does current Bitcoin node implementations even support filtering "Bitcoin specific monetary transactions outlined in the Whitepaper"?  I suspect they do not, and therefore the Government would not be able to do this.   What Bitcoin nodes should continue to support, is filtering (at layer-1) of anything non-monetary getting into blocks (i.e. layer-0).



### Statement: It doesn't matter, your node will follow consensus whether you like it or not. Filters have been proven not to work many different times. Sub sat fees are not paying more and are not being slowed down, even with 99% coverage. So what is it you think filters are accomplishing?

  Bullet: Saying filters are proven not to work is untrue.  This could be proven by scanning the history of transactions, and measuring average size of OP_CODE over time.   If it has grown as of late, then that is proof that larger OP_CODES are succeeding in getting in.   The relative non-existence of long OP_CODES is the evidence that it was working in the past.



### Statement: If filters can succeed at this that also means governments can just spin up a bunch of nodes that block "unsanctioned" transactions. Bitcoin is not this fragile, it is specifically designed to maintain permissionless usage and uphold censorship resistance.


  Bullet: It is not true that governments could run existing Node implementation and block pure monetary p2p transactions.  It is de-incentivized, since they would spend a lot of money and resources and success would not be very likely to justify the wasteful spending.   They would have to control 99% + of the nodes in the system to block something from getting in a block.


### Statement: The real problem is some people dont like how other people value blockspace and create FUD about how it will kill Bitcoin or how devs are malicious.  But it doesnt matter what you or I like. What matters is what an individual is willing to pay for blockspace with their money on a permissionless monetary network.

  Bullet:  Yes, let them pay for using our blockspace to store non-monetary data.  If they are paying more than is paid by monetary transactions, then I would say "filtering is working", or you could say "spam is de-incentivized".  


### Statement: No rules were loosened for sub sat fees and even with 99% of nodes filtering them they are being propagated and mined. What does this tell you about filtering?


  Bullet:  The fact is that those sub sat fee txos in blocks got in there because there were less than 1% of nodes allowing them in, and a miner using that node put them in there.   There is no possible way you can run enough filtering nodes to stop sub sat fee txos from getting in, if someone wants to mine with them.  The only reason this happened was during a time when fees overall were very low and empty blocks were common.  I don't think it would not happen if transaction demand was high.


