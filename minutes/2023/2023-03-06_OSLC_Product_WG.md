# OSLC Product Workgroup (March 6th 2023)

Location : Online at https://meet.jit.si/oslc-op

**Chairs:** Gray Bachelor, Patrick Ollerton

**Attendees:** 

- Gray Bachelor (IBM) 
- Robert Baillargeon (Sodius-Willert)
- Jad El-Khoury (KTH)
- Martin Ulrich (Bosch)
- Eran Gery (IBM)
- Jim Gammon(Raytheon)
- Fabrice Mendes (IBM)
- Jim Amsden (IBM)
- Ralph Schoon (IBM)
- David Honey (IBM)


Apologies
- Tanupreet Jolly (PTC)
- Andrew Berezovskyi (KTH)
- Michael Rowe (IBM)
- Patrick Ollerton (PTC)

Prior attendees
- Axel Reichwein (Koneksys)
- Jeff Zemsky (PTC)
- Erik Herzog (Saab)
- François-Régis Jaunatre (Sodius-Willert)
- Judith Crockford (Eurostep)


**Previous minutes:** https://github.com/oslc-op/oasis-open-project/blob/master/minutes/2023/2023-02-27_OSLC_Product_WG.md

## Agenda

- [ ] Roll call
- [ ] Start video 
- [ ] Minutes of the last meeting - any matters arising
https://github.com/oslc-op/oasis-open-project/blob/master/minutes/2023/2023-02-13_OSLC_Product_WG.md
	- [ ] Additional tie for perspectives on representing PLM resource using OSLC < continued OEM input from Martin Ulrich Bosch
	A presentation was provided at https://github.com/oslc-op/Product-Definition/blob/main/Bosch%20OSLC%20product%20scenarios%202.pptx
- [ ] Discussion & summary on OEM input
	Notes below
- [ ] Plans for next meeting where we will aim to consolidate the inputs into areas – general needs, scenarios, specific gaps/proposals
                            Planned for March 20th – other inputs – potential input on STEP and from 2 other OEMs
- [ ] Any other business
- [ ] Any closing comments from attendees

## Minutes

1. New folder for files and contributions < thanks Jim Amsden
2. Notiing the contribution of Jim Gammon of Raytheon
3. Martin Ulrich of Bosch continued:
4. Clarification of terms
	CI is equivalent  to an OSLC Configuration Contribution
		Configuration is a container on which actions are done on the CIs
			project, system elements and physical products are CIs
				project may or not be versioned or at least deliverables are versioned
		the Contribution is reiified to carry more properties
			DH says its an embedded resource via a blank node at least in ELM
		can have an link ietme between
	Part / product are equivalent
5. Expect OSLC connectors to Share point
6. List capability
	Want CI item type < need richer properties
7. May want to allocate an config container as a place holder for future 
	cardinality 0>1
		example "tailoring of project" - identify work packages and work products but they dont exist but want to see the full structure	
		already have a component - could have a contribution as a placeholder
	type may be missing from artefacts - sharepoint doesnt
Properties of the componetn, relationship or resource	

OSLC Configs are "part of the configuration" - no rdftype (optional), anonymous blank node, no resource shape
To construct a BOM - add the quantity on the relationship therefore add to the contibution
Request to add additional typing and propertoies to the OSLC Contribution
Proposal to add the Thu meeting - how to achieve in a non-breaking manner 
8. 7 topics
	Product Master data	
		Abstract concepts and versions are independent
			e.g. a product, prod line (host product instances) ISO26580 or project based configs
		
		Manage master product  - inhertitence, identity/classify - clustering, org responsibility
			specialisation of a compponent (unit of configurability)
		Status control 
		Component and Product begin as version independent concepts
			OSLC Components are not containers to make a hierachy - concpetually a concept 
				use a Configfuration or a resource - 
		Aim to seperate the concerns of the version identity and the the thing being versione
					
		Spec - Component is a collection of concept resources
			e.g. Compo with 100 req concept resources < may select concepts in pool and then which versions
				this is akin to the artefacts in Bosch model
		Selection is relevant for the local config
		
		
	In general GC - Component have contribs and Local Configs have Selections but this is an implementation decision, either could use both concepts
		
Summary of key points

1. Typing of Contribiution to elevate it to be the CI
2. Manage Product Master Data use case < create product structure
3. Choose to separate resource from configuration

We decided to summarise the progress so far back to the pgb - to confirm the scope and approach - this may already be possible this week Thursday.

We will schedule the Product workgroup as March 20th




















## Contact points

gray_bachelor@uk.ibm.com
pollerton@ptc.com

