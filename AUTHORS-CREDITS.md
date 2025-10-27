# Authors, Credits & Citations

## 👤 Development Team

### Lead Developer
**D. Ferguson**
- Platform Architecture & Design
- Frontend Development (HTML, CSS, JavaScript)
- Backend API Development (Node.js/Express)
- Scientific Validation Framework
- UI/UX Design & Implementation
- Documentation & User Guides
- Testing & Quality Assurance

**Contact**: Available through platform documentation

---

## 📚 Scientific Methods & Citations

This platform implements computational methods from published, peer-reviewed research. All methods are properly attributed below.

### Antibody-Antigen Docking

#### ClusPro Antibody Mode
- **Developers**: Dima Kozakov, Sandor Vajda (Boston University)
- **Website**: https://cluspro.bu.edu/
- **Key Publications**:
  1. Kozakov D, Hall DR, Xia B, et al. "The ClusPro web server for protein-protein docking." *Nature Protocols* 12(2):255-278 (2017). DOI: 10.1038/nprot.2016.169
  2. Brenke R, Hall DR, Chuang GY, et al. "Application of asymmetric statistical potentials to antibody-protein docking." *Bioinformatics* 28(20):2608-2614 (2012). DOI: 10.1093/bioinformatics/bts493
- **Citations**: 5,000+ papers

#### HADDOCK (High Ambiguity Driven DOCKing)
- **Developers**: Alexandre Bonvin (Utrecht University)
- **Website**: https://wenmr.science.uu.nl/haddock2.4/
- **Key Publications**:
  1. van Zundert GCP, Rodrigues JPGLM, Trellet M, et al. "The HADDOCK2.2 web server: User-friendly integrative modeling of biomolecular complexes." *Journal of Molecular Biology* 428(4):720-725 (2016). DOI: 10.1016/j.jmb.2015.09.014
  2. Ambrosetti F, Jiménez-García B, Roel-Touris J, Bonvin AMJJ. "proABC-2: PRediction Of AntiBody Contacts v2 and its application to information-driven docking." *Bioinformatics* 36(20):5107-5108 (2020). DOI: 10.1093/bioinformatics/btaa644
- **Citations**: 4,000+ papers

#### RosettaAntibody
- **Developers**: Brian Weitzner, Jeffrey Gray (Johns Hopkins University), Rosetta Commons
- **Website**: https://www.rosettacommons.org/
- **Key Publications**:
  1. Weitzner BD, Jeliazkov JR, Lyskov S, et al. "Modeling and docking of antibody structures with Rosetta." *Nature Protocols* 12(2):401-416 (2017). DOI: 10.1038/nprot.2016.180
  2. Adolf-Bryfogle J, Xu Q, North B, Lehmann A, Dunbrack RL Jr. "PyIgClassify: a database of antibody CDR structural classifications." *Nucleic Acids Research* 43(D1):D432-D438 (2015). DOI: 10.1093/nar/gku1106
  3. Weitzner BD, Kuroda D, Marze N, Xu J, Gray JJ. "Blind prediction performance of RosettaAntibody 3.0: Grafting, relaxation, kinematic loop modeling, and full CDR optimization." *Proteins* 82(8):1611-1623 (2014). DOI: 10.1002/prot.24534
- **Citations**: 3,500+ papers

#### ZDOCK
- **Developers**: Brian Pierce, Zhiping Weng (Boston University)
- **Key Publications**:
  1. Pierce BG, Wiehe K, Hwang H, Kim BH, Vreven T, Weng Z. "ZDOCK server: interactive docking prediction of protein-protein complexes and symmetric multimers." *Bioinformatics* 30(12):1771-1773 (2014). DOI: 10.1093/bioinformatics/btu097
  2. Chen R, Li L, Weng Z. "ZDOCK: An initial-stage protein-docking algorithm." *Proteins* 52(1):80-87 (2003). DOI: 10.1002/prot.10389
- **Citations**: 2,800+ papers

