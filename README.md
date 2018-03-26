# c-genie

Estimating the sizes of coalescent genes ("c-genes") and single-topology tracts.

#### Summary

Scripts in this repository allow the estimation of the sizes of coalescent genes (termed "c-genes" by Doyle 1995) and single-topology tracts (genomic regions sharing the same topology) given a species tree and estimates for the population size and the recombination rate. The resulting estimates are based on the assumption that the phylogeny is in fact the true species tree, that the population size is constant and equal for all species, and that the recombination rate is homogeneous across the genome or according to a provided recombination map.

<!-- #### Background

To be written
 -->
<!-- #### Requirements

To be written
 -->
<!-- #### c-genie input

To be written
 -->
#### Running c-genie

Run with e.g.
`./c-genie primates.tre primates.html -l 100000 -n 100000 -t 100000 -c 7`

<!-- #### c-genie output

To be written
 -->
#### References
* Doyle JJ (1995) The irrelevance of allele tree topologies for species delimitation, and a non-topological alternative. Systematic Botany, 20, 574–588.
