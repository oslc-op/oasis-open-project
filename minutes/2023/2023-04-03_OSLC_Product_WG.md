# OSLC Product Workgroup (April 3rd 2023)

Location : Online at https://meet.jit.si/oslc-op

**Chairs:** Gray Bachelor, Patrick Ollerton

**Attendees:** 

- Gray Bachelor (IBM)
- Andrew Berezovskyi (KTH)
- Patrick Ollerton (PTC)
- Jim Amsden (IBM)
- Eran Gery (IBM)
- Fabrice Mendes (IBM)

Apologies
- Ralph Schoon (IBM)
- Michael Rowe (IBM)
- Robert Baillargeon (Sodius-Willert)


Past attendees
- Jad El-Khoury (KTH)
- Martin Ulrich (Bosch)
- Tanupreet Jolly (PTC)
- David Honey (IBM)
- François-Régis Jaunatre (Sodius-Willert)
- Jim Gammon(Raytheon)
- Axel Reichwein (Koneksys)
- Jeff Zemsky (PTC)
- Erik Herzog (Saab)
- Judith Crockford (Eurostep)

**Previous minutes:** https://github.com/oslc-op/oasis-open-project/blob/master/minutes/2023/2023-03-06_OSLC_Product_WG.md

## Agenda

- [ ] Roll call
- [ ] Start recording
- [ ] Minutes of the last meeting - any matters arising
https://github.com/oslc-op/oasis-open-project/blob/master/minutes/2023/2023-03-20_OSLC_Product_WG.md
- [ ] - [ ] PGB - position - what and when to take back		
- [ ] Update on PGB feedback and complete the mission  https://github.com/oslc-op/Product-Definition/blob/main/Aim%20of%20the%20OSLC%20Product%20workgroup_200323.docx
- [ ]   Discussion around additional available input from a PTC customer - Whirlpool
- [ ]     Discussion on first scenario to confirm our scope
- [ ] Any other business
- [ ] Any closing comments from attendees


## Minutes

report back to PGB aims to keep a focus on Product structure 

Jim provided an initial set of use cases as  a suggestion - then refined at the end of the call 

Patrick summarised the Whirlpool document - referred to page 15 of 53 (INCOSE deck
	1st integration case - what is it in PLM (EBOM) that "will satisfy" - a part connecting to an individual (sets relats to cfgm
	later in the lifecycle (does satisfy)
	may be 1 part to many reqs or reverse
	dont general deal with ind parts - make link at the assy
	(Multiple tools use for reqs 
	Business relaates to demand on 3rd party suppliers
	
	2nd example where reqs are "allocate"d to a node (higher level conceptual assembly) "planning link" - this is earlier in a lifecycle 
		allocate to existing
		
	Product Manager or Lead Engineer is the sponsor and responsible to check
	
Jim suggest adding a V&V capability and C&CM on a separate

Whirlpool's focus is relationships

Trace EMBOM to AM logical elements and then Reqs - WP like OSLC GCM (ref P7/16 Use case 2 Create the link

PLM dont have have a GC context - WP request that - latest live not cfg aware - select / aware of the cfg layer - choose
its resolves a set of conditions and that is the prevailing cfg 

Every part in PLM has many version - default = Latest

(UC1 P5 Update a SKU record - small scope of overall - this ties the SKU management to the more fluid scoping)

Need: select a cfg and it sets the prevailing elements and links
Need: reconcile and align PLM "resolving action" with OSLC GC Approach: static baseline or effectivity definition
Need: define a scope within PLM of the resolving action (WP UC1)

Suggestion: Start w/o version aware, then become version aware, need to signify that versions now matter and it's dependency graph
(PLM ecxpose versions and SCM generally dont) - PLM milestone - formal approval - Release (to Manf) 

PLM ask about a Req version - in IBM DNG its hidden as its managed by the Cfg

UC3 Arch model to / from PS
	want 2 way traversal from AM to PLM and back (Today model to PLM 

UC4 Baselining	the resolved PS and its related artefacts at the SKU level - main or specific variant

Could the prevailing versions be just a view in PLM = version - configuration record 

Side note: WC Modeller version the container

Jim suggested that ALM is perhaps more generalised in its use of CfgM
 and it may be possible to learn something from applying SysML as a way to define PS. Eran reminded of the need to address the current challenge of PLM integration. It was proposed to do PLM 1st then turn to the SysML scenario.

Defining the product structure (PLM centric
	define the scope UC1
Capturing requirements for product structure.UC2
	(Connect Reqs to PS
Designing components of product structure. UC3 link AM and PS
Managing change request on product structure.
Verification and Validation of product structure UC4
Creating versions and variants of product structure UC4 baselining

Not 
Define meta-model

? What is a product structure - membership, inclusion, primacy

Jim updated his proposed list 
Primary use cases I think should be addressed
	1. Defining the structure of some complex product.
	2. Capturing requirements for product structure.
	3. Designing components of product structure.
	4. Managing change request on product structure.
	5. Verification and Validation of product structure against requirements
	6. Creating versions and variants of product structure over time to meet different requirements. 

Note: We may well consider the specialisation of AM spec

Propose for the 17th: Initial focus on product strcuture then use that to walkthrough the Whirlpool 4 UCs 

Thanks to Whirlpool for the contributed input and to Patrick for intrducing it.
Thanks everyone for a useful discussion 

Action: Patrick to lodge the report on the Github Product Definition folder https://github.com/oslc-op/Product-Definition

## Contact points

gray_bachelor@uk.ibm.com
pollerton@ptc.com