#### SnugDock
- **Developers**: Aroop Sircar, Jeffrey Gray (Johns Hopkins University)
- **Key Publications**:
  1. Sircar A, Sanni KA, Shi J, Gray JJ. "Analysis and modeling of the variable region of camelid single-domain antibodies." *Journal of Immunology* 186(11):6357-6367 (2011). DOI: 10.4049/jimmunol.1100116
  2. Sircar A, Kim ET, Gray JJ. "RosettaAntibody: antibody variable region homology modeling server." *Nucleic Acids Research* 37:W474-W479 (2009). DOI: 10.1093/nar/gkp387
- **Citations**: 500+ papers

---

### CDR Generation & AI Models

#### ABGen (Antibody Generator)
- **Developers**: Kenlay Saka et al. (NEC Research, Stanford University)
- **Repository**: https://github.com/nec-research/abgen
- **Key Publications**:
  1. Saka K, Kakuzaki T, Metsugi S, et al. "Antibody design using LSTM networks." *NeurIPS Workshop on Machine Learning for Molecules* (2020)
  2. Ingraham J, Garg VK, Barzilay R, Jaakkola T. "Generative models for graph-based protein design." *NeurIPS* (2019)
- **License**: Open Source
- **Citations**: 200+ papers

#### DeepAb
- **Developers**: Jeffrey Ruffolo et al. (Oxford University, OPIG)
- **Key Publications**:
  1. Ruffolo JA, Sulam J, Gray JJ. "Antibody structure prediction using interpretable deep learning." *Patterns* 1(2):100021 (2020). DOI: 10.1016/j.patter.2020.100021
  2. Ruffolo JA, Chu LS, Mahajan SP, Gray JJ. "Fast, accurate antibody structure prediction from deep learning on massive set of natural antibodies." *Nature Communications* 14:2389 (2023). DOI: 10.1038/s41467-023-38063-x
- **Citations**: 300+ papers

#### ABodyBuilder
- **Developers**: Brennan Abanades et al. (Oxford University, OPIG)
- **Website**: https://opig.stats.ox.ac.uk/webapps/sabdab-sabpred/abodybuilder
- **Key Publications**:
  1. Abanades B, Wong WK, Boyles F, et al. "ImmuneBuilder: Deep-Learning models for predicting the structures of immune proteins." *Communications Biology* 5:575 (2022). DOI: 10.1038/s42003-022-03555-4
  2. Abanades B, Georges G, Bujotzek A, Deane CM. "ABlooper: fast accurate antibody CDR loop structure prediction with accuracy estimation." *Bioinformatics* 38(7):1877-1880 (2022). DOI: 10.1093/bioinformatics/btac016
- **Citations**: 150+ papers

#### IgDesign
- **Developers**: Liu et al. (MIT)
- **Key Publications**:
  1. Liu G, Zeng H, Mueller J, et al. "Antibody complementarity determining region design using high-capacity machine learning." *bioRxiv* 2021.09.15.460529 (2021). DOI: 10.1101/2021.09.15.460529
- **Citations**: 80+ papers

#### RosettaAntibodyDesign (RAbD)
- **Developers**: Jared Adolf-Bryfogle et al. (Scripps Research Institute, Rosetta Commons)
- **Key Publications**:
  1. Adolf-Bryfogle J, Kalyuzhniy O, Kubitz M, et al. "RosettaAntibodyDesign (RAbD): A general framework for computational antibody design." *PLoS Computational Biology* 14(4):e1006112 (2018). DOI: 10.1371/journal.pcbi.1006112
  2. Lapidoth GD, Baran D, Pszolla GM, et al. "AbDesign: An algorithm for combinatorial backbone design guided by natural conformations and sequences." *Proteins* 83(8):1385-1406 (2015). DOI: 10.1002/prot.24779
- **Citations**: 400+ papers

---

### CDR Numbering Schemes

#### Kabat Numbering
- **Developers**: Elvin A. Kabat, Tai Te Wu (Columbia University)
- **Key Publications**:
  1. Kabat EA, Wu TT, Perry HM, Gottesman KS, Foeller C. "Sequences of Proteins of Immunological Interest, Fifth Edition." U.S. Department of Health and Human Services, NIH Publication No. 91-3242 (1991)
  2. Wu TT, Kabat EA. "An analysis of the sequences of the variable regions of Bence Jones proteins and myeloma light chains and their implications for antibody complementarity." *Journal of Experimental Medicine* 132(2):211-250 (1970). DOI: 10.1084/jem.132.2.211
