# Computing for Food Security -- Course Overview


The course is organized into 4 main sections:
1. Food production and consumption, world-wide
1. Predicting agricultural productivity: Micro and Macro
1. Agriculture and Climate Change
1. Optimizations for Productivity and Sustainability

The course will be presented during the 10-week Spring quarter of 2023.
There will be one 2-hour lecture each week, on Wednesday.
Each of the main sections will be covered in 2 to 3 weeks.

## 1. Food production and consumption, world-wide

### Course Overview:

- Socio-economic perspectives; Food (In)security
  - e.g., UN Sustainable Goals; mission of FAO
  - e.g., draw from [FAO The State of Food Security and Nutrition in the World 2022](https://www.fao.org/publications/sofi/2022/en/)
  - Food systems overview (e.g., [visible and invixible flows of ag prod](https://www.iisd.org/sites/default/files/2021-01/mueller-2015-food-system-type-figure.jpg)
- FAO (and related) data sets; data and tools, including production, trade,
  - Illustrative example: Impact of war in Ukraine on food supply
- Crop yield prediction; tools
- Interplay of agriculture and climate change
- Trade-offs between productivity and environmental impact

### Intro to FOA and related data on production, trade, nutrition, nutritional needs

- [FAO Ag production statistics (1961-2020)](https://www.fao.org/food-agriculture-statistics/data-release/data-release-detail/en/c/1491961/)
- [FAO Trade of ag commodities (1986-2020)](https://www.fao.org/food-agriculture-statistics/data-release/data-release-detail/en/c/1507740/)
- [FAO Central Product Classification (CPC) v2.1](https://unstats.un.org/unsd/classifications/unsdclassifications/cpcv21.pdf) and also see
  [dataset available here](https://unstats.un.org/unsd/classifications/Econ/cpc)
- Some data set about nutrition in foods -- ??
  - Draw from pp. 19 and following from "Global Food Security" by Zhang-Yue Zhou (2020)
  - Shift in perspectives about nutrition, from calories alone to nutritious diet overall
    (cf [2020 SOFI report](https://www.fao.org/documents/card/en/c/cc0639en)
- Some data set about country-level populations and nutritional needs -- ??
- Something about food loss and waste, e.g., McKinsey insights paper
  "Reducing food loss: What grocery retailers and manufacturers can do", Sept. 7, 2022,
  available [here](https://www.mckinsey.com/industries/consumer-packaged-goods/our-insights/reducing-food-loss-what-grocery-retailers-and-manufacturers-can-do)

### Key themes

- Talk about challenges of gathering global-level data, and standardizing across data sets
  - e.g., challenge of harmonizing production and trade data sets
  - e.g., [FAO Zambia training deck](https://www.fao.org/fileadmin/templates/ess/CountrySTAT/Zambia_training_2012/Classification_Correspondence_Table.pdf)
- Talk about role of Computer Scientists in the larger ecosystem of achieving social goals
  (We are an important but relatively small part of the overall ecosystem!)
  - <span style="color:red">Looking for good image/description of overall FOA
    strategy/process</span>
  
 
### Computing illustrations and exercise

- Bringing data into Postgres, including "normalization", using Python, Jupyter, DBeaver (students may use their favorite tools)
  - Talk about challenges of creating diverse datasets that can be used together
- Use of Protege ontology tool to help visualize categories
- Visualization using Tableau Public and/or DataWrapper
  - Importance of pre-processing data for use with these visualization tools

- Student exercise (over first 2 or 3 weeks) is to download and organize the data,
  ask an interesting question (e.g., given reduction of Ukraine's ag output due to
  the war, what is impact on food levels available to Ghana as compared with 2019
  levels?) and produce some informative visualizations the communicate the answer



## 2. Predicting agricultural productivity: Micro and Macro


### Crop Forecast at the Micro Level: Simulators

- APSIM as a representative simulation system,
  introduced using a few articles and videos, including
  
  - “Plant Modeling Framework: Software for building and running crop
     models on the APSIM platform” dby Brown HE, Huth NI, Holzworth
     DP, Teixeira EI, Zyskowski RF, Hargreaves JNG, Moot DJ,
     Environmental Modeling & Software 62, 385-398,
     available [here](https://www.sciencedirect.com/science/article/pii/S1364815214002588)

  - YouTube: "APSIM Next Gen Training Video"
    available [here](https://www.youtube.com/watch?v=5DogVqLYbUs)

  - other ...

- Validation of APSIM

  - Article “Simulation of growth and development of diverse legume
    species in APSIM” by M. J. Robertson, P. S. Carberry,
    N. I. Huth, J. E. Turpin, M. E. Probert, P. L. Poulton,
    M. Bell, G. C. Wright, S. J. Yeates, and R. B. Brinsmead
    Aust. J. Agric.Res., 2002, 53, pp 429-446,
    available [here](https://www.researchgate.net/profile/S-Yeates-2/publication/263003628_Simulation_of_growth_and_development_of_diverse_legume_species_in_APSIM/links/573bf7d408ae298602e45f01/Simulation-of-growth-and-development-of-diverse-legume-species-in-APSIM.pdf)


- Overview of other simulation models

  - e.g., "Comparing the performance of 11 crop simulation models in
    predicting yield response to nitrogen fertilization" Tapio J. Salo,
    Taru Palosuo, Kurt Christian Kersebaum, Claas Nendel, Carlos
    Angulo, Frank Ewert, Marco Bindi, Pierluigi Calanca, Tommy Klein,
    Marco Moriondo, et al.;
    available [here](https://hal.science/hal-01413572)


    
### Crop Forecast at the Macro Level


- Remote Sensing, including interpretation and interpolation
  - <span style="color:red">What articles?  What data sets?</span>

- 









### Computing illustrations and exercises





## 3. Agriculture and Climate Change


### Overview of Climate Change: Shared Socioeconomic Pathways (SSPs) &
    Relative Concentration Pathways (RCPs)

- e.g., selections from [Climate Change: The Physical Basis](https://www.ipcc.ch/report/ar6/wg1/)
- e.g., [Shared Socioeconomic Pathways Scenario Database web pages](https://iiasa.ac.at/models-tools-data/ssp)


### Basics of Impacts of Climate Change on Agriculture

- <span style="color:red">What articles?</span>
- <span style="color:red">Want data about weather for a given region, and ability
  to create .met file (and perhaps others) from it</span>


- Using APSIM to model impacts of climate change
  - e.g., Continuous Wheat with Climate Change, described
    [here](https://www.apsim.info/support/apsim-training-manuals/climate-change/);
    <span style="color:red">However, this is for APSIM Classic; how to convert
    into APSIM NextGen?</span>    

- <span style="color:red">Illustration of impact of climate change at a more macro level??
  </span>

### Basics of Agricultural impact on GHG's and Climate Change

- 

- Something about Soil Organic Carbon (?), e.g.,
  FAO document "Soil Organic Carbon: The Hidden Potential" (2017)
  available [here](https://www.fao.org/3/a-i6937e.pdf)


### Climate Smart Agriculture

- e.g., Deloitte insight paper
  "Transforming Food Systems with Farmers: A Pathway for the EU", April 2022;
  available [here](https://www2.deloitte.com/content/dam/Deloitte/us/Documents/consulting/us-transforming-food-systems-farmers.pdf)
- e.g., EU website "[Climate Smart Agriculture](https://ec.europa.eu/eip/agriculture/en/news/climate-smart-agriculture)"

- <span style="color:red">Something about instrumentation for smart ag??</span>


### Computing illustrations and exercises

- The idea is to use APSIM to illustrate how climate change would affect ag production
  at a fairly localized scale.  Need to translate various climate change weather predictions
  into met files?

- Possibly a similar exercise at a more macro level





##  4. Optimizations for Productivity and Sustainability

This topic will be centered around two papers:

- "Trading carbon for food: Global comparison of carbon stocks
  vs. crop yields on agricultural land Paul C. West pcwest@wisc.edu,
  Holly K. Gibbs, Chad Monfreda, +3 , and Jonathan A. Fole available
  [here](https://www.pnas.org/doi/10.1073/pnas.1011078107)

- “Relocating croplands could drastically reduce the environmental
  impacts of global food production” by Robert M. Beyer,Fangyuan Hua ,
  Philip A. Martin , Andrea Manica & Tim Rademacher, COMMUNICATIONS
  EARTH & ENVIRONMENT; (2022)3:49, available
  [here](https://doi.org/10.1038/s43247-022-00360-6)

There will probably not be a programming exercise with this topic area

