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

## #2

Replace paragraph in %proposals, from
> If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since their last proposal, it may be failed without a vote.
to
> If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since their last open proposal, it may be failed without a vote.

<a name='3'/>

## #3

Edit %closing-proposals, changing
> All active players have cast a vote or abstained from voting on the proposal.
to
> All active players have cast a vote or abstained from voting on the proposal, and there are more than two active players.

<a name='4'/>

## #4

This proposal is incompatible with #2.

Edit %proposals, changing
> If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since their last proposal, it may be failed without a vote.
to
> If a player creates a proposal when they are the author of 10 currently open proposals, or when less than 10 minutes has passed since they last created a proposal, it may be failed at any time if it is open.