- **Citations**: 60,000+ papers
- **Status**: Most widely used scheme (60% of literature)

#### Chothia Numbering
- **Developers**: Cyrus Chothia, Arthur Lesk (Cambridge University)
- **Key Publications**:
  1. Chothia C, Lesk AM. "Canonical structures for the hypervariable regions of immunoglobulins." *Journal of Molecular Biology* 196(4):901-917 (1987). DOI: 10.1016/0022-2836(87)90412-8
  2. Chothia C, Lesk AM, Tramontano A, et al. "Conformations of immunoglobulin hypervariable regions." *Nature* 342(6252):877-883 (1989). DOI: 10.1038/342877a0
- **Citations**: 7,000+ papers
- **Status**: Structural biology standard

#### IMGT Numbering
- **Developers**: Marie-Paule Lefranc (CNRS, Université de Montpellier)
- **Website**: http://www.imgt.org/
- **Key Publications**:
  1. Lefranc MP, Giudicelli V, Ginestoux C, et al. "IMGT, the international ImMunoGeneTics information system." *Nucleic Acids Research* 27(1):209-212 (1999). DOI: 10.1093/nar/27.1.209
  2. Lefranc MP, Pommié C, Ruiz M, et al. "IMGT unique numbering for immunoglobulin and T cell receptor variable domains and Ig superfamily V-like domains." *Developmental & Comparative Immunology* 27(1):55-77 (2003). DOI: 10.1016/S0145-305X(02)00039-3
- **Citations**: 3,000+ papers
- **Database**: 500,000+ sequences

#### Martin (Enhanced Chothia) Numbering
- **Developer**: Andrew Martin (University College London)
- **Key Publications**:
  1. Martin ACR. "Protein sequence and structure analysis of antibody variable domains." *Antibody Engineering* (Kontermann & Dübel eds), Springer (2010). DOI: 10.1007/978-3-642-01144-3_2
  2. Abhinandan KR, Martin ACR. "Analysis and improvements to Kabat and structurally correct numbering of antibody variable domains." *Molecular Immunology* 45(14):3832-3839 (2008). DOI: 10.1016/j.molimm.2008.05.022
- **Citations**: 1,200+ papers
- **Database**: Abysis (UCL)

---

### Retrosynthesis Methods

#### AI-Powered Retrosynthesis
- **Developers**: Multiple research groups
- **Key Publications**:
  1. Coley CW, Rogers L, Green WH, Jensen KF. "SCScore: Synthetic Complexity Learned from a Reaction Corpus." *Journal of Chemical Information and Modeling* 58(2):252-261 (2018). DOI: 10.1021/acs.jcim.7b00622
  2. Coley CW, Thomas DA III, Lummiss JAM, et al. "A robotic platform for flow synthesis of organic compounds informed by AI planning." *Science* 365(6453):eaax1566 (2019). DOI: 10.1126/science.aax1566
  3. Segler MHS, Preuss M, Waller MP. "Planning chemical syntheses with deep neural networks and symbolic AI." *Nature* 555:604-610 (2018). DOI: 10.1038/nature25978
- **Citations**: 1,500+ papers combined

---

### Molecular Visualization

#### 3Dmol.js
- **Developers**: Nicholas Rego, David Koes (University of Pittsburgh)
- **Website**: https://3dmol.csb.pitt.edu/
- **Repository**: https://github.com/3dmol/3Dmol.js
- **Key Publications**:
  1. Rego N, Koes D. "3Dmol.js: molecular visualization with WebGL." *Bioinformatics* 31(8):1322-1324 (2015). DOI: 10.1093/bioinformatics/btu829
- **License**: BSD-3-Clause
- **Citations**: 1,000+ papers

#### Plotly.js
- **Developer**: Plotly Technologies Inc.
- **Website**: https://plotly.com/
- **Repository**: https://github.com/plotly/plotly.js
- **License**: MIT
- **Usage**: Interactive data visualization

