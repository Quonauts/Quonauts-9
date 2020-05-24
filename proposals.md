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

## #56 — Passed

Add rule "Opinion Polls" as subrule of %polls:
> Players may conduct polls to informally gather opinions about any game relevant topic, called "opinion polls".
> 
> An opinion poll may only be created if no other opinion poll by that player is currently open. By default, the allowed reactions of an opinion poll are thumbsup and thumbsdown, but the opinion poll may specify different allowed reactions for itself.

<a name='57'/>

## #57 — Failed

Add a quantity called "Worship"
At any time, if they have not in 12 hours, a player may worship heavpoot to gain one Worship.

<a name='58'/>

## #58 — Failed

Add a new rule, %winning:
> All players win the game. The game does not end.

<a name='59'/>

## #59 — Failed

Add a new rule, %primes, under %quantities:
Upon the legal passing of a prime-numbered proposal, the author gets an additional point.

<a name='60'/>

## #60 — Failed

Add a new rule %composites, under %quantities:
Upon the legal passing of a composite-numbered proposal, the author gets an additional point.

<a name='61'/>

## #61 — Passed

Add a new rule %perfects, under %quantities:
Upon the legal passing of a perfect numbered proposal, the author gets an additional point.

<a name='62'/>

## #62 — Passed

Add a new rule, %tree, under %quantites:
Upon the legal passing of a proposal of number TREE(n) for any n, the author gets points equal to the number of the proposal

<a name='63'/>

## #63 — Passed

Add a new rule %odd-perfects, under %quantities:
Upon the legal passing of an odd perfect numbered proposal, the author wins and the game ends. This overrides everything where applicable.

<a name='64'/>

## #64 — Failed

Add a new rule, %goodstein: Change the numbering of proposals in accord with the Goodstein sequence, starting with proposal #100.  The author of proposal #0 wins the game. This rule overrides other rules.

<a name='65'/>

## #65 — Passed

stop it, you muffins

<a name='66'/>

## #66 — Failed

__ __

<a name='67'/>

## #67 — Failed

@everyone

<a name='68'/>

## #68 — Passed

.,,,,,,,,,,............,...........,.........,,,nnnnnnnnn897667576586tgghcgfcgfcfhcjrye5y4w365wesfgsxdxxcvbvc 65 6445e3 45mdjur4deckigftr6jkuftrtvgjð” ̉fr mjutr5em rf bvf m
Create a new rule named iuashipg8f796765ugtjjjjjjfttttttttttttttttttttttttttttttytftyighf:
wwei is a ajskkfhjkkkkkkkkk8799999999998797898533243524333333333333333333332rrrrrrrrrrrrfv frv frv fr vfrv frv
All players are to be considered adfojpio455u345u34. osdfhkzsdhfhdkflgjsdhf is to be considered part of the game state. Gibson is considered to be part of the first state of america (in alphabetical order). jjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjhhhhhjkjjjjjjjjjjjjjjjjjj8979799879879799999999999999999999999999999999999999999999777777777979797979ninesevensevensevenninenine9979797999999999999

111111¹¹¹¹¹¹¹¹¹¹¹111111111111¹111¹¹¹1¹¹1111111¹11¹11¹¹11¹11¹12aaaaaa
boredom
aaaa

bored
anyone want to play minecraft lol

<a name='69'/>

## #69 — Failed

🖲️

<a name='70'/>

## #70 — Failed

Add a new rule, %ruley-mcruleface, under %quantities:
any player with less than zero points loses the game. The game does not end.

<a name='71'/>

## #71 — Failed

Add a new rule, %ruley-mcruleface, under %quantities:
any player with over 1000 points wins the game. The game does not end.

<a name='72'/>

## #72 — Failed

reopen Proposal #72, then fail a random proposal, overriding any rule stating you cannot do so.

<a name='73'/>

## #73 — Failed

Reopen Proposal #73 and give everyone who abstained on it 1 point (see %quantities).

<a name='74'/>

## #74 — Failed

Reopen proposals #73 and #74 and give everyone who abstained on either 1 point.

<a name='75'/>

## #75 — Failed

Change %<#700035894538928229> to:
> Players may post any messages to <#700035894538928229> as longs as said messages contain none of a, e, i, o, or u.

<a name='76'/>

## #76 — Failed

