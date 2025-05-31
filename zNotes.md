1. Only the owner can mint dTSLA token
2. Anyone can redeem the dTSLA token for USDC or "the stablecoin" of choice. This is actually what's going to keep the DTSLA token pegged. You can always sell or swap your DTSLA token for USDC
3. Chainlink functions will kick off a TSLA sell for USDC, and then send them to the contract.
4. And then finally the user will have to call finishRedeem to get their USDC out.

5. forge init --force