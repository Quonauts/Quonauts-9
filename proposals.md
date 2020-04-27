# Quonauts 9: Quorantine — Proposals

<a name='1'/>

## #1 — Passed

Add a rule "Quantities" (%quantities) in %root:
> A quantity is a named property with a numerical value for each player.
> 
> By default any unique quantity added to the game:
> * applies to all players.
> * is instantiated at zero.
> * must be an integer.
> * must never have a negative value.
> 
> When a new quantity is created, a subsection of this rule must be created, containing a short description and possible gameplay effects. The description has no relevance to the game.

Add a rule "#transactions" (%transactions) in %channels:
> The #transactions channel may be used to modify quantities, but only in ways specifically allowed by the rules.

<a name='2'/>

## #2 — Failed

Replace paragraph in %proposals, from
> If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since their last proposal, it may be failed without a vote.
to
> If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since their last open proposal, it may be failed without a vote.

<a name='3'/>

## #3 — Passed

Edit %closing-proposals, changing
> All active players have cast a vote or abstained from voting on the proposal.
to
> All active players have cast a vote or abstained from voting on the proposal, and there are more than two active players.

<a name='4'/>

## #4 — Passed

This proposal is incompatible with #2.

Edit %proposals, changing
> If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since their last proposal, it may be failed without a vote.
to
> If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since they last created a proposal, it may be failed at any time if it is open.

<a name='5'/>

## #5 — Failed

Add Sinthorion to active players.

<a name='6'/>

## #6 — Failed

This proposal is incompatible with #6.

<a name='7'/>

## #7 — Failed

<@!549449251822764043> wins Quonauts 9

<a name='8'/>

## #8 — Failed

Remove
If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since their last proposal, it may be failed without a vote.
from %proposals.
Add
If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since their last open proposal, it may be failed without a vote.
to %closing-proposals

<a name='9'/>

## #9

Remove
If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since they last created a proposal, it may be failed at any time if it is open.
from %proposals.
Add
If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since the creation of their last open proposal, it may be failed at any time if it is open.
to %closing-proposals

<a name='10'/>

## #10 — Failed

Add a rule "Winning" (%winning):
> Any player who successfully finishes construction of a death star wins the game.

<a name='11'/>

## #11 — Passed

Define a new quantity named Points, with this description:
*** Points** are an arbitrary (positive integer) value which should generally be used as a reward/currency.

<a name='12'/>

## #12 — Failed

Define a new quantity called Clay, with this description:
*** Clay** is a positive real value which is used to build things

<a name='13'/>

## #13 — Failed

Add a new section Voting Power (%voting-power) that is a subsection of %quantities:
> Voting Power is initialized to one. Whenever a player votes on a proposal or poll, that player's vote is worth a number of votes equal to that player's Voting Power.

<a name='14'/>

## #14 — Passed

This proposal depends on propsoal #11.
Create a new rule within %Quantities% named "Obtaining Points". This rule section should be updated whenever a new method is created.
> When a proposal is passed, its author obtains 2 points and the person who enacted it obtains 1, if this is applicable.

<a name='15'/>

## #15 — Deleted

<a name='16'/>

## #16 — Passed

Edit %quantities, changing
> When a new quantity is created, a subsection of this rule must be created, containing a short description and possible gameplay effects. The description has no relevance to the game.
to
> The following quantities exist:
> *
> 
> When a new quantity is created, it must be added to the above list, along with an optional short description. The description, if present, has no relevance to the game.

If proposal #11 has passed, add the "points" quantity to the list of quantities.
If proposal #12 has passed, add the "clay" quantity to the list of quantities.

<a name='17'/>

## #17 — Failed

Make a new rule section named "Cabals" below all other rules:
> A cabal is defined as a collection of 2 or more players. A player may belong to only one cabal, and cabals are part of the game state. The creator of a cabal is the owner, and may invite other players into a cabal or kick them out. Cabals must be named.
> 
> All members of the Dramly cabal win the game. This applies at all moments in the game.

<a name='18'/>

## #18 — Failed

Depends on #11.
Add a rule "Winning" (or append to it if it already exists):
> The first player to reach 100 points wins the game.