Reopen proposals #73, #74, and #76, and give everyone who abstained on at least one of them 1 point.

<a name='77'/>

## #77 — Failed

Reopen proposals #73, #74, #76, and #77, and give everyone who abstained on at least one of them 1 point.

<a name='78'/>

## #78 — Failed

Reopen proposals #73, #74, #76, #77 and #78, and give everyone who abstained on at least one of them 1 point.

<a name='79'/>

## #79 — Failed

Reopen proposals #73, #74, #76, and #79 and give everyone who abstained on or voted against at least one of them one point.

<a name='80'/>

## #80 — Failed

Reopen proposals #73, #74, #76, #77, #78, and #79, and give everyone who abstained on at least one of them 1 point.

<a name='81'/>

## #81 — Failed

Remove the following clause from #land-actions:
> After a player makes an action, they must wait 2 hours before performing another action.

<a name='82'/>

## #82 — Failed

Append to %land-actions:
> A player may do no more than 4 land actions per 24 hours.

<a name='83'/>

## #83 — Failed

Append to %land-actions:
A player may do no more than 400 land actions per 24 hours.

<a name='84'/>

## #84 — Failed

Add a new banana (note: not a rule): Quonauts 4.5 ends immediately

<a name='85'/>

## #85 — Failed

change all mentions of "rules" to "bananas" in the rules. Change <#700035968467599442> to #bananas.

<a name='86'/>

## #86 — Failed

Append to %odd-perfects:
Other conditions for a rule to go under the same procedure as mentioned previously are the number never reaching 1 in its Collatz-iteration trajectory and it being a negative number.

<a name='87'/>

## #87 — Failed

Proposal #83
Append to %land-actions:
A player may do no more than 4e529 land actions per 24 nanoseconds.

<a name='88'/>

## #88 — Failed

fail this proposal

<a name='89'/>

## #89 — Failed

Append to %land actions:
A player may do no more than Graham's number actions per planck-time.

<a name='90'/>

## #90 — Failed

Reopen proposals #73, #74, #76, #77, #78, #79, #80, and #90, and give everyone who either voted on or abstained from at least one of those proposals one point.

<a name='91'/>

## #91 — Failed

Call this proposal #100 and pretend that the numerical quantities 91-100 exclusive do not exist. Any action which might associate a quantity with numbers in this range should be denied.

<a name='92'/>

## #92 — Failed

RRRRR¶¶¶¶¶

<a name='93'/>

## #93 — Failed

Append to %land-actions:
A player may do no more actions per duck.

<a name='94'/>

## #94 — Failed

Add a new rule, %ambiguous-wording
> If any proposal is similar enough to #68, according to at least three people, it may not be enacted. However, keep rule 8. (To prevent it from being used again and not being funny)

<a name='95'/>

## #95 — Failed

Add a new rule 8.1 (%%iuashipg8f796765ugtjjjjjjfttttttttttttttttttttttttttttttytftyighf-1):
> Yes (I would like to play Minecraft).

<a name='96'/>

## #96 — Failed

For every request made not vital to the game, you lose a point.

<a name='97'/>

## #97 — Failed

quonauts is dead, long live quonauts
Add a new rule named %spicy:
Every UTC day, <@!160279332454006795> must ping every member in the server in <#700035894538928229>.

<a name='98'/>

## #98 — Failed

quonauts is alive, long die quonauts
add a new rule named %minty:
every UTC day, every member *may* ping <@!160279332454006795> in <#700035894538928229>

<a name='99'/>

## #99 — Failed

add a new rule %zfc.
add a new rule, %extensionality, under %zfc:
∀x∀y[∀z(z∈x⇔z∈y)⇒x=y]
add a new rule, %regularity, under %zfc:
∀x[∃a(a∈x)⇒∃y(y∈x∧¬∃z(z∈y∧z∈x))].}
add a new rule, %specification, under %zfc:
for any formula phi:
∀w\_1,...,w\_n∀A∃B,∀x(x∈B⇔[x∈A∧phi(x,w\_1,... ,w_n,A)])}
add a new rule, %pairing, under %zfc:
∀x∀y∃z((x∈z)∧(y∈z)).}
add a new rule, %union, under %zfc:
∀F∃A∀Y∀x[(x∈Y∧Y∈F)⇒x∈A].
add a new rule, %replacement, under %zfc:
for any formula phi:
∀A∀w\_1∀w\_2...∀w_n[∀x(x∈A⇒∃!y,phi)⇒∃B∀x(x∈A⇒∃y(y∈B∧phi ))]}
add a new rule, %infinity, under %zfc:
∃X[Ø∈X∧∀y(y∈X⇒S(y)∈X)]
add a new rule, %powerset, under %zfc:
∀x∃y∀z[(∀w(w∈z⇒w∈x))⇒z∈y].
add a new rule, %choice, under %zfc:
∀X[Ø∉X⇒∃f:X↦⋃X   ∀A∈X,(f(A)∈A)]

