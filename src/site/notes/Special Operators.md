---
{"dg-publish":true,"permalink":"/special-operators/"}
---

#Busqueda 

These are operators that may work in some databases but not all of them.  These often don't work in PubMed, but they are relevant for other databases. 

## The wildcard operator

1. Single character wildcard (?) 
	1. ne?t = neat, nest, next 

## Zero-or-one character 

1. colo$r = color, colour

This one is especially useful when attempting to account for alternate spellings between english dialects.

## Proximity Search

Finds one word occurring within a specific distance of another word
1. health NEAR/3 heart (will find results with the word health within 3 words of the word heart)
2. patient NEXT/3 education (will find results that have the word education AFTER the word patient within 3 words)

[[Systematic Search Workshop\|Systematic Search Workshop]]
