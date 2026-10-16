#Recorded Opsin genes in Nematostella vectensis

Author: Shay Wang
API: [MyGene.info]https://docs.mygene.info/

##What this script does:
1. extract genes that have 'opsin' in the recorded name, output all matches. Total of 5 opsin genes are recorded
2. For each recorded opsins, extract its full record, including the symbol, name, and RefSeq protein IDs.
3. Plot the number of RefSeq protein records per gene, and output a png image file titled `opsin_protein_counts.png`
4. Compare the number of recorded opsins in Nematostella, humans, fruit flies and zebrafish and output a box plot png image file titled `opsin_by_species.png`.