<a name='100'/>

## #100 — Failed

quonauts is dead, long live quonauts
Add a new rule named %spicy:
Every UTC day, @g must ping every member in the server in <#700035894538928229>.

<a name='101'/>

## #101 — Failed

Add a new rule, %mints:
No rules named %spicy may be proposed or added to the rules. Any rules by that name in the rules are retroactively deleted.

<a name='102'/>

## #102 — Failed

Add a new rule, %hot:
No rules named %mints may be proposed or added to the rules. Any rules by that name in the rules are retroactively deleted.

<a name='103'/>

## #103 — Failed

Add a new rule, %water:
No rules named %hot may be proposed or added to the rules. Any rules by that name in the rules are retroactively deleted.

<a name='104'/>

## #104 — Failed

Pass or fail all the things in this channel already

<a name='105'/>

## #105 — Failed

Officially declare this game as dead already.

<a name='106'/>

## #106 — Failed

Sinthorion wins the game. The game ends.

<a name='107'/>

## #107 — Failed

All people who voted for this, and sinthorion, win the game. The game ends.

<a name='108'/>

## #108 — Failed

the game is only failing because youre doing things like this

<a name='109'/>

## #109 — Failed

I agree

<a name='110'/>

## #110 — Failed

Add a new rule under %<#700035956522090596> called %no-conversation:
> the <#700035956522090596> channel is not to be used for conversation.

<a name='111'/>

## #111 — Passed

I disagree with #110.
Remove rule %no-conversation, if it exists.

<a name='112'/>

## #112 — Failed

I disagree with #111.
Retroactively revert #111, if it passed

<a name='113'/>

## #113 — Failed

I disagree with #111.
Retroactively revert #111, if it passed; otherwise fail it

<a name='114'/>

## #114 — Failed

Treat all currently open proposals as though they are two days old and pass or fail them accordingly. This is a wildcard proposal if there ever was one

<a name='115'/>

## #115 — Failed

I disagree with #110.
Remove rule %no-conversation, if it exists.

<a name='116'/>

## #116 — Failed

Retroactively pass #114

<a name='117'/>

## #117 — Failed

This proposal applies retroactively, i.e simulate the entire game and the players' descisions again, but with this proposal always being passed.

<a name='118'/>

## #118 — Failed

Iff proposal #117 passes but #116 does not, Moooosey gains one land (seee %quantities). Iff proposals #117 and #116 both pass, everyone who abstained on this proposal get one land. Else, all active players get two land

<a name='119'/>

## #119 — Failed

If there is no quantity named "passes (119)" in %quantites, add a new quantity called "passes (119)", starting at 0.

<a name='120'/>

## #120 — Failed

If there is no quantity named "passes (120)" in %quantities, add a new quantity called "passes (120)", starting at zero. If there is no rule named %proposal-120, add a new rule called %proposal-120, under %quantities, with the following content:
> the quantity "passes (120)" can only be changed by action via the 120th proposal

Increment the quantity passes (120), for the player <@!421060058009305088>. Unless passes(120) exceeds 5 for any player, reopen proposal #120./

<a name='121'/>

## #121 — Failed

Create a rule (%tap-to-edit) under %land-movement:
> All "ajskkfhjkkkkkkkkk8799999999998797898533243524333333333333333333332rrrrrrrrrrrrfv frv frv fr vfrv frv"s must roll a d6 before performing any land action. The value rolled is their speed for their next movement action.
> 
> Choose a bottom caption

This is why I don't propose anymore

<a name='122'/>

## #122 — Failed

Pass a random proposal. Reopen proposal #122.

<a name='123'/>

## #123 — Failed

Fail a random open proposal.

<a name='124'/>

