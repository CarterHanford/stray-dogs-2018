## Geospatial Analysis of the City of St. Louis <img src="https://slu-soc5650.github.io/images/logo.png" align="right" />

[![](https://img.shields.io/badge/semester-spring%202018-orange.svg)](https://github.com/CarterHanford/stray-dogs-2018)
[![](https://img.shields.io/badge/release-complete-green.svg)](https://github.com/CarterHanford/stray-dogs-2018)
[![](https://img.shields.io/github/repo-size/CarterHanford/stray-dogs-2018.svg)](https://github.com/CarterHanford/stray-dogs-2018)

### Introduction

This is the repository for my geospatial analysis project of the City of St. Louis. This project was completed while I was a student at Saint Louis University and it involves the analysis and evaluation of datasets from the `Citizen's Service Bureau` 2009-2015.  The raw data `(n = 786,355)` was downloaded from the CSB website, and one goal of the project is to clean the entire data set.  For this project, I focused on only one variable, or instance; `Stray Dog At Large`.  `Rstudio` was used to clean the data to get down to that point `(n = 4,666)`. 

Once the CSB data had been cleaned, the next goal of the project was to project the data into maps using `ArcMap`. Additional maps were created to understand racial and poverty trends in the city of St. Louis, as well as inset, ward, reference, and precint maps.  Once the data was ready, choropleth maps were created to display the distribution of the `Stray Dog At Large` variable across wards and precints.  Choropleth maps of race and poverty were also created in order to find similarities/differences between the number of stray dogs and race/poverty in the city. 

At the end of the project, I discovered a clear link between instances of stray dogs and racial/poverty trends in the city of St. Louis.  Higher instances of stray dogs were linked with higher African American populations, as well as higher poverty rates.  Inversely, lower instances of stray dogs were associated with lower African American populations and lower rates of poverty.  These trends can be identified by the thematic maps, located in the `ArcMap PDFs` folder. 

I presented my project and findings as an academic poster to my professor, Dr. Chris Prener, as well as my colleagues at the end of the semester.

### Repository Contents

* The `ArcMap PDF's` folder contains pdf's of all the maps created using ArcGIS, including the thematic maps of race, poverty, and CSB data, as well as reference and inset maps. 
* The `ArcMap projects` folder contains the actual ArcGIS project files used to create the maps.
* The `CSB Data Clean` folder contains the `R` project containing all of the programming code needed to clean the raw data, as well as the organized `R` notebook that documents my process.
* The `Stray Dogs Final Poster` pdf file in this repository is the final poster that I presented to Dr. Prener and my colleagues.

### Acknowledgements

I would like to specifically thank [Dr. Chris Prener](https://chris-prener.github.io/) for allowing me to publish this project on a public github repository to display my work.  I would also like to thank him personally for successfully teaching and providing the information necessary to complete this project.

I would also like to thank my two other teammates, Nigarhan Gurpinar & Marissa Colombo. We worked together long hours together formatting the maps and figuring out the code we needed throughout this project, and they were amazing to work with and together we were extremely satisfied with how the project turned out.

### About Carter Hanford

Carter Hanford is a Sociology B.A. student at `Saint Louis University` (SLU) with a minor in Mathematics. He attended `Jefferson College` prior to his time at SLU, playing baseball and obtaining an associates degree in Mathematics. Carter then transferred to SLU to pursue his education and play baseball at the NCAA Division 1 level. He continued to purse Mathematics, obtaining his minor, and also took an interest with Urban related issues in Sociology. During his time on the SLU Baseball team, Carter was a key contributor on the 2018 Atlantic-10 championship team, starting all 56 games at third base. Him and the team went on to compete on the national level, playing Ole Miss and Missouri State at the University of Mississippi on ESPN in front of 15,000+ fans. After his time at Saint Louis University, he hopes to move on to graduate school, studying data science or data analytics, or find a job in the data science field.

### About Saint Louis University <img src="https://slu-soc5650.github.io/images/sluLogo.png" align="right" />

Founded in 1818, [Saint Louis University](http://wwww.slu.edu) is one of the nation’s oldest and most prestigious Catholic institutions. Rooted in Jesuit values and its pioneering history as the first university west of the Mississippi River, SLU offers nearly 13,000 students a rigorous, transformative education of the whole person. At the core of the University’s diverse community of scholars is SLU’s service-focused mission, which challenges and prepares students to make the world a better, more just place.