# Student 2’s Answer to Question 2

**Q2.** Assign variables to the individual components of your favourite gene (e.g., promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene by concatenating these parts.

**Answer**


```
promoter = "TTTATTTAAATTTAAA"
five_prime_UTR = "AAAATTTTGGGGGAAAA"
start_codon = "ATG"
exon1 = "ATGCGTACGTA"
intron = "GGGGCGGGA"
exon2 = "ACTGAAAGT"
stop_codon = "TGA"
three_prime_UTR = "TTTTTAAAATTTTAAAA"

my_fav_gene = promoter + five_prime_UTR + start_codon + exon1 + \
            intron + exon2 + stop_codon + three_prime_UTR

print("My favourite gene sequence is as follows:")
print(my_fav_gene)

```