## #124 — Failed

Reopen Proposal #124

<a name='125'/>

## #125 — Failed

If more than 100 proposals in a row fail, the first person to pass a new proposal gains 5 points

<a name='126'/>

## #126 — Failed

give sarp 5 points for such a good idea

<a name='127'/>

## #127 — Failed

Create a new rule "Winning" (%winning) in %root:
> When one or more players have reached 100 points, they win and the game ends.

<a name='128'/>

## #128 — Passed

Create a new quantity goods, which can be traded.
Create a new rule "Producing goods" (%producing-goods) in %land-actions:
> As a land action, a player may gain a number of goods equal to the number of land they have claimed.

<a name='129'/>

## #129 — Failed

anyone who votes against this proposal loses all their points

<a name='130'/>

## #130 — Failed

This proposal depends on #128.

Create a new quantity ducks.

Replace the text of %obtaining-points with:
> When a proposal is passed, its author obtains 2+n points and the person who enacted it obtains 1+n, if this is applicable, where n is the number of ducks both players have (combined).

Create a new quantity bread. Thirty goods may be traded for one bread.

Create a new rule "Feeding ducks" (%feeding-ducks) in %land-actions:
> A player residing in a land tile with land-x equal to double land-y may spend 1 bread to gain one duck. Each player may only do this once per applicable tile.

<a name='131'/>

## #131 — Failed

give sarp -5 points for failing to follow the proper rule addition format

<a name='132'/>

## #132 — Failed

Anyone who voted against Proposal #129 loses all their points

<a name='133'/>

## #133 — Failed

Anyone who votes against #129 or #132 gains one point. That's plus two points for voting against both.

<a name='134'/>

## #134 — Failed

Pass proposal #135.

<a name='135'/>

## #135 — Failed

Add a new rule %haha-you-should-have-been-more-careful, under %passing-proposals:
Any rule proposed by <@!421060058009305088> is automatically passed.

<a name='136'/>

## #136 — Failed

Replace the following in %passing-and-failing-proposals:
> When a proposal is closed, it passes if it has more votes in favour than against; otherwise, it fails.
With:
> When a proposal is closed, it fails.

<a name='137'/>

## #137 — Failed

Replace the following in %passing-and-failing-proposals:
> When a proposal is closed, it passes if it has more votes in favor than against; otherwise, it fails
With:
> When a Proposal is closed, it passes if it has more votes in favor than against; otherwise, <@!160279332454006795> chooses whether it passes or fails.

<a name='138'/>

## #138 — Failed

This proposal depends on #130:
Add a new rule %reversibility:
> A player residing in a land tile with land-x equal to double land-y may spend 1 duck to gain one bread, resetting the amount of times they may trade bread for ducks on that tile.

<a name='139'/>

## #139 — Failed

Add a new rule %ignore:
> Anybody who violates this rule in a turn gains 1 point.

<a name='140'/>

## #140 — Failed

Reopen and pass proposal #140

<a name='141'/>

## #141 — Failed

Fail proposal #141.

<a name='142'/>

## #142 — Failed

æ?

<a name='143'/>

## #143 — Passed

Create a new rule "Winning" (%winning) in %root:

> When one or more players have reached 50 points, they win and the game ends.

<a name='144'/>

## #144 — Failed

add a new quantity, cookies. Three goods may be exchanged for a cookie.

<a name='145'/>

## #145 — Passed

Sinthorion's movement from (-1,-1) to (999,999) is retroactively legalised as unique special case.

<a name='146'/>

## #146 — Failed

Add a new rule, %speakingofspecialcases: Moooosey can legally pass any proposal. This overrides content in %passing-proposals.

<a name='147'/>

## #147 — Failed

Add this clause to rule %land-movement:

> In case of illegal movement which is caught after the fact, the person who illegally moved should be rolled back to their playing state before they made their movement. All land the person claimed after the movement is automatically unclaimed and the person is transported to their coordinates before the illegal movement. This punishment overrides any other rules about land.

<a name='148'/>

## #148 — Failed

Add a new rule, %decree: By decree of the holy 148th proposal, Sinthorion wins the game.

<a name='149'/>

## #149 — Passed

Add a rule %never-another-sinthorion
> As Sinthorion has already won many games undeservedly, whenever Sinthorion would win in this game, another player randomly chosen from the active players with the least previous Quonauts victories wins instead.

