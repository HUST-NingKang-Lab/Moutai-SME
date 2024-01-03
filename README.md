# Moutai-SME
The codes, mathematical equations，softwares and data sources involved in Moutai-SME project.

### The necessary resources of softwares and databases had been provided as following.
|   **Softwares**  |      **Version**      |                   **Reference**                   |                   **Identifier**                  |
|:---------------------------:|:---------------------:|:----------------------------------------------:|:-------------------------------------------------:|
|         Trimmomatic         |         v0.38         |  https://doi.org/10.1093/bioinformatics/btu170 |      https://github.com/usadellab/Trimmomatic     |
|           MEGAHIT           |         v1.1.2        |  https://doi.org/10.1093/bioinformatics/btv033 |         https://github.com/voutcn/megahit         |
|            QUAST            |         v5.0.2        |  https://doi.org/10.1093/bioinformatics/btt086 |           https://github.com/ablab/quast          |
|           MetaWRAP          |         v1.2.2        |    https://doi.org/10.1186/s40168-018-0541-1   |         https://github.com/bxlab/metaWRAP         |
|           CheckM            |        v1.0.18        |      https://doi.org/10.1101/gr.186072.114     |         https://github.com/tribe29/checkmk        |
|          Prodigal           |         v2.6.3        |    https://doi.org/10.1186/1471-2105-11-119    |        https://github.com/hyattpd/Prodigal        |
|            Prokka           |        v1.14.5        |  https://doi.org/10.1093/bioinformatics/btu153 |         https://github.com/tseemann/prokka        |
|           MMseqs2           |         v4.8.1        |  https://doi.org/10.1093/bioinformatics/btq003 |       https://github.com/soedinglab/MMseqs2       |
|          KofamScan          |         v1.3.0        |  https://doi.org/10.1093/bioinformatics/btz859 | https://github.com/rotheconrad/KEGGDecoder-binder |
|           DIAMOND           |      v2.0.14.152      |       https://doi.org/10.1038/nmeth.3176       |     https://github.com/python-diamond/Diamond     |
|           DeepARG           |         v1.0.2        |    https://doi.org/10.1186/s40168-018-0401-z   |         https://github.com/Deeparg/Deeparg        |
|        eggNOG-mapper        |         v2.1.6        |     https://doi.org/10.1093/molbev/msab293     |     https://github.com/eggnogdb/eggnog-mapper     |
|          antiSMASH          |         v6.0.0        |       https://doi.org/10.1093/nar/gkab335      |       https://github.com/antismash/antismash      |
|          BiG-SCAPE          |         v1.1.5        |    https://doi.org/10.1038/s41589-019-0400-9   |     https://github.com/medema-group/BiG-SCAPE     |
|             dRep            |         v3.4.0        |     https://doi.org/10.1038/ismej.2017.126     |           https://github.com/MrOlm/drep           |
|           GTDB-tk           |         v2.1.1        | https://doi.org/10.1093/bioinformatics/btac672 |       https://gtdb.ecogenomic.org/downloads       |
|        **Databases**        | **Date for download** |                   **Reference**                   |                   **Identifier**                  |
|            eggNOG           |     v5.0; 2022_12     |       https://doi.org/10.1093/nar/gky1085      |       http://eggnog5.embl.de/#/app/downloads      |
|             KEGG            |        2022_12        |       https://doi.org/10.1093/nar/gkaa970      |    http://kobas.cbi.pku.edu.cn/kobas3/download/   |
|             COG             |        2022_12        |       http://oi.org/10.1093/nar/gkaa1018       |          http://www.ncbi.nlm.nih.gov/COG/         |
|              GO             |        2022_12        |        http://oi.org/10.1093/nar/gky1055       |              http://geneontology.org/             |
|            CAZyDB           |        2022_12        |       https://doi.org/10.1093/nar/gkn663       |                http://www.cazy.org/               |
|              EC             |        2022_12        |       http://oi.org/10.1093/nar/28.1.304       |        https://enzyme.expasy.org/index.html       |
|             CARD            |        2022_12        |       https://doi.org/10.1093/nar/gkz935       |         https://card.mcmaster.ca/download         |
|             VFDB            |        2022_12        |       https://doi.org/10.1093/nar/gki008       |       http://www.mgc.ac.cn/VFs/download.htm       |
|             GTDB            |        2022_12        | https://doi.org/10.1093/bioinformatics/btac672 |       https://gtdb.ecogenomic.org/downloads       |
|         Swiss-sport         |        2022_12        |      https://doi.org/10.1093/nar/gkac1052      |              https://www.uniprot.org/             |
|            TrEMBL           |        2022_12        |      https://doi.org/10.1093/nar/gkac1052      |              https://www.uniprot.org/             |
|           UniRef50          |        2022_12        |  https://doi.org/10.1093/bioinformatics/btm098 |              https://www.uniprot.org/             |
|             Pfam            |        2022_12        |               https://doi.org/10.1093/nar/gkaa913              |            http://pfam-legacy.xfam.org/           |

