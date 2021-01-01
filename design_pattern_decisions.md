Design Pattern 1:
    Pull over Push Payments (also known as the Withdrawal Pattern)
   With the unstakeTokens Function it allows accounts to transfer their balance from the contract to their account.

Design Pattern 2: 

I believe I have some sort of circuit breaker pattern in my contracts in the following ways
in the function stakeTokens by only adding a user to stakers array ONLY if they haven't staked already and ensuring only an owner can issue reward tokens