<a name='19'/>

## #19 — Failed

Depends on #18.

Add a new rule "The end" (%the-end) after %winning:
> The game ends when one or more players have won.

<a name='20'/>

## #20 — Failed

disallow <@!160279332454006795>  from changing people's nicknames without their consent

<a name='21'/>

## #21 — Passed

If g doesn't change their nickname to something other than "g" within 48h, any of their proposals may be failed instantly. (Note: "g" refers to any player currently named "g").

<a name='22'/>

## #22 — Passed

This proposal depends on #16.

Remove the %points rule section.

<a name='23'/>

## #23 — Failed

Edit %closing-proposals, changing
> * A majority of active players have voted in favour of the proposal, and there are more than 2 active players.
> * A majority of active players have voted against the proposal, and there are more than 2 active players.
to
> * A majority of active players have voted in favour of or abstained from voting on the proposal, and there are more than 2 active players.
> * A majority of active players have voted against or abstained from voting on the proposal, and there are more than 2 active players.

<a name='24'/>

## #24 — Failed

You're a hero, George! aaa i have a headache while writing this proposal :( im gonna sleep now goodnight please write good well thought out proposals regarding possibly like trade of the points currency, maybe even a way to buy votes (extremely expensive because op), etc

<a name='25'/>

## #25 — Passed

gn

<a name='26'/>

## #26 — Passed

Edit %rule-violation-polls: Replace every occurence of 🇦  with 👍 and ever occurence of 🇧 with 🤷.

<a name='27'/>

## #27 — Passed

Create quantities land-x and land-y, which can be negative.

Create a new rule "#the-land" (%the-land) in %channels:
> #the-land is used to announce land actions.

Create a new rule "Land" (%land) in %root:
> The Land is an infinite square lattice. A 'land tile' is a point of this lattice, and has corresponding coordinates.
> 
> 'land-x' and 'land-y' are quantities. A player with (land-x, land-y) matching the coordinates of a certain land tile 'resides' in that land tile.
> 
> 'North' and 'South' respectively correspond to the positive and negative y-axis, and 'East' and 'West' respectively to the positive and negative x-axis.

Create a new rule "Land actions" (%land-actions) in %land:
> Each subsection of this rule corresponds to a land action. Players make a land action by announcing it the #the-land, and carrying out the effects as specified by the subsection. After a player makes an action, they must wait 12 hours before performing another action.

Create a new rule "Land movement" (%land-movement) in %land-actions:
> As a land action, a player may move to a neighbouring tile, i.e. add or subtract one from their land-x or land-y.

<a name='28'/>

## #28 — Passed

This proposal depends on #27.

Edit %quantities, changing
> By default any unique quantity added to the game:
> * applies to all players.
> * is instantiated at zero.
> * must be an integer.
> * must never have a negative value
to
> By default any unique quantity added to the game:
> * applies to all players.
> * is instantiated at zero.
> * must be an integer.
> * must never have a negative value
> * may be traded.

The land-x and land-y quantities may not be traded. Their descriptions in %quantities may be edited to reflect this.

Create a new rule "Trade" (%trade) in %land-actions:
> As an action, two players residing in the same land tile may trade a certain number of points in exchange for a certain number of another tradable quantity.
> 
> Both amounts must be greater than zero. Both players must have amounts of their quantity greater than or equal to the amounts specified in the trade.
> 
> After both players announce the trade in #the-land (they must both specify which quantities will be traded, and the amounts, and both players' announcements must match), the quantities are exchanged as per the trade.
> 
> After a trade, both players must wait one hour, after which they may perform another action (this overrides the usual 12 hour cooldown).

<a name='29'/>

## #29 — Passed

Edit %glossary, changing the definition of "Game State" from
> Every current rule; every non-deleted proposal and any votes on it; every poll and any votes on it; and every message or reaction in any game channel.
to
> Every current rule; every non-deleted proposal and any votes on it; every poll and any votes on it; every quantity and each player's amount of that quantity; and every message or reaction in any game channel.

<a name='30'/>

## #30 — Failed