### The concepts involved in Moutai-SME project.
|   **Name**  |      **Introduction**      |
|:---------------------------:|:---------------------:|
| MSSSF (Multi-stage solid-state fermentation) | SSF (Solid-state fermentation) is a process where there is a porous solid substrate or support for the growth of microorganisms, with a continuous gas phase. MSSSF is a kind of SSF, which has several fermentation stages |
| SME (Starter microbiota engraftment) | SME means that starter is added to the fermentation system before each round of fermentation stages and mixed with fermented grains. In this process, the bacteria in the starter is transplanted into the fermentation system |
| Fermentation triad | The pre-SME recipient, the post-SME recipient and the corresponding donor |
| Distance (post_FGijk, donori) |	The Bray-Curtis distance between post-recipient and donor |  
| Distance (pre_FGi, post_FGijk) |	The Bray-Curtis distance between pre-recipient and donor |
| Mean distance (pre_FGi, donori) |	Mean of distance between post recipient and donor |
| Mean distance (pre_FGi, post_FGi) |	Mean of distance between post recipient and pre_recipient |
| QER (pre_FGi, donori) | Quatative engraftment rate between post recipient and donor |
| QER (pre_FGi, post_FGi) |	Quatative engraftment rate between post recipient and pre_recipient |
| SSW (pre_FGi, donori) |	Sum of Squares Within groups of distance between post recipient and donor |
| SSW (pre_FGi,post_FGijk) | Sum of Squares Within groups of distance between post_recipient and pre_recipient |
| dfwithini |	The degrees of freedom within groups |
| The labels of LASSO-regularized linear regression |	Thresholds are set based on the engraftment rate and S2FG to determine the label of lasso |

### The mathematical equations for calculating the QER index.
We used the relative abundance of microbes of each sample to calculate the Bray‒Curtis distance in the pair of starter vs. post-FG, as well as in the pair of post-FG vs. pre-FG (Figure 3a). The Bray‒Curtis distance between post-FG and starter samples Distance(post_FG_ijk,donor_i), and post-FG and pre-FG samples Distance(pre_FG_i,post_FG_ijk) was calculated by the vegdist() function in R “vegan” package (v2.6-2), in which i {1,2,3,4,5,6}┤ (for example, i=1 represents SME1), j represents the time point in the SMEi process, and k represents the sample k at the j time point in the SMEi process (Figure 3a).
The calculation of QER index is shown as following:
- The mean distance between post-FG and starter samples can be calculated as
$$Mean distance(\post_FG_i\,donor_i)=∑_j∑_kDistance(post_FG_ijk,donor_i)/n_i$$
- The mean distance between post-FG and pre-FG samples can be calculated as
```
Mean distance(pre_FG_i,post_FG_i )=∑_j∑_kDistance(post_FG_ijk,pre_FG_i)/n_i
```
- n_i represents the number of samples in SMEi process
- We calculated the sum of the squares within (SSW) of sample distance to calculate the quantitative engraftment rate (QER) value in each SME process. The SSW(post_FG_i,donor_i) can be calculated as
```
SSW(post_FG_i,donor_i)=∑_j∑_k(Distance(post_FG_ijk,donor_i)-(∑_kDistance(post_FG_ijk,donor_i)))^2 
```
- The SSW(pre_FG_i,post_FG_ijk ) can be calculated as
```
SSW(pre_FG_i,post_FG_i )=∑_j∑_k(Distance(post_FG_ijk,pre_FG_i )-(∑_kDistance(post_FG_ijk,pre_FG_i)))^2 
```
- The inter-group degree of freedom (df_within_i) in a SME process is the total degree of freedom (n_i) minus the number of time points (m_i,{9,10,8,9,8,5}) and then minus 1, which can be expressed as
```
df_within_i=n_i-m_i-1
```
- Then the QER(post_FG_i,donor_i ) is calculated by
```
QER(post_FG_i,donor_i )=SSW(post_FG_i,donor_i )/df_within_i
```
- The QER(pre_FG_i,post_FG_i ) is calculated by
```
QER(pre_FG_i,post_FG_i )=SSW(pre_FG_i,post_FG_i )/df_within_i
```
