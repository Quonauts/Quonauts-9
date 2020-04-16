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

## #6

This proposal is incompatible with #6.

<a name='7'/>

## #7

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

## #10

Add a rule "Winning" (%winning):
> Any player who successfully finishes construction of a death star wins the game.

<a name='11'/>

## #11

Define a new quantity named Points, with this description:
*** Points** are an arbitrary (positive integer) value which should generally be used as a reward/currency.

<a name='12'/>

## #12

Define a new quantity called Clay, with this description:
*** Clay** is a positive real value which is used to build things

<a name='13'/>

## #13

Add a new section Voting Power (%voting-power) that is a subsection of %quantities:
> Voting Power is initialized to one. Whenever a player votes on a proposal or poll, that player's vote is worth a number of votes equal to that player's Voting Power.

<a name='14'/>

## #14

This proposal depends on propsoal #11.
Create a new rule within %Quantities% named "Obtaining Points". This rule section should be updated whenever a new method is created.
> When a proposal is passed, its author obtains 2 points and the person who enacted it obtains 1, if this is applicable.

<a name='15'/>

## #15 — Deleted

<a name='16'/>

## #16

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

## #17

Make a new rule section named "Cabals" below all other rules:
> A cabal is defined as a collection of 2 or more players. A player may belong to only one cabal, and cabals are part of the game state. The creator of a cabal is the owner, and may invite other players into a cabal or kick them out. Cabals must be named.
> 
> All members of the Dramly cabal win the game. This applies at all moments in the game.

<a name='18'/>

## #18

Depends on #11.
Add a rule "Winning" (or append to it if it already exists):
> The first player to reach 100 points wins the game.

<a name='19'/>

## #19

Depends on #18.

Add a new rule "The end" (%the-end) after %winning:
> The game ends when one or more players have won.

