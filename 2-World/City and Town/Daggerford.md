---
NoteIcon: settlement
tags:
  - Category/Settlement
Community-Size: Outpost
Alignment: Chaotic Evil
Government: Autocracy
type: Settlement
politics: Lordship
leader: Isabelle lesla
guildsgroups:
  - Thieves Guild 1
  - Cult 1
  - Guiled 1
region:
  - This area
  - Of this area
size: Small city
population: 1200
commonraces:
  - Humans
  - Dwarves
  - Halflings
religion:
  - Amaunator, Chauntea, Lathander, Tempus, Tymora
exports:
  - Furs, garments
imports:
  - Green Wood
---



> [!infobox]
> # `=this.file.name`
> ![[Flag - Daggerford.webp]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Travel (`=[[Travel Calculator]].HoursPerDay` hrs per day)
> ###### [[Travel Calculator]]  / [[Exhaustion]]:  `=[[Travel Calculator]].ExhaustionLevel`
> Destination |  Travel Days  |
> ---|---|
> [[Waterdeep]] | 🕓: `VIEW[round((120* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> ###### Politics
> Type |  Stat |
> ---|---|
> Govt Type | `=this.politics` |
> Ruler | `=this.leader` |
> Defense | `=this.defences` |
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces` |
> Temples | `=this.religion`  |
> ###### Commerce
> Type |  Stat |
> ---|---|
> Exports | `=this.exports` |
> Imports | `=this.imports` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> ```dataview
table WITHOUT ID link(file.name) AS "Group", link(Leader) AS "Leader"
where contains( PrimaryHome, this.file.name)


# `=this.file.name`
## Overview
Placeholder
## Map
![[Map - Daggerford.webp]]




## Notable NPCs
Placeholder

## Profile
Placeholder

## Story
Placeholder

## Points of Interest
Placeholder

## Valuables
Placeholder

## Internal Relationships
Placeholder

## Outward Relationships
Placeholder

## Background
Placeholder

## Additional Details
Placeholder

