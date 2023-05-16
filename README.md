1. Clone/Download the Repository

2. Install Dependencies:
$ npm install

3. Start Ganache

4. Migrate Smart Contracts
$ truffle migrate --reset

5. Run 1st script
$ truffle exec .\scripts\1_create_proposal.js

---

## Output will be like below

```
truffle exec .\scripts\1_create_proposal.js
Using network 'development'.

Funds released? false
Funds inside of treasury: 25 ETH

Created Proposal: 43483180792989864850383959400668517965767558217107172646126570864166039121810

Current state of proposal: 0 (Pending)

Proposal created on block 21
Proposal deadline on block 26

Current blocknumber: 21

Number of votes required to pass: 50

Casting votes...

Current state of proposal: 1 (Active)

Votes For: 150
Votes Against: 50
Votes Neutral: 50

Current blocknumber: 27

Current state of proposal: 4 (Succeeded)

Current state of proposal: 5 (Queued)

Current state of proposal: 7 (Executed)

Funds released? true
Funds inside of treasury: 0 ETH
```
