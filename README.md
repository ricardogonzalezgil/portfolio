# Data Analyst and Ecologist

My complete CV (last updated November 2024) can be [downloaded here](https://github.com/ricardogonzalezgil/portfolio/blob/main/202411_CV_RGG_Data_Analyst_Ecologist.pdf).

## Table of Contents
- [IT Skills](#it-skills)
- [Education](#education)
- [Work Experience](#work-experience)
- [Projects](#projects)
- [Scientific Visuals Gallery](#scientific-visuals-gallery)
- [Publications](#publications)

<a id="it-skills"></a>
## IT Skills 🖥️

- **Statistical and Data Analysis**: **R programming** (primary tool for most data analysis). Also: Matlab, SPSS, PRIMER, SURFER.
- **Geographic Information Systems (GIS) and Oceanography**: QGIS, Ocean Data View.
- **Version Control and Collaboration**:  Git-related tools (Git, GitLab, GitHub), collaborative platforms (Google Docs, Google Sheets, Trello, Notion, Microsoft Teams, Slack).
- **Design and Visualization**: Inkscape, GIMP, Photoshop.
- **Office Productivity**: Microsoft Office Suite (Word, Excel, PowerPoint).

<a id="education"></a>
## Education 🎓

- **PhD, Marine Ecology**: University of Oviedo (_February 2016_)								       		
- **MSc, Marine Biodiversity and Conservation**: IMBRSea; previously EMBC (_June 2010_)	 			        		
- **BSc, Biology**: University of Oviedo (_June 2008_)

<a id="work-experience"></a>
## Work Experience 💼

- **Blue Economy Coordinator for Latin America and the Caribbean (LAC)**: GOAL (_July 2023-September 2024_)
- **Consultant in marine ecology and data analysis**: Roatan Marine Park, RMP (_July 2023_)
- **Consultant in data analysis**: Coral Reef Alliance, CORAL (_April-June 2023_)
- **Fisheries researcher**: University of Oviedo (_August 2022-April 2023_)
- **Consultant in fisheries, marine ecology and data analysis**: Coral Reef Alliance, CORAL (_May-August 2022_)
- **Consultant in marine ecology and data analysis for aquaculture sustainability**: Blue Remediation Ltd. (_September 2021-March 2023_)
- **Postdoctoral researcher**: University of Strathclyde, Dept. of Mathematics and Statistics (_February 2018-January 2020_)  
- **Fisheries researcher**: University of Oviedo (_June-December 2017_) 

<a id="projects"></a>
## Projects 🚀

### Assigning positions in blocks of repeated elements in a vector: a performance comparison in R. 

For the full exercise with code, visit this [🔗 link](https://ricardogonzalezgil.github.io/analysis-assign-positions-rep-elements-rgg/).

This exercise explores four methods for assigning positions within consecutive, repeated elements in a vector, efficiently labeling sequences of a target value while keeping other values unchanged. For example, given a vector like 0 0 0 1 1 1 1 0 0 1 1 0 0 0 1 1 1 1 0 0 0 0 0, the desired output is 0 0 0 1 2 3 4 0 0 1 2 0 0 0 1 2 3 4 0 0 0 0 0, a need that arises in various applications such as time series analysis (identifying trends and patterns in sequential data), genomic sequence processing (assigning positions in repeated nucleotides or amino acid sequences), and text data manipulation (detecting and processing repeated words, phrases, or characters). To address these diverse use cases, I developed generalized function versions for four different methods and tested their efficiency across vectors of varying lengths, scaling up to 1 × 10⁶ elements (Figs. 1 and 2). The key takeaways are:

  1. Different approaches yield the same result with varying trade-offs in efficiency, readability, and flexibility.
  2. **rle** is the best choice when speed is critical. 
  3. Benchmarking is essential for selecting methods in large-scale data processing.
  4. Alternative implementations not covered here may further optimize performance.

 
![Fig. 1: Performance comparison](/images/methods_comparison_fig1-1.png) 

![Fig. 2: Performance comparison for each vector length](/images/methods_comparison_fig2-1.png)  

<a id="scientific-visuals-gallery"></a>
## Scientific Visuals Gallery 📈

### Research Figures 

A collection of collages featuring selected plots and plot fragments from my research contributions, showcasing different ways I visualize data. These highlight the final visualization results rather than full analytical workflows. To explore the complete set of plots, click on the corresponding paper links. For a full list of publications, see the [Publications](#publications) section.

---

González-Gil, R., Banas, N. S., Bresnan, E., & Heath, M., R. (2022). The onset of the spring phytoplankton bloom in the coastal North Sea supports the Disturbance Recovery Hypothesis. Biogeosciences (highlight paper), 19, 2417-2426. DOI: [10.5194/bg-19-2417-2022](https://doi.org/10.5194/bg-19-2417-2022)

![DRH paper gallery](/images/Bloom_DRH_N_Sea.png)  

González-Gil, R., Taboada, F. G., Cáceres, C., Largier, J. L. & Anadón, R. (2018). Winter mixing preconditioning of the spring phytoplankton bloom in the Bay of Biscay. Limnology and Oceanography, 63(3), 1039-1447. DOI: [10.1002/lno.10769](https://doi.org/10.1002/lno.10769)

![Spring bloom onset C Sea paper gallery](/images/Spring_bloom_onset_C_Sea.png)

González-Gil, R., Taboada, F. G., Höfer, J., & Anadón, R. (2015). Winter mixing and coastal upwelling drive long-term changes in zooplankton in the Bay of Biscay (1993–2010). Journal of Plankton Research, 37(2), 337–351. DOI: [10.1093/plankt/fbv001](https://doi.org/10.1093/plankt/fbv001)

![Zooplankton C Sea paper gallery](/images/Zooplankton_C_Sea.png)

### Graphical Abstracts

Visual summaries of some of my research papers, designed to communicate complex findings in a concise and engaging format.

---

González-Gil, R., Taboada, F. G., Cáceres, C., Largier, J. L. & Anadón, R. (2018). Winter mixing preconditioning of the spring phytoplankton bloom in the Bay of Biscay. Limnology and Oceanography, 63(3), 1039-1447. DOI: [10.1002/lno.10769](https://doi.org/10.1002/lno.10769)

Download the graphical abstract [here](https://github.com/ricardogonzalezgil/portfolio/blob/main/images/Gr_abstr_winter_mixing_spring_bloom_RGG_et_al_2017_LO_v3.0_350dpi.png)

![Grph. abstract Spring bloom onset C Sea paper](/images/Gr_abstr_winter_mixing_spring_bloom_RGG_et_al_2017_LO_v3.0_350dpi.png)

González-Gil, R., Taboada, F. G., Höfer, J., & Anadón, R. (2015). Winter mixing and coastal upwelling drive long-term changes in zooplankton in the Bay of Biscay (1993–2010). Journal of Plankton Research, 37(2), 337–351. DOI: [10.1093/plankt/fbv001](https://doi.org/10.1093/plankt/fbv001)

Download the graphical abstract [here](https://github.com/ricardogonzalezgil/portfolio/blob/main/images/Zooplankton_graphical_abstract_3_copyright_Graphical_abstract_350ppp.png)

![Grph. abstract Zooplankton C Sea paper](/images/Zooplankton_graphical_abstract_3_copyright_Graphical_abstract_350ppp.png)

<a id="publications"></a>
## Publications 📝

### Peer-Reviewed Articles

- Simmonds, E. G., et al. (2023). Recommendations for quantitative uncertainty consideration in ecology and evolution. Trends in Ecology & Evolution, 39(4), 328-337. DOI: [10.1016/j.tree.2023.10.012](https://doi.org/10.1016/j.tree.2023.10.012) 

- Simmonds, E. G., et al. (2022). Insights into the quantification and reporting of model-related uncertainty across different disciplines. iScience, 25(12), 105512. DOI: [10.1016/j.isci.2022.105512](https://doi.org/10.1016/j.isci.2022.105512)

- Izquierdo, P., Rico, J. M., Taboada, F. G., González-Gil, R., & Arrontes, J. (2022). Characterization of marine heatwaves in the Cantabrian Sea, SW Bay of Biscay. Estuarine, Coastal and Shelf Science, 274, 107923. DOI: [10.1016/j.ecss.2022.107923](https://doi.org/10.1016/j.ecss.2022.107923)
  
- Izquierdo, P., Taboada, F. G., González-Gil, R., Arrontes, J., & Rico, J. M. (2022). Alongshore upwelling modulates the intensity of marine heatwaves in a temperate coastal sea. Science of the Total Environment, 835, 155478. DOI: [10.1016/j.scitotenv.2022.155478](https://doi.org/10.1016/j.scitotenv.2022.155478)
  
- González-Gil, R., Banas, N. S., Bresnan, E., & Heath, M., R. (2022). The onset of the spring phytoplankton bloom in the coastal North Sea supports the Disturbance Recovery Hypothesis. Biogeosciences (highlight paper), 19, 2417-2426. DOI: [10.5194/bg-19-2417-2022](https://doi.org/10.5194/bg-19-2417-2022)
  
- Roa-Ureta, R. H., Fernández-Rueda, P., Acuña, J. L., Rivera, A., González-Gil, R., & García-Flórez, L. (2021). Estimation of the spawning stock and recruitment relationship of Octopus vulgaris in Asturias (Bay of Biscay) with generalized depletion models: implications for the applicability of MSY. ICES Journal of Marine Science, fsab113. DOI: [10.1093/icesjms/fsab113](https://doi.org/10.1093/icesjms/fsab113)

- Romero-Romero, S., González-Gil, R., Cáceres, C., Acuña, J. L. (2019). Seasonal and vertical dynamics in the trophic structure of a temperate zooplankton assemblage. Limnology and Oceanography, 64(5), 1939-1948. DOI: [10.1002/lno.11161](https://doi.org/10.1002/lno.11161)

- González-Gil, R., Taboada, F. G., Cáceres, C., Largier, J. L. & Anadón, R. (2018). Winter mixing preconditioning of the spring phytoplankton bloom in the Bay of Biscay. Limnology and Oceanography, 63(3), 1039-1447. DOI: [10.1002/lno.10769](https://doi.org/10.1002/lno.10769)

- Mesa, V., Gallego, J. L. R., González-Gil, R., Lauga, B., Sánchez, J., Méndez-García, C., Peláez, A. I. (2017). Bacterial, archaeal, and eukaryotic diversity across microhabitats in an acid mine drainage. Frontiers in Microbiology, 8(1756). DOI: [10.3389/fmicb.2017.01756](https://doi.org/10.3389/fmicb.2017.01756)

- Mesa, V., Navazas, A., González-Gil, R., González, A., Weyens, N., Lauga, B., Gallego, J. L. R., Sanchez, J. & Pelaez, A. I. (2017). Use of endophytic and rhizosphere bacteria to improve phytoremediation of arsenic-contaminated industrial soils by autochthonous Betula celtiberica. Applied and Environmental Microbiology, 83(8): e03411-16. DOI: [10.1128/AEM.03411-16](https://doi.org/10.1128/AEM.03411-16)

- González-Gil, R., Taboada, F. G., Höfer, J., & Anadón, R. (2015). Winter mixing and coastal upwelling drive long-term changes in zooplankton in the Bay of Biscay (1993–2010). Journal of Plankton Research, 37(2), 337–351. DOI: [10.1093/plankt/fbv001](https://doi.org/10.1093/plankt/fbv001)

- Rivera, A., Weidberg, N., Pardiñas, A. F., González-Gil, R., García-Flórez, L., & Acuña, J. L. (2013). Role of upwelling on larval dispersal and productivity of gooseneck barnacle populations in the Cantabrian Sea: management implications. PLoS ONE, 8(11): e78482. DOI: [10.1371/journal.pone.0078482](https://doi.org/10.1371/journal.pone.0078482)

- Taboada, F. G., Gil, R. G., Hofer, J., González, S. & Anadón, R. (2010). Trichodesmium spp. population structure in the eastern North Atlantic subtropical gyre. Deep Sea Research Part I: Oceanographic Research Papers, 57(1), 65-77. DOI: [10.1016/j.dsr.2009.09.005](https://doi.org/10.1016/j.dsr.2009.09.005)

### Book Chapters

- Fernández Rueda, M. del P., González Gil, R., & Acuña Fernández, J. L. (2023) The octopus trap fishery in western Asturias: an example of science-based sustainable management. In Díaz González, T.E., & Borrell Pichs, Y.J. (Coords.), La sostenibilidad de las pesquerías en el Principado de Asturias: ciencia, gestión y participación en una agenda regional hacia el 2030 (pp. 11-26). Oviedo: RIDEA. URI: [https://hdl.handle.net/10651/71357](https://hdl.handle.net/10651/71357)

- Bode, A., Álvarez-Ossorio, M. T., Anadón, R., González-Gil, R., López-Urrutia, Á., Miranda, A., & Valdés, L. (2012). Zooplancton. In A. Bode, A. Lavín, A., & L. Valdés (Eds.), Cambio climático y oceanográfico en el Atlántico del norte de España. Madrid: Instituto Español de Oceanografía, Ministerio de Ciencia e Innovación. URI: [https://digital.csic.es/handle/10261/321757](https://digital.csic.es/handle/10261/321757)


