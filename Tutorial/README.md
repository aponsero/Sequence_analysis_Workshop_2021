# What can we learn from a DNA sequence?

**Overview of the hands-on exercise**

This hands-on workshop focuses on an unknown DNA sequence collected in a surface seawater metagenomic sample. The sequence is available in contig_unknown.fasta file.

**Discussion: What can we learn from an unknown DNA sequence?**

## 1- What kind of organism this sequence belongs to?
The first question that comes in mind when dealing with an unknown sequence is trying to identify the "who"?

### 1.A Run a BlastN query against the NCBI GenBank database

Step1: Go to the [NCBI Blast page](https://blast.ncbi.nlm.nih.gov/Blast.cgi) and select the Nucleotide Blast tool.

Step2: Paste the sequence in the "Enter Query Sequence" imput box and choose the "Nucleotide collection (nr/nt)" datasbase to query. 

Step3: Run the algorithm to identify "Highly similar sequences (megablast)".

**Discussion: Look at the results. What can we say about the sequence? What type of organism is it?**

**To go further: Explore [microbeWiki](https://microbewiki.kenyon.edu/index.php/MicrobeWiki), a great ressources for the description of microbes**

## 2- What biological functions does this sequence encode ?

Next we want to get an idea of what information we can retrieve on the functions carried in this DNA sequence. 

**Discussion: What is a gene? How can we identify a gene in a DNA sequence?**

### 2.A Unsing GeneMark to identify ORFs

Step1: To retrieve the ORFs from our sequence, we'll use the heuristic [GeneMark](http://opal.biology.gatech.edu/GeneMark/heuristic_gmhmmp.cgi).

Step2: Paste the sequence in the input box. Select "Protein sequence" as output. Leave the other parameters as default. 

Step3: Run GeneMark and open the protein sequence output.

**Discussion: How many ORFs did the algoritm identify in our sequence?**

## 2.B Explore putative protein functions with BlastP

Step1: Go to [BlastP](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE=Proteins) at NCBI.

Step2: Paste our protein sequences (sequence available in unknown_proteins.fasta file) in the input query box, and choose to run BlastP against the "Reference proteins (RefSeq_protein)" database. Leave the other parameters as default

Step3: Browse the results for each of the putative proteins.

**Discussion: What type of functions did we identify? **

## 3 To go further

Step1: Go to [the CARD database](https://card.mcmaster.ca/)

Step2: Navigate to the [BLAST tool on their website](https://card.mcmaster.ca/analyze/blast) and run the tool on the first protein sequence.

**Discussion: What can you learn about that protein functions? in which organism is it usually found?**


