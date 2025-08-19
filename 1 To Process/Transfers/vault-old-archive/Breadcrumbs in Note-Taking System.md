---
id: f2de6f2b-6607-4d11-adcb-2db640508483
author: Ben Jendyk
created: 2023-02-13 02:10
archived: Sunday, 26 January 2025, 05:30:25 UTC+01:00
last_modified: 2023-10-21 05:49
aliases: []
tags: [access/archived] 
---

# Breadcrumbs in Note-Taking System

## Definition

#a/rC 

Breadcrumbs ist erstens der Name eines Plugins in Obsidian und beschreibt zweitens eine Art, Notes in einer hierarchischen Weise miteinander zu verlinken.  

## Exposition

#a/rC

The structure or method of Breadcrumbs is an alternative way to categorize files (type). It is a hierarchical system, different elements can either go up, down, next, previous, or be on the same level. Analogies can be drawn to family systems with father, mother, brother, sister and also programming with different object being parts of bigger different classes (without the inheriting). ^ad9e45

The purpose of the system in place in here is to group elements around similarity but also visualize relations and "similar different" objects. My first approach was to have two hierarchies in place, one for general theme, e.g. public law as down to law, Staatsorga down to public law etc., and one for "similar different" elements. As I differentiate between persistent objects or elements via the type of flowers and more loosely structured elements of type Note, I needed a system to integrate that. Beyond that I also wanted to visualize if something may be relevant to the current file but is not of the theme of the main system.  
This second system consisted of see also (same), notes (down), on (up).  
With time passing I realized this segregation may not even be necessary and decided to abandon it in favor of a unified system.  
In time I came to realise that a fundamental logical rift between elements of the same topic and elements I want to visualize a similarity spans. The current system is doesn't completely abandon all walls between these 

**up**: Up is in general to lead to files that are more broad, of the same theme (e.g. from Public Law there is a up entry to Law). For a note it marks what it is commenting on or directly dependent on. Up can generally only be one

**same**: Same is intended to display elements that are somehow related (not by theme) or relevant to the current file (e.g. #todo). Same can be multiple but normally without entries.

**down**: Down in general leads to more specific topics of the current theme (e.g. from Law there is a down entry to Public Law). Down can generally only be one and be omitted (if there is a up, implicitly there also is a down) best practice is to still write it down.

**next**: Next is the next entry in a line of similar elements of the same theme (e.g. from Used Margin there is a next entry to Free Margin). Next can generally only be one.

**prev**: Previous is the next entry in a line of similar elements of the same theme (e.g. from Free Margin there is a prev entry to Used Margin). Prev can generally only be one and be omitted (if there is a next, implicitly there also is a prev) best practice is to still write it down.
