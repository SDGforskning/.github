# Welcome to SDG research strings!

This work consists of
- **Open search strings to find academic publications related each target and goal of the [Sustainable development goals](https://sdgs.un.org/goals)** (*Repo: sdg-strings*). These files include search blocks/hedges, in both Web of Science syntax and a python script,
and include detailed documentation of what the strings cover and why.
The [release of the current version is available on Zenodo](https://doi.org/10.5281/zenodo.7241689), and covers ten SDGs. The remaining six are currently under development (2025-26).
- **A tagger in python**, which can tag text or data in dataframes using these mappings (*Repo: sdg-tagger*). 
This is under development (2025-26), and will improve on and replace the python script in *sdg-strings*. Currently this supports English and Norwegian. 
- **A website, [baerekraftsforskning.no](https://baerekraftsforskning.no/)** which allows vistors to search or browse academic publications produced in Norway that are linked to the SDGs, and open versions of these (*Repo: find-sdg-research*). 

This work is co-ordinated by the library at the University of Bergen (Norway), in collaboration with the libraries at Western Norway University of Applied Sciences and the University of Stavanger. 
Contributing partners include Natural Resources Institute Finland (LUKE), OsloMet (Norway), University of Helsinki (Finland), Aalto University (Finland), Tampere University (Finland), and the Research Council of Norway. 
We recieved support from the National Library of Norway for development during 2021-2023.

## Why are we building strings, and how do they differ to existing mappings?

Previous research has shown that different mappings of SDG-"related" research do not agree very well ([Armitage, Lorenz & Mikki 2020](https://doi.org/10.1162/qss_a_00071), [Purnell 2022](https://doi.org/10.1162/qss_a_00215), [Turunen, Huuskonen & Sandgren 2023](https://doi.org/10.6084/m9.figshare.24278599.v1)). 
This is perhaps unsurprising when you consider that there are different ways to interpret what an SDG covers, different viewpoints on which research themes should be counted as "related", different mapping methods, 
and different data sources (see our previous work, [Armitage, Lorenz & Mikki 2020](https://doi.org/10.1162/qss_a_00071)). 
For example, should *SDG 3 Good health* cover all medical research? Does *SDG 13 Climate Action* cover basic climate science? You will probably get different answers depending on who you ask.

Instead of trying to find the "right" answer, we think multiple mappings (which can capture different views of relatedness) are a good idea. 
But in order for these to have meaning, documentation must explain a) what it is supposed to find (i.e. how the SDG was interpreted and what research is considered relevant), and 
b) how the mapping is done. We have written our own strings because we believe there is currently a gap for this kind of mapping. We also felt there was a gap for a mapping on SDG **target** level, an action-oriented mapping,
and we wanted to provide a version via Python which could search in any data and not only in English.

For more details about the mapping and how to use it, see the [sdg-strings README](https://github.com/SDGforskning/sdg-strings/blob/main/README.md).

## A short history

This work began in 2019, growing out of a concern when examining differences between SDG mappings ([Armitage, Lorenz & Mikki 2020](https://doi.org/10.1162/qss_a_00071)).
This led to the project *Bærekraftsforskning for alle – en transparent kartleggings- og gjenfinningstjeneste* (Sustainable development research for all – a transparent mapping and discovery tool), 
a Norwegian project supported by the National Library of Norway (2021-2023). **[Read more about the project and find contact details here](https://www.uib.no/en/ub/148804/sustainable-development-research-all-%E2%80%93-transparent-mapping-and-discovery-tool)**. 
The goal of the project was both to further develop a well-documented mapping, and to make Norwegian results more accessible. 
The contents of this repository are partially a result of this work. 
This project was led by the University of Bergen Library, partnered with the libraries at Western Norway University of Applied Sciences and the University of Stavanger. 

v2.0.0 of the strings (which covers ten SDGs) was developed under this project by these three insitutions, together with Natural Resources Institute Finland (LUKE) who contributed with search strings for two SDGs. 
Further development (strings for the remaining six SDGs and improvements to the python script) is being done in a larger collaboration between the institutions listed at the top of this file. 