<a name='150'/>

## #150 — Failed

This proposal depends on #149.
Add a new rule %everyonewins:
> Sinthorin wins until everyone else does.

<a name='151'/>

## #151 — Failed

If this proposal is prime, the submitter of the next prime proposal wins the game.

<a name='152'/>

## #152 — Passed

Remove the following clause from %glossary:
> Whenever the word "if" is used in the rules, it is to be interpreted as "if and only if".

At the time of this proposal's passing, replace all occurences of the word "if" in the rules with the words "if and only if".

```//We might want to use "if" by it's normal definition instead of as "if and only if"```

<a name='153'/>

## #153 — Passed

Replace the contents of %polls (https://discordapp.com/channels/547529950404542476/700035968467599442/703303637165801553) with:
> A poll is a means of gathering the opinions of players on an issue. A poll is created by sending a message in the <#700035979792089208> channel, provided a rule permits the poll's creation.
> 
> Players may vote on a poll by reacting to it with a certain reaction (except for 🔐), as specified in the rule permitting the poll's creation. No unspecified reactions are permitted. The reaction 🔐 does not represent a vote.
> 
> The player that posted a poll may edit it freely, as long as such edits do not change the meaning/intent of any existing reactions to the poll.
> 
> In the event of a conflict, the following parts of this section never take precedence over a rule that allows a poll to be created.
> 
> Each player may cast only one vote on a given poll, all votes by a player who voted for multiple options are ignored.
> 
> A player may close a poll when one or more of the following conditions is met:
> 
> • The poll is at least 24 hours old.
> • All active players have voted on the poll, and there are more than two active players.
> • A majority of active players have voted in favour of or against the poll, and there are more than two active players.
> 
> Whenever a player closes a poll, that player must react to the poll with 🔐, signifying that it is closed.
> 
> When a poll is closed, no more votes may be cast on it, and it may not be edited. If more active players have voted in favour of the poll than against, the poll passes, otherwise, it fails.

For all polls that have been closed previous to the enacting of this proposal, the player who enacted this proposal will react to those polls with 🔐 to signify that they are closed.

<a name='154'/>

## #154 — Passed

This proposal depends on Proposal #152.
In %polls, %proposals, and %conflict-resolution, replace all occurences of `if and only if` with `if`.
In %rule-violation-polls, replace the last two occurences of `if and only if` with `if`.

<a name='155'/>

## #155 — Passed

Add a new rule, %stop-pinging-us-man:
> <@151149148639330304> is disallowed from pinging other players in <#700035979792089208>

<a name='156'/>

## #156

If Proposal #155 has not passed, replace its contents with the following:
> Add a new rule, %stop-pinging-us-mans:
> > @everyone is disallowed from pinging other players in <#700035979792089208>.
> 
Otherwise, rename rule %stop-pinging-us-man to %stop-pinging-us-mans and replace its contents with the following:
> @everyone is disallowed from pinging other players in <#700035979792089208>.

<a name='157'/>

## #157

Add a new rule %joint-dictatorship:
> <@!160279332454006795>, <@!309787486278909952>, and <@!216295379895844865> are not allowed to make game actions, as they can make any rule edit they want by editting <#556288440740741177>, which controls Quonauts game rules.

<a name='158'/>

## #158 — Failed

Add a new rule, %poll-reform:
The author of a rule violation poll cannot vote on the poll until at least one other person has voted on it

<a name='159'/>

## #159 — Failed

Add a new rule, %minor-infraction-revival-protection:
The author of a rule violation poll regarding an action at least 120 hours (five days) old cannot vote on the poll until at least one other person has voted on it.

<a name='160'/>

## #160 — Passed

Append to %proposals:
> When a proposal passes or fails, it closes.

<a name='161'/>

## #161 — Passed

Move %odd-perfects to be a subsection of %perfects.

<a name='162'/>

## #162

Delete rule %proposal-9 and close and fail Proposal #9.

<a name='163'/>

## #163

Remove the following from %land-actions:
> After a player makes an action, they must wait 2 hours before performing another action.

<a name='164'/>

## #164

Replace the contents of %producing-goods with the following:
> As a land action, a player must gain a number of goods equal to the number of land tiles they have claimed.
>
```javascript
//Players cannot claim "land", the infinite square lattice.
```

<a name='165'/>

## #165

Add a new rule, %soundofspoutingspamprotection: <@151149148639330304> cannot post in <#700035979792089208> more than once every two minutes.

<a name='166'/>

## #166 — Passed

Add the following phrase to %rule-violation-polls:
> In a rule violation poll, the author cannot vote.
(This is so that spamming an excessive amount of bogus RVPs and voting yes strike on all of them doesn't cause problems for the wrongly accused player)

<a name='167'/>

## #167 — Failed

Reopen proposal #99

<a name='168'/>

## #168 — Passed

Replace the following in %dependency-resolution:
> A proposal may state that it depends on other proposals, meaning that proposal will fail if any proposal it depends on passes.
with:
> A proposal may state that it depends on other proposals, meaning that proposal will fail if any proposal it depends on fails.

<a name='169'/>

## #169 — Passed

Replace all occurrences of "50" in %winning with "100".

<a name='170'/>

## #170

Change %winning from
> When one or more players have reached 50 points, they win and the game ends.
to
> When one or more players have reached 50 points, the player(s) with the second most points win and the game ends.

<a name='171'/>

## #171

thiSß PROPOALS ÐEÞENÐS ON proposal 1711111111111111111111111111111!!!!!!!!!!!!!!!!!!!!!¡!!!!!!!!!!!¡!!!!¡!!¡!!!!!!!!!!!!¡!!¡!!!!!!!¡!!111
Create a new rule named ðß&ÆN&ŁÐĦđ³]¶}ÆŁ°E®Ł£°®±£°¼±⅛£¿°§ªÐNª§&ÐN>ª&>Nª©&©™±ΩN⅛±NªN&Æ§ÐN§&NN ©&<>©N£±E®N¡±:
All g are to be considered ðæßæđð. aæaaaaaaaææaaaaaaææaaaæaaaæaaæaaææaaæaaææææææææææææææææææææææææææææææææææææææææææææææææææææææææææææææææææææææææææææææææ
BOREDOM¡!!!¡!!!!!You wouldn't pass a spam proposal TWICE, would you..?
You wouldn't pass a spam proposal TWICE, would you..?
You wouldn't pass a spam proposal TWICE, would you..?
You wouldn't pass a spam proposal TWICE, would you..?
You wouldn't pass a spam proposal TWICE, would you..?
You wouldn't pass a spam proposal TWICE, would you..?
You wouldn't pass a spam proposal TWICE, would you..?
You wouldn't pass a spam proposal TWICE, would you..?
You wouldn't pass a spam proposal TWICE, would you..?
You wouldn't pass a spam proposal TWICE, would you..?
Gibson is to undergo immediate cardiac arrest, along with regular arrest.

