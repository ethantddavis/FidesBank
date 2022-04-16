# ETHDenver2022 Project Fides Bank

This project aims to create an undercollateralized borrowing platform, where users can take loans of Fides token, which aims to stay close to the value of the US dollar. The more a user builds up a history of repayment, the more uncollateralized fides they are allowed to borrow. Initially the user must deposit the amount of DAI they wish to be able to borrow against, and they gradually would be able to increase their borrowing limit. Fides that is borrowed beyond DAI collateral is accompanied by a nontransferable Debt token, which aims to publicly signal which address have outstanding loans. 

<h2>Some ideas on why Fides might retain value equal to $1</h2>

bank only accepts DAI as collateral
user A wants to borrow to buy a house, user B wants to extract value from the system

A deposits 100 DAI, borrows 101 token, cashes out to buy house

loan/interest repayment only accepted in borrow token

If token price is > DAI price (lets say token = $1.10)

    B expects more people like A to borrow, borrowing increases supply, selling decreases price

    B deposits 100 DAI, borrows 100 tokens, sells tokens for DAI, buys tokens at lower price, pays off 

If token price < DAI price (token = $0.90)

    A sees it is favorable to pay off loan, buys tokens at a low price, pays off loan, decreasing supply

    B expects people like A to pay back their loan, buys tokens
