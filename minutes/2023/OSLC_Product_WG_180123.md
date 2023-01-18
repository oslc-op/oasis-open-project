# OSLC Product Workgroup (Jan 18, 2023)

Location : Online at https://meet.jit.si/oslc-op

**Chairs:** Gray Bachelor, Patrick Ollerton

**Attendees:** 

- Gray Bachelor (IBM) 
- Patrick Ollerton (PTC)
- Tanupreet Jolly (PTC)
- Fabrice Mendes (IBM)
- Andrew Berezovskyi (KTH)
- Jim Gammon(Raytheon)
- Eran Gery (IBM)
- Jeff Zemsky (PTC)
- Martin Ulrich (Bosch)


Apologies
- David Honey (IBM)
- Jad El-Khoury (KTH)
- Robert Baillargeon (Sodius-Willert)
- Michael Rowe (IBM)
- François-Régis Jaunatre (Sodius-Willert)


**Previous minutes:** 

## Agenda

- [ ] Roll call 
- [ ] Additional perspectives on representing PLM resource using OSLC < Patrick Ollerton & Tanupreet Jolly, PTC
- [ ] Discussion & summary on PTC input
- [ ] Plans for next meeting - OEM inputs
	1st and 15th feb and 1st mar
- [ ] Any other business
	Meeting timing
- [ ] Any closing comments from attendees

## Minutes

Notes from Patrick and Tanu
1) uses and usedby are the primary relationships but not like UML/SysML
2) children are parts that make up an assembly
3) reuse is by parent with additional uses - is this a template (type) and instance - part carries the definition
	this is different from as-designed vs as-operated
	the relationship of uses indicates the instance of the part e.g. wheel in an assembly e.g. chassis with 4 wheels
4) what are external refs ?
	some internal, some links (e.g. Req OSLC)
5) docs or objects added to instance ? e.g. torque spec on a bolt (instance) 
6) Part master is like an OSLC Concept resource
7) Part version is the changing state
	release is marked
	often latest is used as default
8) Relationships are either version specific (manual change) or always the latest (version independent) - effectivity in config controls the latter (DATE, LOT AND SERIAL NO.)
	OSLC says version independence needs further resolution
9) Key Qs: How much of this PLM revisioning behaviour needs to be catered for ?
10) ALM support branch/copy/merge
11) PTC Cfg info is on the link as opposed to separate 
12) integrated change tied to configured
	use link to find the next part master
13) relationship product to reqs - allocate, satisfy and implement
14) look at RDF - part is a config component
15) OSLC Query Look for parts and versions
16) resource Shape exposed
17) client app use the query e.g. part tree
18) Observations 
	is Cfg domain "inappropriate" or insufficient 
		AM Resource was more generic like a superclass e.g. part as a sub-class
		CfgM doesnt describe the item being represented 
	what limits data quality - extent of representation ?
	PLM data is accessed "one at a time" - may need a collection concept
	"Filtering like effectivity, LC state not part of CfdgM spec"
	End to end cfgm with domains - rels controlling appearance in a cfg - "all 
	
19) Conclusions 
		Version of part is central - vs resolution by GC context over contributions in OSLC CfgM
		
20) Recommendations / propoosal
		Look for use cases that distinguish / isolate the needs	
		Look at extensions to AM and CfgM
		Order of business: BOM, rels to other specs and CfgSpec - BOM, look at change over time and how represent, version visibility due to effectivity 
			GC that relate version of Reqs to version of parts
			but perhaps some other approach for relationship between parts ?/TBC
		Aim to keep part and configuration distinct

	

### Plans for OEM input

Requests
Bosch - Martin Ulrich
Raytheon - Jim Gammon
Saab - Erik Hartog
+ 1 other via Patrick

### Meeting timing ?

We will stay with 15CET/9ET start for next meeting

### Other Topics

Andrew request follow up on the P22 reverse link service


## Action items

- [ ] Gray to send invites for Feb 1st, 15th and March 1st
- [ ] Patrick to send ppt
- [ ] Fabrice to share recording if its succesful
- [ ] Martin schedule input for next meeting Feb 1st
- [ ] Gray to post minutes on GitHub
- [ ] Andrew send email on reverse link look up

## Contact points

gray_bachelor@uk.ibm.com
pollerton@ptc.com