<a name='172'/>

## #172

Add this to %passing-and-failing proposals:

> All proposals with no content which is legible in English and affects the game state should be failed.

<a name='173'/>

## #173

[REDACTED]

<a name='174'/>

## #174 — Deleted

<a name='175'/>

## #175

Replace the following in %polls:
> When a poll is closed, no more votes may be cast on it, and it may not be edited. If more active players have voted in favour of the poll than against, the poll passes, otherwise, it fails.
with:
> When a poll is closed, no more votes may be cast on it, and it may not be edited. If more players have voted in favour of the poll than against, the poll passes, otherwise, it fails.

<a name='176'/>

## #176

Replace the following in %passing-and-failing-proposals:
> The player that authored a proposal may fail it at any time.
with:
> The player that authored a proposal may fail it at any time if it is open.

<a name='177'/>

## #177

Append the following to %obtaining-points:
> When a player fails a proposal, if that player is not the author of that proposal, that player obtains 1 point.

<a name='178'/>

## #178

If proposal #176 has passed, retroactively revert it. 
Add the following to %passing-and-failing-proposals:
> The state of a proposal may not be directly changed from passed to failed, or directly from failed to passed.

<a name='179'/>

## #179

Add a new rule named æß:
The proposals channel may not be posted in. This overrides all other rules

<a name='180'/>

## #180

Remove the rule called æß, if it exists.

<a name='181'/>

## #181

Add a rule named heav-bad:
> Heavpoot#5118 and all accounts he creates automatically obtain a permanent "Rule Offender" role immediate upon this rule's creation or account creation. This overrides all other rules.

