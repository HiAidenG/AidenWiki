Composed of two distinct subregions: 
1. AT-rich DNA containing 13-mers of a conserved sequence: GATCTNTTNTTTT aka the 'DNA unwinding element'. AT rich DNA can be more easily separated by [DnaA](../Prokaryotic-Proteins/DnaA). This is also known as the DUE (DNA unwinding element)
2. DNA boxes of varying affinities. Three high affinity boxes and 8/9 low affinity boxes. DnaA binds to the high affinity boxes first, then the low affinity, until they occupy most of the oriC. [DnaB](../Prokaryotic-Proteins/Helicase) can now bind with the help of [DnaC](../Prokaryotic-Proteins/DnaC) 

![OriC Diagaram](../images/oriC.png)


# Experimental Detection of OriC
Most famously done by the autonomously replicating sequence (ARS) assay.
- This is done by 'shotgun cloning' cleaved sequences from the genome into plasmids. If you manage to make a plasmid that can replicate on its own, you know you must have the oriC. 
- Dependent on the restriction enyzme you are using, if you accidentally digest with an enzyme that also cuts in the oriC, then you would not get replication.

How do you know it's a unique sequence (how can you check for sequence identity)?
	This is pre-sequencing.
	Restriction digests, if you always get the same banding pattern it's likely you have the same sequence. 
	But... it's also possible you have two different sequences where neither sequence has a digest site for that enzyme or both sequences do. So then you will have to replicate with many restriction enzymes. 

# Measuring Interactions with Initiator
initiator element also known as [DnaA](../Prokaryotic-Proteins/DnaA) binds at the replicator
If you have the replicator elements and the initiator, how can you figure out where binding occurs?
- EMSA (gel shift)
- or, DNase I Footprinting

How to determine necessary sequences in yeast: 
- Mutate regions of the initiator, clone into plasmids with uracil complementarity for deficient cells. If the cells survive -> sequence must have been replicated. I guess you would also have to account for transformation efficiency here... this would be somewhat imprecise. 
- If you really care about being off by a constant factor, you could probably also have the plasmids express GFP to use as a measure of TE.