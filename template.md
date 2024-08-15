# Awesome title

- By: [Your Name][ORCID]
- Analysis: Date

Feel free to change the example text. Most of it is there as examples 

## Introduction

[Palmer Lab][OurResearch] performs genome-wide association studies (**GWAS**)
using [heterogenous stock (**HS**) rats][CoreB]...

This project aimed to ...

## Materials & Methods

### Dataset

HS rats were sequenced by ~0.25x coverage double-digest genotyping by sequencing
([Gileta *et al.* 2020][Gileta2020]) or low-coverage whole-genome sequencing.
Biallelic single nucleotide polymorphisms (**SNP**s) on [mRatBN7.2][MRatBN72]
were imputed by [STITCH][STITCH] as described in [Chen *et al.* 2023][Chen2023].
Full genotypes are [archived][UCSDLibraryGenotypes].

Rats were filtered to only those... SNPs were filtered by standard thresholds: 

- minor allele frequency (**MAF**) of ≥ 0.005
- missing rate of ≤ 0.1
- [Hardy-Weinberg equilibrium][HWE] (**HWE**) p-value of ≥ 10<sup>-10</sup>

The final dataset had ? SNPs called in ? rats.

### Cool method

[Cool Method][CoolMethod] was applied by...

1. Step 1
2. Step 2

Code:

```
plink --bfile data/geno --cool --option one two --out results/cool
cut -f1 results/cool.ext > results/final_ids.txt
```

### Software

- [PLINK][PLINK] version `version`, used for...
- [R][RProject] version `version`, used for data analysis Packages used:
    - [`cowplot`][Cowplot] version `version`, used for plot themes/arrangement
    - [`ggplot2`][Ggplot2] version `version`, used for general plotting

Code was deposited in [GitHub][GitHub] for Palmer Lab members.

## Results/Discussion

### Cool method is cool

| Right-aligned | Centered | Left-algined |
|--------------:|:--------:|:-------------|
| Cool method   | 3:45     | Awesome!     |
| Boring method | 10:22    | Boooo        |

<sub>**Table 1.** Table title. Columns are...</sub>

Compared cool method and boring method.

### Interesting result

![](images/fig1.png)

<sub>**Figure 1.** Plot title. **A.** Panel title. Fizz count on X-axis, buzz
count on Y-axis. Colored by coolness. **B.** Next panel title...</sub>

Cool method found a result. Relevant code is in [GitHub][CoolScript]

## Conclusion

We should use Cool Method more often.

## References

<sub>Chen D, Chitre A, Cheng R, Peng B, Polesskaya O, Palmer A. 2023. Palmer Lab
Heterogeneous Stock Rats Genotyping Pipeline.
doi:[10.5281/zenodo.10002191][Chen2023].</sub>

<sub>Gileta AF, Gao J, Chitre AS, Bimschleger HV, St. Pierre CL, Gopalakrishnan
S, Palmer AA. 2020. Adapting Genotyping-by-Sequencing and Variant Calling for
Heterogeneous Stock Rats. *G3 Genes|Genomes|Genetics*. 10(7):2195–2205.
doi:[10.1534/g3.120.401325][Gileta2020].</sub>

[Chen2023]: https://doi.org/10.5281/zenodo.10002191
[CoolMethod]: https://example.com
[CoolScript]: https://github.com/Palmer-Lab-UCSD/<yourRepo>/blob/main/<script>
[CoreB]: https://ratgenes.org/cores/core-b/
[Cowplot]: https://wilkelab.org/cowplot
[Ggplot2]: https://ggplot2.tidyverse.org/
[Gileta2020]: https://doi.org/10.1534/g3.120.401325
[GitHub]: https://github.com/Palmer-Lab-UCSD/<yourRepo>
[HWE]: https://www.biologysimulations.com/post/how-to-use-chi-squared-to-test-for-hardy-weinberg-equilibrium
[MRatBN72]: https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_015227675.2/
[ORCID]: https://orcid.org/<yourORCID>
[OurResearch]: https://palmerlab.org/our-research/
[RProject]: https://www.r-project.org/
[PLINK]: https://www.cog-genomics.org/plink/2.0/
[STITCH]: https://github.com/rwdavies/STITCH
[UCSDLibraryGenotypes]: https://doi.org/10.6075/J0CR5TKW