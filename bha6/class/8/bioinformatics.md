---
layout: page
title: Bioinformatics
permalink: /bha6/class/8/bioinformatics/
---

## Goal

This practical introduces you through several online databases and tools used in Bioinformatics, such as [Blast](https://blast.ncbi.nlm.nih.gov/Blast.cgi) and [Expasy](https://web.expasy.org/translate/)

## Excercise 1: Using BLAST

### Goal:
Use Blast.
Identify the Gene in a Sleep Disorder, exercise from [https://www.ncbi.nlm.nih.gov/Class/MLACourse/Modules/BLAST/q_mastery_blastn_blastp.html](https://www.ncbi.nlm.nih.gov/Class/MLACourse/Modules/BLAST/q_mastery_blastn_blastp.html)

0. Copy the sequence from above link.
1. Go to Blast: [https://blast.ncbi.nlm.nih.gov/Blast.cgi](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
2. Perform a Nucleotide Blast using the DNA sequence
3. Perform a protein Blast using the Amino Acid sequence
4. What gene correlates with the sleeping disorder?
5. Is there difference in the number in resulting hits in the databases between nucleotides and proteins? Which one would be more specific?

## Excercise 2: From DNA to Protein!

### Goal:
Learn about reading frames, from DNA to Protein!

0. Copy the sample DNA sequence from [https://www.ncbi.nlm.nih.gov/Class/NAWBIS/Modules/InfoHubs/infohubs3.html](https://www.ncbi.nlm.nih.gov/Class/NAWBIS/Modules/InfoHubs/infohubs3.html)
1. Go to Blast: what is the gene name associated?
2. Google: what is the clinical relevance of this gene (i.e. in health care) ?
3. What is the amino acid sequence in humans? Copy and save it somehwere
4. Download the FASTA format of the gene.
5. Every nucleotide sequence can be read in 6 reading frames: every 3 nucleotides can be translated in 1 amino acid, and DNA can be read 5' --> 3' or 3' --> 5'. Parts that start with **Met** and and with **Stop** are translated into amino acids.
We want to find out: What is the reading frame for this protein?
To find out, go to Expasy: [https://web.expasy.org/translate/](https://web.expasy.org/translate/)
6. Type in the DNA sequence from the FASTA file, and find out: what is the reading frame for this protein?

## Excercise 3: Learn about genes!

### Goal:

How do you find out information about genes online?

In Prof Simon E. Fisher's [Twitter thread](https://twitter.com/ProfSimonFisher/status/1105121806921416707) he talks the about the ORIGEN Superhero consumer DNA test, writing "They claim their FOXP2 test can reveal whether "you have the mind of a super-genius". [Bangs head repeatedly against desk while sobbing.]"

0. Which genes are included in the Superhero test at [https://shop.orig3n.com/products/superhero](https://shop.orig3n.com/products/superhero) ?
1. Go to [https://www.ncbi.nlm.nih.gov](https://www.ncbi.nlm.nih.gov)
2. What can you learn about the genes? Can you find evidence for superhuman ability in the FOXP2 gene? What about the other genes mentioned in the Superhero test?


## Other links

Other interesting software in bioinformatics:

* [Jalview](http://www.jalview.org) is used to align sequences. You can download them in the FASTA format, and import them in Jalview.

Return to [BHA6 - Class 8](/bha6/class/8/)
