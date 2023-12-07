# Student 2's Answer to Question 2
**Question2**Please assign variables to the individual components of your favori
promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print
by using the string concatenation operator, on the standard output! Note: Feel f
fictional gene sequence by randomly filling in the gene components by the charac
corresponding to individual nucleotide bases.


**Answer**

promoter="AAATTTAAAAATTTTAAA"
5_prime_UTR="CCGGAAATTTAAGGG"
start_codon ="AGC"
exon1="CCGGAAAATTTCCGAAG"
intron="GGGGAAATTTCCCCGGAA"
exon2= "TTTAAAGGGCCCAAAT"
stop_codon="UAG"
3_prime_UTR="CCCTTTAAAGGGAAAT"


my_favorite_gene = promoter + five_prime_UTR + start_codon + exon1 + \
                   intron + exon2 + stop_codon + three_prime_UTR

 print("My favorite gene sequence is as follows:")
 print(my_favorite_gene)
