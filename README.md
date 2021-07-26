# Carbon-Project



Technical Descirption

1.	carboncredits.sol: Creates a registration template that takes in details from 3 groups:
•	Group 1 - Verifiers: They validate carbon credits from credit holders. They also verify that carbon tokens burnt are equivalent to the burning of a proportionate amount of emissions.
•	Group 2 – Creditholders: They are organizations that already hold carbon credits in the emissions trading ecosystem
•	Group 3 – Customers: They are individuals and companies interested in offsetting their carbon footprint by buying carbon credits and burning the carbon token.
2.	credittoken.sol: Creates an ERC20 token based on supplied and approved carbon credits through a series of functions:
•	Approve credits entered by the creditholders, which is certified by the verifiers.
•	Mint the Carbon token.
•	Make the Carbon token transferrable and burnable.
3.	certification.sol: Creates an ERC721 token (NFT) as a badge of successful burning carbon tokens, representing offsetting carbon emissions.
•	Mint an ERC721 token for every 20 Carbon tokens burnt.
4.	Create a Balancer Smart Pool (AMM)
•	A smart pool that includes swappable DAI - Carbon token pair
•	The pool provides incentives for liquidity providers through a transaction fee
•	It also provides dynamic pricing for the Carbon token