Create new quantity "ponits", with the description:
* **Ponits** describes how many ponits a player owns. A ponit may use the moves "Tackl", "Embr", "Flame Charg" and "Stmp".

Give <@!91269654017748992> one ponit.

<a name='31'/>

## #31 — Failed

Create a vote. Any player may vote for any active player. Any one of those players who gets at least three votes in twenty-four hours loses.

<a name='32'/>

## #32 — Failed

hi

<a name='33'/>

## #33 — Failed

Create a new quantity called "prestige points" with the following description:
* At any time, a player may exchange their points for half as many prestige points, rounded down. Players may trade prestige points for any other quantities which may be legally traded.

<a name='34'/>

## #34 — Passed

Create a new quantity "land" (the amount of land a player has claimed)

Create a new rule "Claiming land" (%claiming-land) in %land-actions:
> As a land action, a player who resides in a land tile that has not been claimed may claim that land tile. When a player claims a land tile, they gain 1 land.

<a name='35'/>

## #35 — Failed

Players have spaceships with which they can travel around. Replace every occurrence of "land" in rule %land or any sub-rule of it (including the rule titles and tags) with "space" (maintaining the same capitalisation).

<a name='36'/>

## #36 — Failed

Create a new property named "Proposals" with the following description:
> * When a proposal is (legally) passed, the author gains one "Proposal".
Add a new paragraph to "Obtaining Points":
> For every 10 "Proposals" the author has, add one to the amount of points they receive upon their proposal being successfully passed.

<a name='37'/>

## #37 — Failed

(whoops)
This proposal depends on proposal #36.
Add a new rule section within Quantities named "Obtaining Proposals":
> When a proposal is legally passed, its author gains one "Proposal" (as in, the quantity).
> If 3 proposals by the same author are failed in a span of 24 hours, and this failing is due to the proposal having more/equal against votes than for, then the authors "Proposals" decrease by 1, and 1 per every proposal failed afterwards which also fits in this time period. Proposals cannot be negative, and if a player would gain negative Proposals, they will merely stay at 1 Proposal.

<a name='38'/>

## #38 — Failed

Append the following to the end of %land-movement:
> A player may not move to a land tile if another player currently resides there.

Replace the following in %trade:
> As an action, two players residing in the same land tile may trade a certain number of points in exchange for a certain number of another tradable quantity.
with:
> > As an action, two players residing in neighboring land tiles (land tiles within at most 1 distance of each other) may trade a certain number of points in exchange for a certain number of another tradable quantity.

<a name='39'/>

## #39 — Failed

give <@!421060058009305088> a new role, "mapman", since they're the only person that's actually updating the maps

<a name='40'/>

## #40 — Passed

Replace the rule %land-movement by:
> As an action, a player may move to a different tile which has an euclidean distance of up to the player's movement speed from their current position. In other words, they may change their land-x and land-y such that `sqrt(dx²+dy²) ≤ movement speed`, where `d<n> = old land-<n> - new land-<n>`.
> 
> The movement speed of each player is 3, unless other rules modify it.

<a name='41'/>

## #41 — Failed

Proposal number 41 is automatically failed

<a name='42'/>

## #42 — Failed

Create a new channel named #jibson. Give gibson 2 points. Take 3 points from gibson. Award gibson 1 point.

<a name='43'/>

## #43 — Failed

The last person to vote for Proposal #43 gets one point

<a name='44'/>

## #44 — Passed

Edit %land-actions, changing
> After a player makes an action, they must wait 12 hours before performing another action.
to
> After a player makes an action, they must wait 2 hours before performing another action.

Remove from %trade:
> After a trade, both players must wait one hour, after which they may perform another action (this overrides the usual 12 hour cooldown).

<a name='45'/>

## #45 — Passed

Create a new rule named Proposal #9:
> Proposal #9 is to be considered open indefinitely, and cannot be closed. This overrides all other rules, including all rules which state they override this one.

<a name='46'/>

## #46 — Failed

Add a new rule, %contradiction, which overrides %proposal-#9. This overrides all other rules, including all rules which state they override this one.

<a name='47'/>

## #47 — Failed

