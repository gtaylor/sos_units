Sands of Solaris units
======================

This repository contains all of the units used in Sands of Solaris.


Submitting units
----------------

* Download `Solaris Skunkworks`_
* Template something snazzy
* Save the unit and send the SSW file to kelvin@sandsofsolaris.com

Human and AI mech pools
-----------------------

Mechs are split up into two different pools:

* AI Pool (Only AI can use these units)
* Human Pool (Units are buildable/ownable by humans)

We are very flexible with what we let into the AI pool, as long as an AI could 
conceivably make good use of the unit. They can't switch ammo modes, manage heat as well
as a human, and they can't currently toggle special techs (ECM, Rotary/Ultra ACs).

The Human Pool mechs, on the other hand, are subjected to a much more rigorous review
process. We have to work hard to lessen power creep, and we don't want there to be
clear "best" and "worst" mechs.

Before starting work on your custom, decide whether you are aiming to submit a unit
to the AI pool or the human pool.

The SoS style
-------------

While it's unfortunate that we weren't able to use FASA mechs, there are some positives.
The power creep over time with the FASA units has been very pronounced. This makes sense
when set within the context of the greater Battletech universe, but we'd end up with
artificial tiers in a game like SoS. Rather than restrict players to certain tech
levels for certain matches, we'd like to just keep things open when possible.

What we'd like to do with SoS is avoid creating clear winners and losers in our human
pool mechs. We'd like all of our human pool mechs to be viable in their given role.
If we are successful, we'll have a good deal of variety in what our players are fielding.

One of the most important parts of keeping our unit power levels under control is
managing the usage of advanced techs. Put simply, any given unit should be *mostly*
lowertech, with a slight sprinkling of newtech. For example, perhaps you have an ERPPC
and some conventional laers. Or some ACs and an ELRM. What you won't see is a 
straight pulseboat, or TSM + XL + Super heavy + loads of armor/weapons. Or targeting
computers + pulse, or TC/LolPulse + C3i.

*We are looking for a tasteful blending of oldtech and newtech.*

Aside from the tech creep, the other important thing to manage is the unit's power level.
This is a very subjective thing to weigh, but if a submitted mech is better than all of the
others currently in its class, it's probably too much. Instead of trying to outperform
other units, aim to change playstyle instead. The player should have to choose units
based on utility and situation. There should never be a mech that the whole playerbase
chooses 100% of the time in a given role/weight class.

If in doubt, talk to Kelvin in-game. If a submitted unit is deemed inappropriate for the
human pool, it may be entered into the AI pool. It's also more than OK if I give you 
some feedback and you decide to re-work.

Custom unit guidelines
----------------------

These are still in a state of flux, but...

* No clantech.
* No ICE mechs.
* Don't go overboard with the advanced tech!
* I generally dislike 70+ tonners that go 6/8.
* See here for a full list of available weapons: https://github.com/gtaylor/btmux_template_io/blob/master/btmux_template_io/item_table.py
* No split crits.
* No quads.
* Tech level isn't important. Mix-and-match freely.
* **Make sure you pick Inner Sphere for Techbase**. Mixed and Clan techbases are both not accepted right now.
* The site is Solaris themed, so it's perfectly fine if your units are quirky or odd

.. _Solaris Skunkworks: http://www.solarisskunkwerks.com/
