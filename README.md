<h1 align="center">
  awsome-rna-3d-tools
</h1>

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->

**Table of Contents**

- [awsome-rna-tools](#awsome-rna-tools)
    - [RNA Toolbox](#rna-toolbox)
    - [RNA Structural databases](#rna-structural-databases)
    - [RNA 3D annotation](#rna-3d-annotation)
    - [RNA-Protein Docking](#rna-protein-docking)
    - [RNA Minimization/Optimize](#rna-minimizationoptimize)
    - [List of tools (at labs)](#list-of-tools-at-labs)
        - [RNApolis](#rnapolis)
            - [RNApolis – a virtual laboratory of RNA bioinformatics](#rnapolis--a-virtual-laboratory-of-rna-bioinformatics)
            - [Computational systems for quadruplexes](#computational-systems-for-quadruplexes)
            - [Other computational tools](#other-computational-tools)
        - [bgsu.edu](#bgsuedu)

<!-- markdown-toc end -->

# awsome-rna-tools
awesome tools for RNA
https://bio.tools/

(Quick and dirty dump of tools, by Category or by Labs, to be cleaned and improved over time)

## RNA Toolbox

- rna-tools: a toolbox to analyze sequences, structures and simulations of RNA (and more) docs @ http://rna-tools.rtfd.io web @ http://rna-tools.online https://github.com/mmagnus/rna-tools `pip install rna-tools`

## RNA Structural databases

- http://rna.bgsu.edu/rna3dhub
- RNAsolo - database of cleaned PDB-derived RNA 3D structures https://rnasolo.cs.put.poznan.pl

## RNA 3D annotation

- RNAspider A webserver to analyze entanglements in RNA 3D structures https://rnaspider.cs.put.poznan.pl/

## RNA-Protein Docking

- NPDock (Nucleic acid-Protein Dock) is a web server for modeling of RNA-protein and DNA-protein complex structures http://genesilico.pl/NPDock

## RNA Minimization/Optimize

- BRiQ - Xiong, P., Wu, R., Zhan, J. & Zhou, Y. Pairing a high-resolution statistical potential with a nucleobase-centric sampling algorithm for improving RNA model refinement. Nat Commun 12, 2777 (2021). https://www.nature.com/articles/s41467-021-23100-4 https://github.com/Jian-Zhan/RNA-BRiQ

- QRNAS - Stasiewicz, J., Mukherjee, S., Nithin, C. & Bujnicki, J. M. QRNAS: software tool for refinement of nucleic acid structures. BMC Struct. Biol. 19, 5 (2019). http://genesilico.pl/qrnas https://bmcstructbiol.biomedcentral.com/articles/10.1186/s12900-019-0103-1 https://github.com/sunandanmukherjee/QRNAS

> CYANA (Güntert and Buchner 2015), NAMD (Phillips et al. 2020), XPLOR-NIH (Schwieters et al. 2003)—for the preliminary models or ensuring a proper stereochemistry from the early stages of prediction. One can also process the predicted RNA structures using tools—for example, RNAfitme (Zok et al. 2015; Antczak et al. 2018) or QRNAS (Stasiewicz et al. 2019)—having the potential to refine the nucleic acid structure. [^1]

- PYMOL https://pymolwiki.org/index.php/Optimize https://pymolwiki.org/index.php/Molecular_Sculpting 

- Chimera https://www.cgl.ucsf.edu/chimera/current/docs/ContributedSoftware/minimize/minimize.html

## List of tools (at labs)
### RNApolis

- https://github.com/RNApolis
- https://www.cs.put.poznan.pl/mszachniuk/site/research-grants/

#### RNApolis – a virtual laboratory of RNA bioinformatics

- RNAssess	webserver for quality assessment of RNA 3D structures 
- RNAComposer	fully automated RNA structure prediction server
- RNAfitme	webserver for modeling nucleobase and nucleoside residue conformation in fixed-backbone RNA structures 
- RNA FRABASE	RNA FRAgments dataBASE and search engine
- RNAhugs*	webserver for RNA 3D structure alignment 
- RNAloops	database of RNA multiloops 
- RNAlyzer	framework for quality analysis of RNA models 
- RNApdbee	multifunctional webserver tool for RNA structure annotation
- RNAQUA	computational tool for RNA QUality Assessment 
- RNAspider	webserver to analyze entanglements in RNA 3D structures 
- RNAsolo	database of cleaned PDB-derived RNA 3D structures 
- RNAtango*	webserver for torsion-angle based similarity analysis of RNA 3D structures 
- RNAthor	webserver for the automatic normalization of RNA probing data 
- RNAtive	webserver to rank 3D RNA models and infer the native 
- RNAvista	webserver to assess RNA secondary structures with non-canonical base pairs 
- MCQ4Structures  standalone app to compute torsion angle-based similarity of molecule structures 

#### Computational systems for quadruplexes

- DrawTetrado	standalone app to draw layer diagrams representing quadruplex structures 
- ElTetrado	standalone app for identification and classification of tetrads and quadruplexes 
- ONQUADRO	database of tetrads, quadruplexes, and G4-helices 
- WebTetrado*	webserver to annotate and visualize quadruplexes in nucleic acid 3D structures 

#### Other computational tools

- SMERFA*	structural, muscular and elastic RNA finder and aligner 
- Virxicon	a lexicon of viral sequences 

### bgsu.edu
https://www.bgsu.edu/research/rna/web-applications.html

Currently we are hosting 4 web applications for analyzing RNA 3D structure:

- WebFR3D - server for finding and superimposing RNA 3D motifs
- R3D Align -  global pairwise alignment of RNA 3D structures using local superpositions
- JAR3D - predicting RNA 3D motifs in sequences
- R3D-2-MSA Server - server for accessing alignments from 3d structures

(ref in Nature style)

[^1]: Carrascoza, F., Antczak, M., Miao, Z., Westhof, E. & Szachniuk, M. Evaluation of the stereochemical quality of predicted RNA 3D models in the RNA-Puzzles submissions. Rna 28, 250–262 (2022)
