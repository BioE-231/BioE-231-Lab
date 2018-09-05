#Lab 2
After generating the phylogenetic tree for the sequences in **seq.fa**, I find there are some apparent clusters in this tree in which I highlight them by drawing a red cycle on them.
![](https://i.imgur.com/GCJ2iU7.jpg)

Then, I choose a specimen from each cluster to do the identification by using BLAST.

For sequence **hu.39**, the result is shown as followed:
![](https://i.imgur.com/vABHps9.png)

For sequence **pi.1**, the result is shown as followed:
![](https://i.imgur.com/mlKl7R7.png)

For sequence **rh.35**, the result is shown as followed:
![](https://i.imgur.com/i7c1YEd.png)

For sequence **hu.43**, the result is shown as followed:
![](https://i.imgur.com/aRrOGmW.png)

From the results above, it is clearly seen that through BLAST, I find the most matched sequence whose identities up to 100% in the database online. However, BLAST is able to generate several matches and rank them in the order of identities. For example, for sequence **rh.35**, according to the default configuration, 100 matches are shown in the results (each red line represents a gene sequence):
![](https://i.imgur.com/7wwBKSV.png)

As is shown above, we can see almost all the matched sequences in the database get high alignment scores, though they actually represent different genes. Therefore, it is believed that sometimes the result from BLAST is less convincing for it has enormous data, and some gene sequences are only different from each other for 1%-10% nucleotides, which are also screened as matches by BLAST, though they represent different genes.

Then, I analyze the %AT and %CG in each cluster I have marked in the begining and generate the following four figures:

For **cluster1**：
![](https://i.imgur.com/OICpVef.png)

For **cluster2**：
![](https://i.imgur.com/pH78MUG.png)

For **cluster3**：
![](https://i.imgur.com/d2jCyo2.png)

For **cluster4**：
![](https://i.imgur.com/bybkplF.png)

Next, I calculate the length of each sequence in all four clusters, and then draw a boxplot shown as follows:

For the data in **seqs.fa**:
![](https://i.imgur.com/NsTrCBR.png)

For the data in **seqs.aligned.fa**:
![](https://i.imgur.com/qCNWRcw.png)

It is clearly shown that the length of sequences increases and reaches the same value after multiple sequence alignment process.