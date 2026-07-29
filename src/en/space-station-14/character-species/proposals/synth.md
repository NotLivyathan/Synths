# Synth Species

| Designers | Coders | Implemented | GitHub Links |
|---|---|---|---|
| NotLivyathan | NotLivyathan | :x: No | TBD |

## Overview

This proposal covers Synths as a playable round-start species. Synths are a species of synthetic androids created by Vader-San.

Synths are a humanoid species that vaguely resemble reptilians in aesthetic. Although reminiscent of Reptilians, Synths easily manage to stand out, featuring expressive visors, vibrant color palletes, and an array of LED lights that provide them with a visually distinct, but inoffensive appearance. And their modular origins allow room for them to be very customizable.

## Background

Synths have always been a fairly popular species since their inception, and have managed to make appearances in multiple games thanks to the talents of very devoted creators. At least one even officially.

Despite this, and despite a definite interest among subsets of both communities, Synths have never existed in any serious capacity within Space Station 13 or 14. So far, multiple SS14 downstreams have added them as a playable species, to shockingly positive reception.

As such, the goal of this document is to introduce Synths to the broader SS14 community, and implement them in such a way that they provide interesting new (mechanical and roleplay) experiences to the players that would be interacting with them.

## Features/Design

Although similar to Reptilians in aesthetic, Synths share almost nothing in common with them. Nor do they share similarities with any of the other currently avaialble round-start species. Compared to other species, Synths could be considered mildly complicated, but should be easy to learn or understand at a glance, and most of the confusion should be isolated to medical treatment.

### Core Visual Elements

Synths are bipedal, featuring reptile-like heads and tails, visors that display the Synth's eyes, horn-like antennas, and an assortment of highly customizable status lights. Synths communicate at a vocal frequency that, conveniently, happens to be very similar to that which a standard Cyborg does. Albeit with room for replacement in the future. Similar to Reptilians, their tails protrude from their jumpsuits/hardsuits, but their digitigrade legs allow them to be easily distinguished from Reptilians. Synths tend to be tall and slender, but their sizes may vary based on personal preference or occupational requirements.

### Naming Convention

Synths lack a conventional naming convention, in that nothing necessarily doesn't work. Even Cyborg-like names and serial numbers could be considered normal or socially acceptable. As with appearance, whatever feels right to a Synth is right to that Synth.

### Special Features

#### Internal Batteries

Similarly to Cyborgs, Synths require power for their bodies to function. Unlike Cyborgs, however, their batteries are internal and cannot be removed without surgery, meaning upgrades are not currently be possible. Despite this, Synth chassis are better optimized and last longer without needing recharged.

If depleted, Synths will suffer the same effects as Cyborgs, slowing down as basic functions begin to fail.

Additionally, Synths feature a miniature bioreactor as part of their stomach, which processes organic matter to generate power and faciliate autonomous bodily repair, allowing nutriment to be consumed for charge.

#### Internal Nanites

Internal nanites allow them to passively recover from Brute and Burn damage over time at the cost of satiation. (Brute and Burn at 0.75 per tick, which translates to roughly 0.25 for each Brute damage type and 0.185~ for each Burn damage type, as actual healing would be 0.75 divided by 3 (for Brute) and 4 (for Burn).  Values can be further tweaked.)

Autonmous repairs are slow and quickly deplete a Synth's hunger, resulting in starvation if over-relied on, and will eventually stop if a Synth's bioreactor is starved. (Passive healing stops if hunger reaches <50 (starvation).)

#### Synth Bloodstreams

Synths contain fullerene, a carbon-based blood-like solution which assists their internal nanites in performing repairs. As their bloodstream depletes, autonomous repairs will slow down, and eventually stop completely once below 30% blood level.

As fullerene is carbon-based, Synths can consume carbon to restore depleted blood, similar to iron or copper for other species. In the event of an emergency, Synth blood packs can be crafted at a medical techfab for plastic and diamond.

Due to the complexity of their chassis, Synth bloodstreams are virtually inacessible through normal means, rendering injections impossible and oral administration required for metabolization. Needles and hyposprays will not work on Synths. (Consequentially, reagents ingested orally are 50% less effective than when injected into the bloodstream, resulting in slower, weaker application in Synths.)

#### Resistances

Synths are required to breathe, but will suffer Heat damage instead of Asphyxiation where breathing fails. Specifically what they breathe remains to be decided.

Exact effects of EMPs remain undecided, but could range anywhere between completely depleting a Synth's internal battery (which could be minimized with preemptive nutriment consumption to immediately begin recharging the battery on EMP), or an effect similar to a flash, where they're briefly disabled.

#### Central Computing Unit

Synths possess a CCU in place of an organic brain. Functionally, their CCU is very similar to a Cyborg's positronic brain, meaning their consciousness remains active despite the CCU being removed. CCUs can also be inserted into cyborg chassis without the need of a man-machine interface.

It remains to be decided if Synth CCU should be capable of speech or not.

#### Nanites

Nanites is a special new reagent that can be created through chemistry. It requires 5 Carbon, 5 Copper, 5 Fersilicite, 2 Hydrogen, 1 Oxygen, and 1 Sulfuric Acid, and can be synthesized using an electrolysis unit, resulting in 20 units of Nanites. 

Nanites function as the most effective means of treating injuries in Synths, effectively serving as their Omnizine, and even works on the dead. It heals them at a rate slightly higher than Omnizine, but comes with a dangerous OD if the dosage exceeds 10.5 units.

Additionally, organics suffer this OD regardless of the dosage, resulting in an undecided degree of injury, probably relative to Amatoxin or something. 
