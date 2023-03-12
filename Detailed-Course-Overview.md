# Computing for Food Security -- Course Overview


The course is organized into 4 main sections:
1. Food production and consumption, world-wide
1. Forecasting agricultural productivity: Micro and Macro
1. Agriculture and Climate Change
1. Optimizations for Productivity and Sustainability

The course will be presented during the 10-week Spring quarter of 2023.
There will be one 2-hour lecture each week, on Wednesday.
Each of the main sections will be covered in 2 to 3 weeks.

In the outline below, a red cirle (&#x1F534;) indicates an area where
I am still looking for appropriate materials, data or software tools...


## 1. Food production and consumption, world-wide

### Course Overview:

- Socio-economic perspectives; Food (In)security
  - e.g., UN Sustainable Goals; mission of FAO
  - e.g., draw from [FAO The State of Food Security and Nutrition in the World 2022](https://www.fao.org/publications/sofi/2022/en/)
  - Food systems overview (e.g., [visible and invisible flows of ag prod](https://www.iisd.org/sites/default/files/2021-01/mueller-2015-food-system-type-figure.jpg))
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
- Nutrition in foods; going from food production/import to nutrition availability
  - Draw from pp. 19 and following from the book
    "Global Food Security" by Zhang-Yue Zhou (2020)
  - Shift in perspectives about nutrition, from calories alone to nutritious diet overall
    (cf [2022 FAO report on The State of Food Security and Nutrition in the World](https://www.fao.org/documents/card/en/c/cc0639en))
  - &#x1F534; Some data set about nutrition in foods -- ??
- &#x1F534; Some data set about country-level populations and nutritional needs -- ??
- Something about food loss and waste, e.g., at least in western countries it is about 15%
  from field to warehouse or processing, and another 15% from retail to consumer
  - e.g., McKinsey insights paper
    "Reducing food loss: What grocery retailers and manufacturers can do", Sept. 7, 2022,
    available [here](https://www.mckinsey.com/industries/consumer-packaged-goods/our-insights/reducing-food-loss-what-grocery-retailers-and-manufacturers-can-do)

### Key themes

- Talk about challenges of gathering global-level data, and standardizing across data sets
  - e.g., challenge of harmonizing production and trade data sets
  - e.g., [FAO Zambia training deck](https://www.fao.org/fileadmin/templates/ess/CountrySTAT/Zambia_training_2012/Classification_Correspondence_Table.pdf)
- Talk about role of Computer Scientists in the larger ecosystem of achieving social goals
  (We are an important but relatively small part of the overall ecosystem!)
  - &#x1F534; Looking for good image/description of overall FOA
    strategy/process, that shows role of data collection, data analysis
  
 
### Computing illustrations and exercise

- Bringing FAO production and trade data into a database management
  system, including "normalization", using Postgres, Python, Jupyter, DBeaver
  (students may use their favorite tools)
  - Talk about challenges of creating diverse datasets that can be used together
- &#x1F534; Bring in data about nutrition and country populations -- what data sets?
- Use of Protege ontology tool to help visualize categorizations
- Visualization using Tableau Public and/or DataWrapper
  - Importance of pre-processing data for use with these visualization tools
- Student exercise (over first 2 or 3 weeks) is to download and organize the data,
  ask an interesting question (e.g., given reduction of Ukraine's ag output due to
  the war, what is impact on food and nutrition levels available to, e.g., Chad or
  Central African Republic as compared with 2019
  levels?) and produce some informative visualizations the communicate the answer.
  Might also include fertiliser production and trade, if I can find appropriate data sets



## 2. Forecasting agricultural productivity: Micro and Macro


### Crop Forecast at the Micro Level: Simulators

- APSIM as a representative simulation system.  Goal is that students will become
  beginning users of the system, and be able to create some simple crop simulations,
  e.g., for a given (part of a) country.
- Introduction to APSIM will include
  - “Plant Modeling Framework: Software for building and running crop
     models on the APSIM platform” by H.E. Brown et. al.,
     Environmental Modeling & Software 62, 385-398,
     available [here](https://www.sciencedirect.com/science/article/pii/S1364815214002588)
  - other ...
- Key data sets for creating APSIM simulations: weather, soil. 
- Validation of APSIM
  - e.g., Article “Simulation of growth and development of diverse legume
    species in APSIM” by M. J. Robertson et. al.,
    Aust. J. Agric.Res., 2002, 53, pp 429-446,
    available [here](https://www.researchgate.net/profile/S-Yeates-2/publication/263003628_Simulation_of_growth_and_development_of_diverse_legume_species_in_APSIM/links/573bf7d408ae298602e45f01/Simulation-of-growth-and-development-of-diverse-legume-species-in-APSIM.pdf)
  - e.g., Article "Evaluation of the APSIM model in cropping systems of Asia”,
    D.S. Gaydon et. al. (2017); available [here](https://www.sciencedirect.com/science/article/pii/S0378429016308759)
  - Actually, for each [APSIM Next Gen model in release](https://apsimnextgeneration.netlify.app/modeldocumentation/) 
    you can download a pdf "Description &amp; Validation" pdf that includes many things 
    including validation info (e.g., here's the pdf for [Wheat](https://builds.apsim.info/api/nextgen/docs/Wheat.pdf)). These pdf's are kept up-to-date.
- Overview of other simulation models
  - e.g., "Comparing the performance of 11 crop simulation models in
    predicting yield response to nitrogen fertilization" Tapio J. Salo,
    Taru Palosuo, Kurt Christian Kersebaum, Claas Nendel, Carlos
    Angulo, Frank Ewert, Marco Bindi, Pierluigi Calanca, Tommy Klein,
    Marco Moriondo, et al.;
    available [here](https://hal.science/hal-01413572)


    
### Crop Forecast at the Macro Level


- Remote Sensing, including interpretation and interpolation
  - &#x1F534; What articles?  What data sets?
- ML for macro-level forecasting
  - Possible article: “Coupling Machine Learning and Crop Modeling
    Improves Crop Yield Prediction in the US Corn Belt.” Shahhosseini,
    M., H. Guiping, I. Huber, and S. V. Archontoulis. 2021, Scientific
    Reports 11:1606; available
    [here](https://www.nature.com/articles/s41598-020-80820-1)
  - &#x1F534; What articles?  What data?  What tools?  How to incorporate
    impact of farming practices, e.g., amount of fertilizer, irrigation


### Key Themes

- Crop yield forecast, be it by simulation or ML, involves a lifecycle of 
  steps, including model building (by hand or through ML), extensive data collection,
  validation, tuning/calibration
- Overcoming challenges of incomplete data, e.g., cloud cover in remote sensing.
  &#x1F534; What are some good illustrations of this?
- There is always uncertainty (e.g., new pests that aren't in the models or
  the historical data), but there is still tremendous value in reasonably-well
  validated forecasts


### Computing illustrations and exercises

- APSIM
  - There are many YouTube videos for APSIM NextGen, including
    - "APSIM Next Gen Training Video"
      available [here](https://www.youtube.com/watch?v=5DogVqLYbUs) 
    - "How to create and run an APSIM Next Generation simulation" (which
      uses barley); available [here](https://www.youtube.com/watch?v=OUP6dQC1lEU)
  - I will illustrate APSIM by building a simulation, e.g., for a given crop
    and given location
    - &#x1F534; How to get appropriate weather data (.met file)?
      Use [GAEZ](https://gaez.fao.org/) for climate and [BestiaPop](https://bestiapop.readthedocs.io/en/latest/) to translate into .met?
    - &#x1F534; How to get appropriate soil data? Probably use [GAEZ](https://gaez.fao.org/)?
-  &#x1F534; ML and remote sensing for some macro-level example (what to use?)
   - Plan to illustrate for different places



## 3. Agriculture and Climate Change


### Overview of Climate Change: Shared Socioeconomic Pathways (SSPs) &amp; Relative Concentration Pathways (RCPs)

- Selections from IPCC Sixth Assessment Report
  [Climate Change 2021: The Physical Basis](https://www.ipcc.ch/report/ar6/wg1/)
  - e.g., "Climatic impact-drivers (CIDs)"
  - Interesting tool: [IPCC WGI Interactive Atlas](https://interactive-atlas.ipcc.ch/)
- IIASA [Shared Socioeconomic Pathways Scenario Database web pages](https://iiasa.ac.at/models-tools-data/ssp)
  - possibly, talk about Radiative Forcing (e.g., see [MIT Explainers page on radiative forcing](https://climate.mit.edu/explainers/radiative-forcing))
- &#x1F534; What are some good data sets about predicted climate change out
  to 2100, for the 5 standard SSPs? (Can I dig them out of the [IIASA SSPs website](https://iiasa.ac.at/models-tools-data/ssp)?)
- &#x1F534; Possibly, if I can find some appropriate source materials,
  something about the computing technologies for creating the
  different pathway models.  (However this might be too deep and too
  out-of-scope)
  - A possibility here is the article "ClimateBench v1.0: A Benchmark
    for Data-Driven Climate Projections", D. Watson-Parris et. al.,
    Journal of Advances in Modeling Earth Systems (JAMES), Spt, 2022;
    available
    [here](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021MS002954)
    - cf. the [ClimateBench github page](https://github.com/duncanwp/ClimateBench),
      which might have useful software (&#x1F534; Is it relatively easy to learn
      how to use for some basic illsutrations?)


### Basics of Impacts of Climate Change on Agriculture


- &#x1F534; What are some good articles or websites about this?
  - Perhaps, material from [IPCC Sixth Assessment -- Technical Report](https://www.ipcc.ch/report/ar6/wg1/downloads/report/IPCC_AR6_WGI_TS.pdf)?
- &#x1F534; Want data about weather for a given region, and ability
  to create .met file (and perhaps others) from it
- Will illustrate by using APSIM to model impacts of climate change (see below),
  and hopefully at a macro level also

### Basics of Agricultural impact on GHG's and Climate Change


- GHG output from ag industry
  - e.g. [UN Land Use, Land Use Change and Forestry (LULUCF)
    website](https://unfccc.int/topics/land-use/workstreams/land-use--land-use-change-and-forestry-lulucf)
    talks about how AFOLU accounted for about 23% of anthropoorphic
    GHG emeissions 2007-2016
  - &#x1F534; Other sources/articles?
- Carbon sequestration
  - e.g., again [UN Land Use, Land Use Change and Forestry (LULUCF) website](https://unfccc.int/topics/land-use/workstreams/land-use--land-use-change-and-forestry-lulucf)
  - Something about Soil Organic Carbon (?), e.g.,
    FAO document "Soil Organic Carbon: The Hidden Potential" (2017)
    available [here](https://www.fao.org/3/a-i6937e.pdf)
  - &#x1F534; Other??
- Something about other environmental impacts (e.g., fertilizer runoff and eutrophication,
  biodiversity, ...). (&#x1F534; What are some good sources?)


### Climate Smart Agriculture

- e.g., Deloitte insight paper
  "Transforming Food Systems with Farmers: A Pathway for the EU", April 2022;
  available [here](https://www2.deloitte.com/content/dam/Deloitte/us/Documents/consulting/us-transforming-food-systems-farmers.pdf)
- e.g., EU website "[Climate Smart Agriculture](https://ec.europa.eu/eip/agriculture/en/news/climate-smart-agriculture)"
- &#x1F534; Something about instrumentation for smart ag, e.g., styles of
  smart ag (e.g., drip irrigation, precision fertilization), tools for measurement,
  associated computing technologies ??

### Key Themes

- Importance of our understanding of both agricultural productivity and possible
  climate change pathways as the basis for pro-actively working towards
  mitigation of the climate change impacts
- The challenges of moving an industry, in this case agriculture, in a direction
  that will mitigate climate change impacts, in terms of public policy (government
  incentives, etc.), stakeholder education, large and small landholder investments, ...

### Computing illustrations and exercises

- Use APSIM to illustrate how climate change would affect ag production
  at a fairly localized scale.  Need to translate various climate change weather predictions
  into .met files?
  - cf APSIM example on "Continuous Wheat with Climate Change";
    available
    [here](https://www.apsim.info/support/apsim-training-manuals/climate-change/);
    (&#x1F534; However, this is for APSIM Classic; how to convert
    into APSIM NextGen?)
- &#x1F534; Illustration of impact of climate change at a more macro level??








##  4. Optimizations for Productivity and Sustainability

### Simultaneously optimizing productivity and carbon sequestion

- "Trading carbon for food: Global comparison of carbon stocks
  vs. crop yields on agricultural land, Paul C. West et. al.;
  available
  [here](https://www.pnas.org/doi/10.1073/pnas.1011078107)
- “Relocating croplands could drastically reduce the environmental
  impacts of global food production” by Robert M. Beyer,Fangyuan Hua ,
  Philip A. Martin , Andrea Manica &amp; Tim Rademacher, COMMUNICATIONS
  EARTH & ENVIRONMENT; (2022)3:49, available
  [here](https://doi.org/10.1038/s43247-022-00360-6)

### Trade-offs involving Nitrogen fertilization

- “Exploring Trade-Offs Between Profit, Yield, and the Environmental
  Footprint of Potential Nitrogen Fertilizer Regulations in the US
  Midwest” by G. Mandrini et. al., Front. Plant Sci., 15 April 2022
  Sec. Crop and Product Physiology Volume 13 - 2022; Available
  [here](https://www.frontiersin.org/articles/10.3389/fpls.2022.852116/full)
- “How Does Crop Rotation Influence Soil Moisture, Mineral Nitrogen,
   and Nitrogen Use Efficiency?” by R. Yang et. al.  Front. Plant
   Sci., 17 March 2022 Sec. Crop and Product Physiology Volume 13 -
   2022; available
   [here](https://www.frontiersin.org/articles/10.3389/fpls.2022.854731/full)



### Key Themes

- The optimization study on productivity and carbon sequestration
  is "academic" in the sense that it
  focuses on some issues and ignores many others, e.g., the cost of
  re-locating agriculture, and all of the associate infrastructure, from one area to another
  Nevertheless, these kinds of "academic" studies can help people.  
  to understand the art of the possible, and will foster more comprehensive
  analysis of possible paths forward.
- Studies that will help guide public policy bring together a broad array of specialties


### There will probably not be a programming exercise with this topic area



