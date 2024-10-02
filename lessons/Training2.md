## Training 2
#### 6 Nov 2024

Classification and protein structure alignment

### 1. Search for protein domains and their structure

Search in the Uniprot database (www.uniprot.org) the protein with the code Q12923.
• What is the sequence length of this protein?
• Can you cite some domains found in this protein?
• To which domain does the PDB code structure 3PDZ correspond?
• Are there disordered regions in this protein? If so, were the annotations made automatically or by experimental measurement?
• Is there an experimental structure for the whole protein?

### 2. Classification database

A] Find on the PDB website (http://www.rcsb.org) the proteins with the following PDB code: 3PDZ, 1Z86 and 1RGW. Download the sequences in FASTA format (menu "Download Files" on the top right of the web page).

B] Click on the "Annotations" tab at the top of the PDB web pages.
• What is the CATH classification of these domains?
• What is the Protein Family Annotation of these domains?

C] Go to the InterPro database (https://www.ebi.ac.uk/interpro/). Perform a text search for this
domain in the InterPro database. What is the biological function of the domain?

### 3. Structure superimposition

Pymol will be used to visualize the superimposed structures. Pymol will not be used to superimpose the structures.

A] Use ClustalOmega (https://www.ebi.ac.uk/jdispatcher/msa/clustalo) to perform a multiple sequence alignment of the sequences downloaded in section 2A (paste all the sequences in FASTA format). Analyse the sequence alignment, and focus on the conserved amino acids at the different sequence positions. Are these sequences highly conserved?

B] Needle (https://www.ebi.ac.uk/jdispatcher/psa/emboss_needle) is a tool for performing global sequence alignment, and Matcher MA1 Bioinformatics and Modelling Biophysics and Structural Bioinformatics I Practicals (https://www.ebi.ac.uk/jdispatcher/psa/emboss_matcher) for performing local sequence alignment. Perform a global sequence alignment between 3PDZ and 1Z86 with Needle; the sequences must be provided in FASTA format (see section 2A).

Use PDBeFold (http://www.ebi.ac.uk/msd-srv/ssm/ssmstart.html) to align the structures 3PDZ and 1Z86. Choose in the "Query" and "Target" fields the option "PDB entry" as a source and give the PDB codes. What are the values of the z-score and of the rmsd, and what do they mean?

Click on the "1" in the "##" column and then download the superimposed structures (click on the 2 "download" tabs). 

Use Pymol to visualize these superimposed structures. The aligned sequences according to the structure superimposition are available lower on the web page. Compare the aligned sequences obtained by sequence alignment (Needle) and by structure superimposition.

C] Download the sequence of 1FCF from the PDB website.
• Identify from the PDB website the Uniprot code of 1FCF. Use Uniprot to identify the limits of the PDZ domain of this protein.
• Use Matcher and Needle to perform a local and a global sequence alignment between 1FCF and 3PDZ. Comment the results : are the PDZ domains aligned properly?
• Use PDBeFold to superimpose the structures of 1FCF and 3PDZ. What are the alignment scores? Visualize the superimposed structures in Pymol. Analyse the sequence alignment obtained from the structure superimposition, from the PDBeFold website. What are your conclusions? Compare these results with those obtained with
the sequence alignment.

---
### References
