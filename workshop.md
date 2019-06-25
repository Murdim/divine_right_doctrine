# Divine Right: Coronation for non-Catholics

**Extends Catholic-style coronation ceremonies and priest nomination to non-Catholic Christians, reformed Pagans, and/or Random World religions, based on game rules.**

***Localised in English and French.***


## Divine Right doctrine

This new doctrine allows Pagans and randomized religions to access the features of this mod.

It is incompatible with Temporal leadership, for both thematic and gameplay reasons. Due to a missing check in the AI's code, only players are allowed to pick it during reformation.

A Random World setting has been added to allow or forbid Divine Right to randomly-generated religions. It is is unavailable for Catholics, Fraticelli and Muslims, and will never be picked by unreformed Pagans.

## Coronation

The "Coronation Ceremony" decision and its associated event chain have been replicated and adapted for feudal Kings and Emperors of non-Catholic religions.

If their religion uses coronation, non-viceroyal feudal rulers of King or Emperor tier will have access to this decision. They will need to go through the ceremony in order to unlock the mod's other features and avoid "uncrowned" penalties. These same rulers will be treated as crowned by default if their religion does not use coronation.

In contrast to the Pope, religious heads grant the same *weaker* version of the Crowned trait as powerful priest vassals, with only minor differences in the event chain. In return, they are not as demanding as the Pope, though they might still ask for independence under certain circumstances.

By default, this feature is enabled for both **Christians** (except in Random Worlds) and religions with the Divine Right **doctrine**.

## Priest Nomination

Crowned rulers (see above) can use the "Nominate Priest" action on a single member of their court of the appropriate religion, gender and marital status.
 - If an independent religious head exists, this works similarly to the "Nominate Bishop" action available to Catholic rulers with Papal investiture.
 - If the religion has no head, the lower clergy may judge the candidate to be unworthy if their personal score is lower than 20.
 - Finally, both checks will be applied if the religious head is wicked, the sponsor's vassal, or (sometimes) compromised in some other way.

After the death of a direct theocratic vassal, the liege will get the option to have their candidate inherit their titles. They incur a soft, stacking, acceptance-based delay before they are allowed to nominate a new priest: 5 years for a Baron-tier theocracy, 8 for a County, 13 for a Duchy. This delay is increased by one year for every occasion they have chosen to ignore.

Cancelling a nomination can be done by decision or through an event option. Moreover, a candidate can be disqualified if they leave the court, convert away, are excommunicated, and so on. Regardless of circumstances, a cancelled nomination also adds a one-year delay.

By default, this feature is only enabled for religions with the Divine Right **doctrine**.

## Homage

Shortly after the death of a powerful feudal vassal (Duke or King-tier), their primary heir is expected to pay homage to their liege.

Rulers gain prestige from receiving homage and lose it from being denied it. The relationship between liege and vassal will also be impacted.

This event chain was actually recovered from the base game's files: a bug in its initial on-death trigger prevented it from working correctly. The mod simply re-implements the first few steps of the chain in order to make it functional and adapt the religious restrictions.

This feature is **disabled** by default.

## Compatibility

This mod does not replace any file from the main game. It should be compatible with future versions as well as most other mods.

## Links

GitHub repository: <https://github.com/Murdim/divine_right_doctrine>
Paradox Forums: <https://forum.paradoxplaza.com/forum/index.php?threads/mod-divine-right-coronation-priest-nomination-for-non-catholics.1193911>
