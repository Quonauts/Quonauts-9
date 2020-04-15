# Quonauts 9: Quorantine — Rules

## Table of contents

* [**1. Meta rules**](#meta-rules)
    * [**1.1. Glossary**](#glossary)
    * [**1.2. Accuracy**](#accuracy)
    * [**1.3. Precedence**](#precedence)
    * [**1.4. Forbidden actions**](#forbidden-actions)
    * [**1.5. Rule violation polls**](#rule-violation-polls)
    * [**1.6. Timezones**](#timezones)
    * [**1.7. Bots**](#bots)
    * [**1.8. Style conventions**](#style-conventions)
        * [**1.8.1. Content**](#content)
        * [**1.8.2. Headers and tags**](#headers-and-tags)

## <a name='meta-rules'/> Meta rules

This section details how the rules are to be applied to the game.

### <a name='glossary'/> Glossary

The definitions for terms listed here take precedence over their normal English meanings, however any terms defined in a specific section of the rules override these in the section in which they are defined and its subsections. A section may also define terms for use in the whole document.

* **The Game**: The instance of Nomic governed by these rules.
* **Game Channel**: Any text or voice channel listed under the "Game Channels" category of the Discord server.
* **Game Action**: Any modification of the game state.
* **Game State**: Every current rule; every non-deleted proposal and any votes on it; every poll and any votes on it; and every message or reaction in any game channel.
* **The Rules**: The rules of the game, which are described by this document.
* **Section**: A part of the rules contained under one header. Unless otherwise specified, this does not include its subsections.
* **Subsection**: A section contained within another another section.
* **Clause**: A single statement in the rules.
* **Player**: Any participant of the game.
* **Active Player**: Any player who has performed a game action in the preceding 72 hours, and is a member of the Discord server.
* **Inactive Player**: Any player who is not an active player.

Whenever the word "if" is used in the rules, it is to be interpreted as "if and only if".

### <a name='accuracy'/> Accuracy

This document is not guaranteed to always be up-to-date as the game rules are modified, however it is the duty of all players to keep this document accurate as game rules are modified. Where this document disagrees with the game rules, players must follow the game rules as they are, rather than their description in this document.

### <a name='precedence'/> Precedence

In the case of a contradiction between clauses, the following criteria are to be considered in turn until a clear determination can be made as to which clause takes precedence:

* If precedence is specified in the relevant rules and is non-contradictory, follow the instructed precedence.
* The clause which appears last in the rules takes precedence.

### <a name='forbidden-actions'/> Forbidden actions

Unless explicitly stated in the rules, all game actions are forbidden.

Any game action that is forbidden (a "rule violation") is considered void and does not modify the game state; the action and its consequences are to be reverted.

### <a name='rule-violation-polls'/> Rule violation polls

If a player ("the accusing player") believes that another player ("the accused player") has violated the rules, the accusing player may conduct a poll, called a "rule violation poll" or "RVP", to determine whether a forbidden action was performed. The poll must clearly state it is a rule violation poll, and must specify the accused player and what sections of the rules they allegedly violated.

In a rule violation poll, the following reactions are permitted:

* 🇦: In favour of the poll, and in favour of a strike.
* 🇧: In favour of the poll, but against of a strike.
* 👎: Against the poll, and against a strike.

In a rule violation poll, any votes cast by the accused player are ignored.

If the poll passes, the rule violation and its consequences must be reverted.

If the poll passes and more players are in favour of a strike (🇦 reactions) than against (🇧 and 👎 reactions), the accused player may not perform any game actions for the next 24 hours.

### <a name='timezones'/> Timezones

Unless otherwise specified, all times and dates are specified with respect to UTC.

### <a name='bots'/> Bots

Certain game functions may be performed automatically by automated "bots"; the behavior of such bots is not governed by the rules, and any function that bots may perform should be feasible, even if inconvenient, to do manually.

### <a name='style-conventions'/> Style conventions

This section and its subsections describe grammatical and stylistic conventions used throughout this ruleset.

Any player may edit the rules to conform to these style conventions. Edits made this way must otherwise be minimal; i.e. they may not change wording or meaning. Note that the meaning of other, linked rule sections must not be changed by such an edit.

#### <a name='content'/> Content

* All rules should be written in English using proper English grammar and spelling. American and British English spelling are both acceptable.
* Where applicable, rules should be written using gender-neutral language, with "they/them/their" as a third-person pronoun, both singular and plural.
* Sentences should be separated by a single space.
* Paragraphs should be separated by a blank line.
* Each paragraph or list element must be shorter than 1000 characters.
* Rules may not contain invisible characters besides newlines, normal spaces, and (in special cases) tabs. Non-ASCII characters should be used sparingly.
* Double quotes should be preferred instead of single quotes. ASCII-compatible straight quotes should be used instead of "smart" quotes.

#### <a name='headers-and-tags'/> Headers and tags

* Each section must have a header and a tag.
* Headers must use [sentence case](https://en.wiktionary.org/wiki/sentence_case), and must be a short, succinct word or phrase (not a complete sentence) describing the section.
* A section tag must be a string of text begin with a lowercase letter, end with either a lowercase letter or a number, and may contain only lowercase letters `a`-`z`, digits `0`-`9`, and hyphens `-`.
* A rule's tag should resemble its header.
* Tags must be unique; no two rule sections may have the same tag.

