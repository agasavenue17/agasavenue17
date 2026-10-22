# Hey, I'm Avenue

I spend most of my time looking for security bugs in web apps, APIs, and smart contracts, whatever the chain. If a program has a bounty page and pays for valid reports, I'm probably reading its scope.

The web3 side is where I dig deepest: bridges, perps, lending markets. I like the parts where money moves margin, liquidations, funding, oracles because that's where the expensive bugs hide. On web2 it's the usual suspects done properly: broken access control, auth issues, logic flaws that scanners walk right past.

Every report I send comes with a working proof of concept. If I can't reproduce it, it doesn't get submitted.

## Stuff I've built

**[perp-margin-engine](https://github.com/agasavenue17/perp-margin-engine)**
A perpetual futures exchange core in Solidity — collateral vault, leveraged long/short positions, funding accrual, and liquidation with a bonus for whoever triggers it. 11 Foundry tests, CI green.

**[perp-funding-keeper](https://github.com/agasavenue17/perp-funding-keeper)**
The keeper side of the same world: funding rates from mark/index premium, health factor checks, and batch liquidations for underwater accounts. Also 11 tests, also green.

## Tools I reach for

Solidity and Foundry for contracts, Burp for web, and a lot of fork testing in between.

## Say hi

Built something and want a second pair of eyes on it? Open an issue here or find me on X or contact by email.
@agasavenue17
hallo@irsavenue.web.id
