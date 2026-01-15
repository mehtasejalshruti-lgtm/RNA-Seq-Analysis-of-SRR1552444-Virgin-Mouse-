# Folder-3
# Fastqc on SRR1552444 ( VIRGIN MOUSE )

FastQC is used to **check the quality of raw sequencing data** by analyzing read quality scores, GC content, sequence length, and detecting issues like adapters or contamination 

<img width="1920" height="1080" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/5580fddc-1a67-4f60-a184-eecd5fdc5c5d" />

# Trimgalore 

Trim Galore is used to **remove adapter sequences and low-quality bases from sequencing reads** to improve data quality before downstream analysis 
<img width="1920" height="1080" alt="Screenshot (63)" src="https://github.com/user-attachments/assets/8acc4143-ed13-4acc-88ec-22cd72da788f" />
 We convert the trimmed file into FastQC format (run FastQC again on trimmed reads) to check whether trimming actually improved the read quality.
<img width="1920" height="1080" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/06f44085-12af-4f7e-9d52-667750a47cca" />

# Bowtie

Bowtie is a **fast alignment tool** used to **map sequencing reads to a reference genome** efficiently 
<img width="1920" height="1080" alt="Screenshot (78)" src="https://github.com/user-attachments/assets/068d67cc-f670-4946-952a-760bd538b2e2" />

# Featurecounts 
eatureCounts is used to count the number of reads mapped to genomic features (genes/exons) to generate a gene expression count matrix for downstream analysis
<img width="1920" height="1080" alt="Screenshot (79)" src="https://github.com/user-attachments/assets/6efe533e-2046-449a-becf-dca891ecece3" />

# DEseq2
we can use either DEseq2 or edgeR for the next step , but we use DEseq2 as the sample size is small
* **DESeq2:** simpler and more stable, best when you have **few samples**.
* **edgeR:** more flexible and powerful, works better when you have **more samples**
  