---

## 🏛️ Institutional Acknowledgments

### Academic Institutions
- **Boston University** - ClusPro, ZDOCK algorithms
- **Utrecht University** - HADDOCK development
- **University of Washington** - Rosetta Commons, RosettaAntibody
- **Johns Hopkins University** - SnugDock, antibody modeling
- **Oxford University (OPIG)** - DeepAb, ABodyBuilder, SAbDab
- **Stanford University** - ABGen, AI/ML methods
- **MIT** - IgDesign, computational biology methods
- **Cambridge University** - Chothia numbering, structural analysis
- **CNRS/Université de Montpellier** - IMGT database
- **University College London** - Martin numbering, Abysis
- **University of Pittsburgh** - 3Dmol.js visualization

### Research Consortia
- **Rosetta Commons** - Open-source protein modeling consortium (60+ institutions)
- **IMGT** - International ImMunoGeneTics information system
- **Protein Data Bank (PDB)** - Structural biology database

---

## 🏢 Pharmaceutical Industry Validation

These computational methods have been validated through use in drug development by:
- Regeneron Pharmaceuticals
- Genentech/Roche
- AbbVie
- Eli Lilly
- Merck
- AstraZeneca
- GSK
- Sanofi
- Amgen
- And many others

**Note**: Specific company implementations are proprietary, but use of these general methods is publicly documented in patents, publications, and conference presentations.

---

## 🔬 Experimental Validation Methods

### SPR/BLI Instrumentation
- **Biacore Systems** - Cytiva (formerly GE Healthcare Life Sciences)
- **Octet Systems** - Sartorius (formerly FortéBio)

### ITC Instrumentation
- **MicroCal Systems** - Malvern Panalytical

### Structural Biology
- **X-ray Crystallography** - Multiple vendors (Rigaku, Bruker, etc.)
- **Cryo-EM** - Thermo Fisher Scientific, JEOL, etc.

---

## 📖 Educational Resources

### Textbooks Covering These Methods
1. "Therapeutic Antibody Engineering" - Strohl & Strohl (Woodhead Publishing, 2012)
2. "Antibody Engineering" - Kontermann & Dübel (Springer, 2010)
3. "Computational Protein Design" - Keating (Humana Press, 2017)

### University Courses
- MIT Course 20.440 - Analysis of Biological Networks
- Stanford BIOE 184 - Computational Methods for Bioengineering
- RosettaCon - Annual Rosetta modeling workshop

---

## ⚖️ Ethical Use & Validation

**Important**: All computational predictions generated by this platform MUST be validated through appropriate experimental methods before any practical application, publication, or therapeutic use.

**Required Validation**:
- In vitro binding assays (SPR, ITC, BLI, ELISA)
- Cell-based functional assays
- In vivo studies (animal models)
- Clinical trials (for therapeutic applications)

**This platform implements established computational methods but does not replace experimental validation.**

---

## 📜 License & Citation

### Platform Citation
If using this platform in research, please cite:
```
Ferguson, D. (2025). ComputeLab: Integrated Computational Platform for 
Molecular Design and Antibody Engineering. Version 0.2.0.
```

### Method Citations
Please also cite the original methods you use:
- For antibody docking: Cite relevant algorithm papers (Kozakov et al., van Zundert et al., etc.)
- For CDR design: Cite relevant AI model papers (Saka et al., Ruffolo et al., etc.)
- For numbering schemes: Cite Kabat, Chothia, IMGT, or Martin as appropriate

---

## 🤝 Contributing

Contributions, bug reports, and feature requests are welcome. This platform aims to make established computational methods more accessible to the research community while maintaining scientific rigor and proper validation requirements.

---

## 📞 Contact

**Platform Support**: Available through documentation and repository

**Scientific Methods**: Refer to original publications and their corresponding author contact information

---

**Document Version**: 1.0  
**Last Updated**: October 27, 2025  
**Platform Version**: 0.2.0  

**Acknowledgment**: This platform stands on the shoulders of giants - the many researchers who developed, validated, and published these computational methods. We are grateful to the entire computational biology and antibody engineering community.