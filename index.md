---
title       : "Ancient DNA 1: Molecular Phylogenetics"
subtitle    : "BIOL14406: Living Systems"
author      : Dr Axel Barlow
job         : "email: axel.barlow@ntu.ac.uk, office: IBRC115"
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : zenburn      # {zenburn, tomorrow, solarized-dark, ...}
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
logo        : ntu-shield.png
biglogo     : NTU_open-graph.png
assets      : {assets: ../../assets}
license     : by-nc-sa
github:
  user: draxelbarlow
  repo: BIOL14406_aDNA1
  branch: "gh-pages"
---



<!-- adding bold and italic options -->
<style>
em {
  font-style: italic
}
strong {
  font-weight: bold;
}
</style>

## Ancient DNA lectures in living systems

- Phylogeny and tree of life
- Fossils and the fossil record
- DNA
- DNA sequences (phage genomes)
- Mitochondria

<img src="./assets/img/smilodon1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" width="45%" style="display: block; margin: auto 0 auto auto;" />

--- .class #id

## Paijmans et al. 2017

<embed src="./assets/img/Paijmans et al. - 2017.pdf" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" width="100%" height="500" type="application/pdf" />

--- .class #id

## Molecular phylogenetics

- What is a phylogeny and how do we calculate them?
- Genetics, mutation and inheritance
- The mitochondrial genome

--- &twocol bg:white

## You already seen diagrams like this...

### This is called a `phylogeny`. It represents the evolutionary process

*** =right

<img src="assets/fig/unnamed-chunk-3-1.png" title="plot of chunk unnamed-chunk-3" alt="plot of chunk unnamed-chunk-3" width="80%" style="display: block; margin: auto;" />

*** =left

- The phylogeny works like an evolutionary tree
- The tips are species
- The branches show their relationships
- Nodes represents common ancestors, from which new species evolved
- Generally, phylogenies are calculated using **genetic data**

--- .segue .dark 

## How does that work?

--- .class bg:white

<img src="./assets/img/mtDNA_tree.svg" title="plot of chunk unnamed-chunk-4" alt="plot of chunk unnamed-chunk-4" width="95%" style="display: block; margin: auto;" />

--- .class #id

## Inheritance plus mutation

- Errors in DNA replication (mutations) change the DNA sequence
- Human mutation rate is ~1.1×10−8 mutations per site per generation
- This means you carry ~40 mutations in your 3.6 Gb genome
- These differences are inherited by offspring
- Sequence divergence and time are (approximately) linearly related

### Phylogenetics works in reverse: we observe the DNA sequences and try to work out the tree that generated them

--- .class #id

## DNA sequence alignment

<img src="./assets/img/DNA_alingment.png" title="plot of chunk unnamed-chunk-5" alt="plot of chunk unnamed-chunk-5" width="90%" style="display: block; margin: auto;" />

--- .class #id

## Mitochondrial DNA is great for phylogenetics!

<img src="./assets/img/Mitochondrion_mini.svg" title="plot of chunk unnamed-chunk-6" alt="plot of chunk unnamed-chunk-6" width="70%" style="display: block; margin: auto;" />

--- &twocol

## Mitochondrial DNA is great for phylogenetics!

*** =right

<img src="./assets/img/Map_of_the_human_mitochondrial_genome.svg" title="plot of chunk unnamed-chunk-7" alt="plot of chunk unnamed-chunk-7" width="100%" style="display: block; margin: auto;" />

*Emmanuel Douzery, CC BY-SA 4.0*

*** =left

- Mitochondrial genome ~16 kb
- 13 protein-coding genes, 2 rRNAs and 22 tRNAs
- High mutation rate
- No recombination
- High copy number per cell

--- &thankyou

## Next time

**The study of ancient DNA**
