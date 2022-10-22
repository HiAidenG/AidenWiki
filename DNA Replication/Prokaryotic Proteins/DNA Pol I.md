# Function
5' to 3' exonucleolytic activity, functions to remove RNA primers after replication is complete. 

# Nuances
There are two competing models of how the RNA primers are removed:
1. Pol I removes the primers, [[DNA Ligase]] seals the nick in the sugar backbone.
2. [[RNaseH]] degrades the majority of the RNA hybridized to the DNA, Pol I removes the last few nucleotides, [[DNA Ligase]] seals the nick.

Testing *In vivo* which theory is correct:
- Clone plasmids that are double stranded except for one region where it is hybridized to RNA instead of DNA into an *E. coli* cell
- Make the plasmid a mutant that only expresses exonuclease deficient Pol I
- Extract the plasmids, if RNase H degraded the RNA, Pol I should have been able to replace it but if the theory that Pol I also removes the last few RNA nucleotides holds, there should be some RNA present. 
- Either:
	- A. Sanger sequence to detect the RNA
	- B. treat the extracted plasmids with RNAse H again, see if they run differently on a gel.
		- If they do: RNA must have been present
		- If they don't, there must not have been any RNA so RNase H removed all of it *In vivo*

# Testing Directionality
Pol I removes nucleotides in a 5' to 3' fashion, how can we test that *In vitro*?
- Would a DNA sequence in which the template DNA runs 5' to 3' and has two short DNA molecules hybridized to it with fluoresecent nucleotides and a gap between them, where one base in each of the short, hybridized sequences is mispaired. 
- If Pol I travels in the 5' to 3' direction, both those molecules will be excised, and the fluorescence will disappear. 
- If Pol I travels in the 3' to 5' direction, it will not be able to excise the mispaired bases, and the fluorescence will remain.

