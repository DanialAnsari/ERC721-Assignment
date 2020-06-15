# ERC721-Assignment
Question
Following would be the data structure of Property - Register a Property: Property register with its detail and link for more details as URI (add zameen.com urls).  - Define Property asking value (demand) in Ether - By default on register property will not be on Sale. - List Property: A function will enable property for sale - Buying Request: A request for buying property with offer value - Offer Reject: A owner can reject the offer  - Offer Accept: A owner can accept offer - Buy Property against Offer: Transfer ownership on successful transfer. 
How to run
1) First run the register property function to create a token.
2) Than a seperate address would call the addBuyRequest function for the created token.
3) Than the owner of the token may call acceptOffer or rejectOffer to either accept or decline the proposed request.
4) If owner has approved the request the buyer who proposed the request may purchase the property by calling the buyProperty function and pass the offered amount of money in wei. This will make the buyer the new owner of the token.
