# OSLC Product Workgroup (Feb 1, 2023)

Location : Online at https://meet.jit.si/oslc-op

**Chairs:** Gray Bachelor, Patrick Ollerton

**Attendees:** 

- Gray Bachelor (IBM) 
- Fabrice Mendes (IBM)
- Erik Herzog (Saab)
- Tanupreet Jolly (PTC)
- Andrew Berezovskyi (KTH)
- Jim Gammon(Raytheon)
- Eran Gery (IBM)
- Martin Ulrich (Bosch)
- Robert Baillargeon (Sodius-Willert)
- Patrick Ollerton (PTC)
- Ralph Schoon (IBM)

- Michael Rowe (IBM)
- Jeff Zemsky (PTC)


Apologies
- David Honey (IBM)
- Jad El-Khoury (KTH)

- François-Régis Jaunatre (Sodius-Willert)
- judith Crockford (Eurostep)


**Previous minutes:** https://github.com/oslc-op/oasis-open-project/blob/master/minutes/2023/2023-01-18_OSLC_Product_WG.md

## Agenda

- [ ] Roll call
- [ ] Start video 
- [ ] Minutes of the last meeting - any matters arising
	Meeting timing - Doodle - link to chat https://doodle.com/meeting/organize/id/b46Gnr1e
- [ ] Additional perspectives on representing PLM resource using OSLC < OEM input from Jim Gammon, Raytheon
- [ ] Discussion & summary on OEM input
- [ ] Plans for next meeting - OEM & other inputs
	15th feb and 1st mar
- [ ] Any other business
- [ ] Any closing comments from attendees

## Minutes

Jim Gammon of Raytheon session

1. Business needs for technical baseline of data as a Digital Thread at the "artefact level with cfgm" - track versions, change set
2. Program decisions are based off that aggregated baseline (aggregation was slow in the past
2. Program decisions are based off that aggregated baseline (aggregation was slow in the past
3. Business merger and acquisitions compound the challenges of heterogenous sources
4. PLM = Mech & elec, ALM = ESW, Sys, SW - PDM owned the Product Breakdown Structure (PBS) and was treated as source of truth
5. "link & integrate data"
6. Showed a system structure
7. PDM is a potential home for the Digital Thread but needs re-imagining
8. Thread includes the links (identified as within a broker

Q&A
How do integration links play into the DT (P4 diagram)? A: Capture links within the configuration (echo'd by Bosch) (can use a mesh tool )
What are the purpose of the link (locators, unique ID of the relationship, binary rel between resources ? 
Is the diagram one of references or system structure ? its more of a config of congurations
What are the capabilities in PDM that need addressing ? for software, branch/merge, change set to the aggregated - baseline at set config, validation of content and context, trusted simulation context ties to results

Remarks from Bosch - recognise the local and global configuration, links included in the speciifcation, bidirectional navigation
	dont need a seperate CI for the links - included 


Erik Herzog of Saab

1. Has a joint prpoject with eurostep, IBM and KTH
2. Genesis model identifies 4 common needs across the disciplines - ReqM, Confg Item structure, Change control & realisation structure
3. Need to maintain traceability
4. Analysed the info models and noted 
	product data - many PartViews per version, OSLC single version resource
	product structure - PartViewreleationship - multiple breakdownms per View
	configurations - multiple effectivity management - OSLC not say how selection is done
	link - implicit linking in OSLC and context , explicit in STEP with effectivity
5. Heliple project includes another OEM - Volvo to explore Mechanical design and OSLC 

Q&A What is the realisation structure ? physical deliverables (as built)
Q&A What is the configuration structure ? physical deliverables (as designed)
What is the role of the PartVerionRelationhip ? define the version marking
Is STEP sufficient for this task ? Respected in the mechanical world
What is the role of Eurostep ? STEP base repository e.g. for customer gateway


Scenarios
- examples from Raytheon 

gaps and challenges
- examples from Saab

examples of extensions and adaptation
- examples from PTC


### Plans for OEM input

Requests
Bosch - Martin Ulrich - scheduled for 15th Feb
Raytheon - Jim Gammon - done
Saab - Erik Hartog - done 
+ 1 other via Patrick



## Action items

- [ ] Gray to send invites for Feb 1st, 15th and March 1st - await Doodle
- [ ] Patrick to send ppt - done but didnt decide where to put it !
- [ ] Fabrice to share recording if its succesful
- [ ] Martin schedule input for next meeting Feb 15th
- [ ] Andrew send email on reverse link look up

## Contact points

gray_bachelor@uk.ibm.com
pollerton@ptc.com

