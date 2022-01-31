# Fluidum

Fluidum, a Dapp Hackaton project which aims to create the right tool to engage mass adoption of money streaming by proving user the ability to stream money to phone numbers

## Major building blocks and challenges

1) Phone Identification, association with blockchain address
   - Creation of random password (vrf Chainlink)
   - Custom chainlink adapter posting to sms provider the random password
   - Encrypted password validate period 5 minutes
   - Store address=> phone number on chain
   
2) Leverage Superfluid for money transfer
   - Stable coin as supertoken
   - Establishing maximal and minimal accepted deviation of exchange variation 

3) Dapp in Angular frontend with components:
   - Phone Identificaiton
   - Streaminto to checkout

