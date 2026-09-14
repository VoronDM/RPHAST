# RPHAST: Phylogenetic Analysis with Space/Time Models in R



RPHAST is an R interface to the [PHAST](http://compgen.cshl.edu/phast/) software package. It contains much of the functionality of phast within a highly-developed statistical programming environment, and is easy and fun to use. 





# Download and Install


To install the latest version of the package directly from github using the devtools package, use the command in R:

      devtools::install_github("VoronDM/RPHAST")

or

      pak::pak("VoronDM/RPHAST")

      
  
# Documentation


| PDF  | Sweave Source | Description |
| ------------- | ------------- |------------- |
| [Vignette1.pdf](http://compgen.cshl.edu/rphast/vignette1.pdf)  | [Vignette1.Rnw](http://compgen.cshl.edu/rphast/vignette1.Rnw)  | Read in alignment and features, estimate neutral model based on 4d sites using phyloFit, run phyloP and phastCons |
| [Vignette2.pdf](http://compgen.cshl.edu/rphast/vignette2.pdf)  | [Vignette2.Rnw](http://compgen.cshl.edu/rphast/vignette2.Rnw)  | Detect rodent-accelerated regions using a multiple species alignment of human chromosome 22, assess significance by simulation |
| [Vignette3.pdf](http://compgen.cshl.edu/rphast/vignette3.pdf)  | [Vignette3.Rnw](http://compgen.cshl.edu/rphast/vignette3.Rnw)  | Create custom phylogenetic HMM which models a transcription factor binding site; verify the model on a simulated alignment |
| [Vignette4.pdf](http://compgen.cshl.edu/rphast/vignette4.pdf)  | [Vignette4.Rnw](http://compgen.cshl.edu/rphast/vignette4.Rnw)  | Introduction to detecting GC-biased gene conversion with RPHAST; nucleotide and phylo-HMM models |
| [RPHAST-Manual.pdf](http://compgen.cshl.edu/rphast/rphast-manual.pdf)  |   | RPHAST  Reference Manual |


# Publications

 [Hubisz MJ, Pollard KS, and Siepel A. PHAST and RPHAST: Phylogenetic Analysis with Space/Time Models. (in press, Briefings in Bioinformatics).](https://academic.oup.com/bib/article/12/1/41/244593)
 
 # Contact
 
Problems, questions, feature requests should be directed to [phasthelp@cshl.edu](phasthelp@cshl.edu).
