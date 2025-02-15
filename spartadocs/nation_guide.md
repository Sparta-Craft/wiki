---
layout: default
title: Nation
nav_order: 7
description: "Nation Guide"
permalink: nation-guide
---

# Create a nation
{: .fs-9 }

<img src="/assets/images/nation.jpg" alt="nation-image"/>

{: .mt-5 }
{: .caution }
Make sure your nation's name complies with the nation naming [rules].

## Create a nation

Creating a new nation costs 1000 gold. Make sure you deposited the required amount in town's bank via `/t deposit [amount]`. Only a mayor of a town can create a nation. The mayor's town will become the nation capital. Create the nation with `/n new [name]`.

## Nation basics

As a nation leader, you can add allies with `/n ally add [nation]` and invite towns to your nation with `/n add [town]`.

Give and remove ranks from residents of your nation with `/n rank add [player] [rank]` or `/n rank remove [player] [rank]`. You can also kick towns from the nation with `/n kick [town]`, delete the nation with `/n delete`, toggle public joining to your nation with `/n toggle open`, and set the nation's spawn location anywhere within your capital with `/n set spawn`.

Due to nations starting with no allies, you will likely want to get a lot as quickly as you can as you require them to travel anywhere with the `/n spawn` command. An efficient way to do so is by regularly checking `/res list`, and running the `/res` command on all nation kings as marked by a yellow name, then do `/t [name]` for the town listed in their `/res` and send an ally request to them.

As your nation gains more citizens, your ranking on `/n list` will increase. Nations fight each other to be on the top of this list as it shows who has put the most time into recruiting towns and players, which is a good indicator of activity. Nations (as well as towns) can also compete in a few categories. These leaderboards can be seen via `/nation (or /town) list by category` (categories should be automatically shown to the command sender).

## Nation ranks

Nation kings can give nation residents ranks with `/n rank add [player] [rank]`.

- ***Chancellor*** allows the player to do everything a king can do, except of: deleting the nation, setting the capital and setting the king. This is a dangerous rank to give as a player! The unwanted individual could remove allies or kick every town from your nation.
- ***Colonists*** may invite towns to the nation.
- ***Royal-Treasurers*** can not only deposit, but also withdraw gold from the national bank.
- ***Diplomats*** are able to send, accept and deny nation ally requests.

# Nation commands

Only king and nation residents with appropriate ranks can run nation commands.

| Plot type    | Description       | 
|:-------------|:------------------|
|/n [name]	|Get information of specified nation|
|/n new [name]	|Create a new nation|
|/n leave	|Makes your town leave nation|
|/n withdraw [amount]	|Withdraw gold from nation bank|
|/n deposit [amount]	|Deposit gold from nation bank|
|/n add [town]	|Invite town to nation|
|/n kick [town]	|Kick a town from nation|
|/n ally add/remove [nation]	|Add/remove nation ally|
|/n rank add/remove [player][rank]	|Grant/revoke rank from nation resident|
|/n set king [player]	|King command to change the king of the nation|
|/n set capital [town]	|Set nation capital|
|/n set spawn	|Set nation spawn at your location|

[rules]: /server-rules#21-naming