#### Name: Madelyn Kapfhammer

#### Date: 29 March 2021

#### What this is: Questions in blue from the assignment sheet.

#### Part 1.

1. Which software did you use to conduct your analysis?

In order to conduct an analysis of the sequences in `s1.fasta` and `s2.fsta` I used the [Interactive demo for Needleman-Wunsch algorithm website](http://experiments.mostafa.io/public/needleman-wunsch/) that was provided to us in the lab handout.

2. How similar were the two sequences (`s1.fasta` and `s2.fasta`) which you applied an alignment program?

When applied to an alignment program, these two sequences recieved a sequence score of 10. This score indicates that these sequences are relatively similar. While the sequential base-pairs of these sequences do not match completely, their scores within the Needleman-Wunsch algorithm are high up to a point, indicating a strong relationship between the two.

The best alignment between the two of these sequences is:

```
A	T	T	T	G	G	C	T	A	C	A	T	T	T	C	A	C	A	G	T	-
A	T	T	T	C	A	C	A	G	T	A	T	T	-	C	A	C	T	G	A	G
```

Within this alignment, there are only two small gaps. With this in mind, it is shown that these sequences are closely related with only two insertions/deletions present within the two sequences.

3. Are the two sequences closely related to each other, in your opinion?

From looking at the two sequences side by side, and analyzing their contents, I do not believe that these two sequences are closely related to each other.

4. What proof do you have to suggest such a claim?

I believe that these given sequences are not closely related to each other, specifically because they only have three exact replications within their sequences. Each of these sequences match for `ATTT`, `C` and `ATT`. This does not indicate much similarity between the two sequences. Additionally, the sequences do not follow similar patterns of base-pairs. The repetition of bases are not similar within these sequences, possibly indicating that they are not coding for the same nucleotides and amino acids. From this information that was generated through only naked-eye analysis, I do not believe that these two sequences are closely related.

#### Part 2

1. How much similarity exists between each of the sequences to the others?

The provided DNA sequences were renamed for simplicity as depicted below:

A/chicken/Viet_Nam/10/2005_(H5N1)_segment_4 -> labeled `DNA_A`

A/China/GD01/2006_(H5N1)_segment_4 -> labeled `DNA_B`

A/avian/Hong_Kong/719/2007_(H5N1)_segment_4 -> labeled `DNA_C`

`DNA_A` and `DNA_B` sequences were extremely similar with a similarity percentage of 95.2%. `DNA_A` and `DNA_C` sequences were also extremely similar with a similarity percentage of 96%. `DNA_B` and `DNA_C` sequences were the most similar with a similarity percentage of 97.5%.

2. Based on your results so far (which are too few to provide a comprehensive study), do you believe there is evidence that human adaptation is occurring in H5N1 viruses that might merit concern about human-to-human transmission in the near future?

Based on the similarities between avian H5N1 viruses and strains of H5N1 in humans through these alignment studies, I believe that human-to-human transmission should be a concern related to this virus. With such close relationships between avian bird-flu strains, and human strains (specifically depicted with analysis of `DNA_B` and `DNA_C`) it is clear that the H5N1 virus is mutation to become more virulent and changing in modes of transmission. If sequences for birds and humans are very close, it is most likely that humans will soon be able to transmit H5N1 in a direct human contact scenario, rather than from an animal to human interaction. Viruses often mutate quickly to improve (their own) transmission. Evolutionarily speaking, it is the most advantageous for the H5N1 virus to change for human-to-human transmission.

3. Statistics: What were the numbers of Lengths, Similarities, Gaps and Scores for each of your alignment tasks?

**Alignment between DNA_A and DNA_B**

Length: 1776

Similarity: 1690/1776 = 95.2%

Gaps: 45/1776 = 2.5%

Score: 8286.0

**Alignment between DNA_A and DNA_C**

Length: 1751

Similarity: 1681/1751 = 96.0%

Gaps: 20/1751 = 1.1%

Score: 9379.0

**Alignment between DNA_B and DNA_C**

Length: 1776

Similarity: 1731/1776 = 97.5%

Gap: 25/1776 = 1.4%

Score: 9703.0