Create a new rule named Proposal #46:
> When proposal #46 is enacted, all changes to the game state caused by proposal #46 being enacted are to be retroactively reverted, and proposal #46 is to be reopened for voting.

<a name='48'/>

## #48 — Failed

Create a new rule named Proposal #48:
> When proposal #48 is enacted, all changes to the game state caused by proposal #46 being enacted are to be retroactively reverted, and proposal #48 is to be reopened for voting.

<a name='49'/>

## #49 — Failed

Create a new rule named %i-just-wanted-to-have-fun, which sates: when proposal #49 is enacted, the results of proposals #47 and #48 are retroactively reverted.

<a name='50'/>

## #50 — Failed

Create a new rule named ugh go away mooooosey:
Proposals 49 through 55 are to be retroactively undone, and failed. This is done because there is probably going to be a large amount of spam.

<a name='51'/>

## #51 — Passed

Change the content of %<#700035956522090596> to:
> Proposals can be made by posting them to the <#700035956522090596> game channel.
> 
> The first proposal is numbered #1 and each subsequent proposal's number is increased by 1. Deleted proposals retain their number.
> 
> A proposal is either open or closed. When it is first submitted a proposal is open. A non-deleted, closed proposal is either passed or failed. When a player closes a proposal, they must either pass it or fail it. A deleted proposal is closed, but does not pass or fail.
> 
> If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since they created their most recent currently open proposal, it may be failed at any time if it is open.

<a name='52'/>

## #52 — Failed

Reopen Proposal #52

<a name='53'/>

## #53 — Failed

Create a new rule %land-map with the following content under %land:
> The #land-map channel must contain exactly one message, whose contents are a link to a datastore viewable and editable by all players. This datastore must contain all data needed for a complete, accurate description of The Land's and all players' states. The datastore must also be updated at least every 36 hours.
> 
> Falsifying map data violates this rule. In the event of data falsification or addition of bad actions (Land actions not within the rules), the Land state must be reverted to its latest recorded legitimate state. 
> 
> walter

%land-map will not be enforced until 36 hours have passed (after this proposal passes)
Create a channel called #land-map.

<a name='54'/>

## #54 — Failed

[SILLY PROPOSAL]

Change the content of %voting-on-proposals to:

> Hmm yes Freedom Dive very good music yes indeed

<a name='55'/>

## #55 — Failed

If and only if less than 1/2 of previous proposals have passed, give <@151149148639330304> that Cool role they keep asking for

<a name='56'/>

## #56

Add rule "Opinion Polls" as subrule of %polls:
> Players may conduct polls to informally gather opinions about any game relevant topic, called "opinion polls".
> 
> An opinion poll may only be created if no other opinion poll by that player is currently open. By default, the allowed reactions of an opinion poll are thumbsup and thumbsdown, but the opinion poll may specify different allowed reactions for itself.

<a name='57'/>

## #57

Add a quantity called "Worship"
At any time, if they have not in 12 hours, a player may worship heavpoot to gain one Worship.

<a name='58'/>

## #58

Add a new rule, %winning:
> All players win the game. The game does not end.

<a name='59'/>

## #59

Add a new rule, %primes, under %quantities:
Upon the legal passing of a prime-numbered proposal, the author gets an additional point.

<a name='60'/>

## #60

Add a new rule %composites, under %quantities:
Upon the legal passing of a composite-numbered proposal, the author gets an additional point.

<a name='61'/>

## #61

Add a new rule %perfects, under %quantities:
Upon the legal passing of a perfect numbered proposal, the author gets an additional point.

<a name='62'/>

## #62

Add a new rule, %tree, under %quantites:
Upon the legal passing of a proposal of number TREE(n) for any n, the author gets points equal to the number of the proposal

<a name='63'/>

## #63

Add a new rule %odd-perfects, under %quantities:
Upon the legal passing of an odd perfect numbered proposal, the author wins and the game ends. This overrides everything where applicable.

<a name='64'/>

## #64

Add a new rule, %goodstein: Change the numbering of proposals in accord with the Goodstein sequence, starting with proposal #100.  The author of proposal #0 wins the game. This rule overrides other rules.

