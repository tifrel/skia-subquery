Scope: define the basic interface for interaction

Competing yield farming strategies (all based on KSM for now):

- Borrow kUSD against KSM, provide liquidity for KSM/kUSD
- Liquid stake KSM to get LKSM, provide liquidity KSM/LKSM
- Liquid stake KSM -> LKSM -> borrow kUSD -> provide liquidity kUSD/KSM

- constituent metrics:

  - LKSM staking returns
  - LP returns for KSM/kUSD
  - LP returns for KSM/LKSM

- When borrowing, we will use a factor 2 for overcollateralization to avoid
  liquidation
