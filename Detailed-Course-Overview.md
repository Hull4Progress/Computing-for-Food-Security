
# Computing for Food Security -- Course Overview


The course is organized into 6 sections:
1. Course introduction and overview (about 1.5 hours)
1. Global initiatives and data in support of Food Security
1. Forecasting agricultural productivity: Micro
1. Agriculture and Climate Change
1. Forecasting agricultural productivity: Macro
1. Climate Smart Agriculture

The course as described here is intended for senior and/or graduate-level CS students.
It assumes a 15-week semester, with 2.5 hours
of lecture time per week, or a 10-week quarter with 3 to 4 hours of lecture
time per week.
The lecture time will be split between
traditional lectures (including some class discussion);
coding labs that review example code snippets; and student presentations
about team software projects.
Some content
will be dropped if the course is presented in a 10-week quarter.




## 1. Course introduction and overview (about 1 or 1.5 hours)

- Socio-economic perspectives; Food (In)security
  - e.g., [UN Sustainable Goals](https://www.un.org/sustainabledevelopment/blog/2015/12/sustainable-development-goals-kick-off-with-start-of-new-year/); mission of [FAO](https://www.fao.org/home/en/)
  - e.g., draw from [FAO The State of Food Security and Nutrition in the World 2022](https://www.fao.org/publications/sofi/2022/en/)
  - Food systems overview (e.g., [visible and invisible flows of ag prod](https://www.iisd.org/sites/default/files/2021-01/mueller-2015-food-system-type-figure.jpg))
- FAO (and related) [data sets](https://www.fao.org/faostat/en/); data and tools, including production, trade,
  - Illustrative example: [Impact of war in Ukraine on food supply](https://www.statista.com/chart/27892/share-of-food-imports-by-country-affected-by-by-food-export-bans/)
- Crop yield prediction, tools, e.g.
  - [APSIM](https://www.apsim.info/),
     [WOFOST](https://www.wur.nl/en/research-results/research-institutes/environmental-research/facilities-tools/software-models-and-databases/wofost.htm)
  - Machine Learning approaches, e.g.,
    [Forecasting Corn Yield with ML Ensembles](https://www.frontiersin.org/articles/10.3389/fpls.2020.01120/full),
    [Combining ML and crop modeling](https://www.nature.com/articles/s41598-020-80820-1), and
    [ML for West African Countries](https://reader.elsevier.com/reader/sd/pii/S2772375522000168),
  - Global gridded [soil](https://www.isric.org/explore/soilgrids) and
    [agro-ecological](https://gaez.fao.org/) data
- Intro to Climate Change Science, e.g.,
    [IPCC 6th Assessment Report](https://www.ipcc.ch/report/ar6/wg3/downloads/report/IPCC_AR6_WGIII_SummaryForPolicymakers.pdf),
    [IPCC Climate Change 2021: The Physical Science Basis](https://www.ipcc.ch/report/ar6/wg1/downloads/report/IPCC_AR6_WGI_SPM_Stand_Alone.pdf)
- Interplay of agriculture and climate change, e.g.,
  [impacts of agriculture on climate](https://www.ipcc.ch/report/ar6/wg3/figures/summary-for-policymakers/figure-spm-7/),
  [impacts of climate change on agriculture](https://agmip.org/agmip-crop-modeling-study-included-in-ipcc-ar6-syr/?et_fb=1)
- Trade-offs between productivity and environmental impact, e.g.,
    [Carbon Release vs. Ag Productivity](https://www.pnas.org/doi/10.1073/pnas.1011078107),
    [Optimizing for Carbon Sequestration](https://doi.org/10.1038/s43247-022-0)
- Climate Smart Agriculture (CSA), e.g.,
    [World Economic Forum](https://www.weforum.org/agenda/2020/11/why-we-must-scale-up-climate-smart-agriculture-csa-climate-hunger-population-resilience/),
  [FAO homepage on CSA](https://www.fao.org/climate-smart-agriculture/en/),
  [FAO Climate Smart Agriculture Sourcebook](https://www.fao.org/climate-smart-agriculture-sourcebook/en)



## 2. Global initiatives and data in support of Food Security

- [UN Sustainability Goals](https://sdgs.un.org/goals)
- Intro to FAO, e.g.,
  [FAO goals vis-a-vis UN Sustainability Goals](https://www.fao.org/sustainable-development-goals/indicators/en/)
- Important data sets
  - [FAO data on production, trade, nutrition, food balances, food costs, ...](https://www.fao.org/faostat/en/#data)
  - Auxiliary data sets, e.g.,
    [UN Standard country and area codes (M49)](https://unstats.un.org/unsd/methodology/m49/overview/), 
    [FAO Central Product Classification (CPC) v2.1](https://unstats.un.org/unsd/classifications/unsdclassifications/cpcv21.pdf)
  - See also:
       [FAO methods and standards](https://www.fao.org/statistics/methods-and-standards/en/),
       [FAO data collection](https://www.fao.org/statistics/data-collection/en/)
  - Drill down: [FAO methodology for computing Food Balances](https://fenixservices.fao.org/faostat/static/documents/FBS/New%20FBS%20methodology.pdf); [Tufts page on Food Balance Sheets](https://inddex.nutrition.tufts.edu/data4diets/data-source/food-balance-sheets-fbs)
- Food Insecurity metrics and data, e.g.,
  - "Global Food Security" by Zhang-Yue Zhou (2020) pp. 3-18
  -  [FAO Food Security Indicators](https://www.fao.org/faostat/en/#data/FS)
- Nutrition in foods; going from food production/import to nutrition availability
  - "Global Food Security" by Zhang-Yue Zhou (2020) pp. 19-27
  - Shift in perspectives about nutrition, from calories and macronutrients (calories, protein, fats)
    alone to nutritious diet overall, e.g.,
    [2022 FAO report on The State of Food Security and Nutrition in the World](https://www.fao.org/documents/card/en/c/cc0639en)),
    [UN Decade of Action on Nutrition (2016 to 2025)](https://cdn.who.int/media/docs/default-source/nutritionlibrary/decade-of-action-on-nutrition/work_programme_nutrition_decade.pdf) 
- Challenges of gathering global-level data, and standardizing across data sets
  - Methods for data collection, e.g.,
    [FAO Data Collection Questionnaires](https://www.fao.org/statistics/data-collection/en/);
    [FAO New Food Balances: Description of utilization variables](https://fenixservices.fao.org/faostat/static/documents/FBS/New%20FBS%20methodology.pdf)
  - Principles of creating statistical classifications:
    [CPC implementation and other activities on classifications in FAO](https://unstats.un.org/unsd/classifications/expertgroup/egm2015/ac289-16.PDF)
  - Approaches to harmonizing production and trade data sets, e.g., 
       [FAO Guidlines for Ag Statistics](https://www.fsinplatform.org/sites/default/files/resources/files/Guidelines-for-Int-Classifications-on-Agricultural-Statistics-web.pdf)
  - [FAO Zambia training deck](https://www.fao.org/fileadmin/templates/ess/CountrySTAT/Zambia_training_2012/Classification_Correspondence_Table.pdf)
  - [Statistical Data and Metadata eXchange (SDMX)](https://sdmx.org/) and the training book
  "[The SDMX Information Model](https://circabc.europa.eu/ui/group/8828dd71-a744-4914-b019-361aec02b6bb/library/25f5a77c-0974-4dab-a21d-15e5a541c0bf/details).)"
     See also the [Clickable SDMX Interface to the information model](https://statswiki.unece.org/display/ClickSDMX/Clickable+SDMX+Home)

- Additional Topics
  - US Global Change Research Program: [Impacts of Climate Change on Food Safety, Nutrition and
           Distribution (2016)](https://health2016.globalchange.gov/low/ClimateHealth2016_07_Food_small.pdf)
  - Impact of Ukraine war on food supply, e.g.,
    - FAO: [Note on the impact of the war on food security in
            Ukraine 20 July 2022](https://www.fao.org/3/cc1025en/cc1025en.pdf)
    - Washington Post July 22, 2023: [5 countries hit hard by the grain crisis in
         Ukraine](https://www.washingtonpost.com/world/2022/06/15/ukraine-war-russia-grain-food-crisis-world-hunger/)
    - Statista August 2, 2022: [Where Food Imports Are Affected in the Ukraine Crisis](https://www.statista.com/chart/27892/share-of-food-imports-by-country-affected-by-by-food-export-bans/)
  - Intro to fertilization and yield: Thunder Said Energy [Crop production: how much does nitrogen fertilizer increase yields](https://thundersaidenergy.com/downloads/crop-production-how-much-does-nitrogen-fertilizer-increase-yields/)
  - McKinsey on Food Loss and Waste: [Reducing Food Loss](https://www.mckinsey.com/industries/consumer-packaged-goods/our-insights/reducing-food-loss-what-grocery-retailers-and-manufacturers-can-do)
  - Role of Data and Computer Scientists in the larger ecosystem of achieving FAO (and related) goals, e.g.,
    - [FAO Strategic Framework](https://www.fao.org/about/strategy-programme-budget/strategic-framework/en/)
    - Tackling the Digital Divide in Agriculture: [CGIAR Digital Innovation Initiative](https://www.cgiar.org/initiative/digital-innovation/?section=about)
  
 
#### Computing illustrations

- Bringing FAO data (e.g., production, trade, food balances, food insecurity) into a persistent store
  including "normalization", using, e.g., Postgres, DBeaver, Python, Jupyter 
  - Challenges of integrating across diverse datasets
- Visualization using Tableau Public 
  - Importance of pre-processing data for use with these visualization tools
  - [Tableau Tips and Tricks](https://www.tableau.com/blog/7-tips-and-tricks-dashboard-experts)
- Possibly: Use of Protege ontology tool to help visualize categorizations

#### Student exercises
- Exploration of food security issues for a country or region
  by analyzing a join of two or three data sets
  from [FAO data sets](https://www.fao.org/faostat/en/#data)
  and/or related data sets (e.g., country-level populations, country-level economies, civil strife).
  - This exercise is broken into 2 parts:
    - Part one is to identify and start to analyze the data,
    - Part two is to further analyze the data based on feedback, and to create visualizations
      using Tableau Public or similar.
  - Note: students may use their favorite tools; for example, they can use Postgres for most of their
    persistent data storage and data manipulation, or they can use csv files for
    persistent data storage and
    rely on the Python pandas package for data manipulation



## 3. Forecasting agricultural productivity: Micro

- Introduction to Crop Forecast Models
  - The importance of modeling in Computer Science, e.g., UML, Entity-Relationship data modeling
  - Chapter 9, "Fundamental concepts of crop models illustrated by a comparative
     approach" by N. Brisson, J. Wery and K. Boote, in the book "[Working
     with Dynamic Crop Models: Evaluation, Analysis, Parameterization,
     and Applications](http://ndl.ethernet.edu.et/bitstream/123456789/43022/1/53.pdf)” 
     edited by D. Wallach, D. Makowski and J.W.Jones (Elsevier, 2006)
  -  Building a crop forecast model from scratch: based on Section 1.2 
     "A Crop Model is a Dynamic System"
     from the "Working with Dynamic Crop Models ..." 
     book just mentioned, with some extensions

- Introduction to APSIM, a representative simulation system.  Goal is that students will become
    beginning users of the system, and be able to create some simple crop simulation,
    e.g., for a given region and a given climate situation (e.g., historical or future)
  -  “[Plant Modeling Framework: Software for building and running crop models on the APSIM platform](https://www.sciencedirect.com/science/article/pii/S1364815214002588)” 
     by H.E. Brown et. al., Environmental Modeling & Software 62, 385-398,
  - [APSIM Next Generation home page](https://apsimnextgeneration.netlify.app/)

- Principles and Data about weather properties and impacts, e.g.,
  - Solar irradiance, including 
        [Photosynthetically Active Radiation](https://www.spar.msstate.edu/class/EPP-2008/Chapter%201/Solar%20Radiation.pdf)
  - [NASA POWER](https://power.larc.nasa.gov/) (global) and [SILO](https://www.longpaddock.qld.gov.au/silo/about/) (Australia only)
    gridded global data sets
  - Tangent: New paints can help shed heat from the planet
    - [Washington Post (2023): We are building our roofs wrong ...](https://www.washingtonpost.com/climate-environment/2023/06/20/cool-roof-coatings-global-warming/)
    - [Lawrence Berkeley Lab: Cool Roofs](https://heatisland.lbl.gov/coolscience/cool-roofs)
    - [Geopolymer-based sub-ambient daytime radiative cooling coating (2022)](https://onlinelibrary.wiley.com/doi/full/10.1002/eom2.12284); 
        see also
        [Advance Science News (2022): New material is a game changer in radiative cooling](https://www.advancedsciencenews.com/new-material-is-a-game-changer-in-radiative-cooling/)

- Principles and Data about soil properties and impacts, e.g., 
  - [FAO on Soil and Water](https://www.fao.org/3/R4082E/r4082e03.htm),
      including mineral content, soil organic carbon, cation exchange capacity, ...
  - Soil as a Natural Resource: 
    [FAO Status of the World’s Soil Resources (SWSR) (2015)](https://www.fao.org/documents/card/en/c/c6814873-efc3-41db-b7d3-2081a10ede50/)
  - [A protocol to build soil descriptions for APSIM simulations (2021)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8720820/)
  - FAO GAEZ soil classification framework:
      [FAO "Global Agro Ecological Zones v4 MODEL DOCUMENTATION" (2021)](https://www.fao.org/geospatial/resources/detail/en/c/1410694/); (see also [GAEZ Data Viewer](https://gaez.fao.org/pages/data-viewer)
  - [ISRIC SoilGrids](https://www.isric.org/explore/soilgrids/); see also
      [SoilGrids data portal](https://soilgrids.org/)
      and [ISRIC Data Hub](https://data.isric.org/geonetwork/srv/eng/catalog.search#/home)

  
- Overview of other simulation models, e.g.,
  - "[Comparing the performance of 11 crop simulation models in
    predicting yield response to nitrogen fertilization](https://hal.science/hal-01413572)" Tapio J. Salo,
    Taru Palosuo, Kurt Christian Kersebaum, Claas Nendel, Carlos
    Angulo, Frank Ewert, Marco Bindi, Pierluigi Calanca, Tommy Klein,
    Marco Moriondo, et al.
  - [WOFOST](https://www.wur.nl/en/research-results/research-institutes/environmental-research/facilities-tools/software-models-and-databases/wofost.htm)


- Validation of Crop Models
  - Chapters 12 & 13 of 
    "Fundamental concepts of crop models illustrated by a comparative
    approach" by N. Brisson, J. Wery and K. Boote, in the book "Working
    with Dynamic Crop Models ..." mentioned above
  - Article “[Simulation of growth and development of diverse legume
    species in APSIM](https://www.researchgate.net/profile/S-Yeates-2/publication/263003628_Simulation_of_growth_and_development_of_diverse_legume_species_in_APSIM/links/573bf7d408ae298602e45f01/Simulation-of-growth-and-development-of-diverse-legume-species-in-APSIM.pdf)” 
    by M. J. Robertson et. al., Aust. J. Agric.Res., 2002, 53, pp 429-446,
  - Article "[Evaluation of the APSIM model in cropping systems of Asia](https://www.sciencedirect.com/science/article/pii/S0378429016308759)”,
    D.S. Gaydon et. al. (2017)
  - Also, for each [APSIM Next Gen model in release](https://apsimnextgeneration.netlify.app/modeldocumentation/) 
    you can download "Description &amp; Validation" pdf that includes many things 
    including validation info (e.g., here's the pdf for [Wheat](https://builds.apsim.info/api/nextgen/docs/Wheat.pdf)). These pdf's are kept up-to-date.


#### Computing illustrations

- Selected steps in the creation of a crop yield forecast system from scratch, following examples/discussion from
    Section 1.2 and Chapter 9 of
   the book 
     "[Working
     with Dynamic Crop Models: Evaluation, Analysis, Parameterization,
     and Applications](http://ndl.ethernet.edu.et/bitstream/123456789/43022/1/53.pdf)”

- APSIM
  - There are many YouTube videos for APSIM NextGen, including
    - "APSIM Next Gen Training Video"
      available [here](https://www.youtube.com/watch?v=5DogVqLYbUs) 
    - "[How to create and run an APSIM Next Generation simulation](https://www.youtube.com/watch?v=OUP6dQC1lEU)"
       (which uses barley)
  - The lectures include an illustration of building a simulation in APSIM, for a given crop
    and given location

- Key data sets and tools for creating APSIM simulations:
  - Soil: [ISRIC SoilGrids](https://www.isric.org/explore/soilgrids/)
    - [SoilGrids data portal](https://soilgrids.org/);
      see also [here](https://data.isric.org/geonetwork/srv/eng/catalog.search#/home)
    - [R-based tool to fetch soil profiles for APSIM](https://search.r-project.org/CRAN/refmans/apsimx/html/get_isric_soil_profile.html)
  - Weather/Climate: 
    - [NASA POWER](https://power.larc.nasa.gov/)
    - Processing tool to format weather data for APSIM: [BestiaPop](https://github.com/JJguri/bestiapop) 

#### Student Exercises

- Creation of simplified crop simulation modeling tool, expanding on illustrations and example code 
   presented in the lectures

- Modeling with APSIM (Part 1): Forecasting crop yields in a selected region.  
    In this exercise students will pick
    some small region (e.g., 100km x 100km) and some crops grown in the region, and
    create APSIM simulations of predicted crop yield for different places in the region
    using soil data and recent historical weather data.


## 4. Agriculture and Climate Change


#### Introduction to Climate Change Science

- Selections from [IPCC Sixth Assessment Report (2021)](https://www.ipcc.ch/report/ar6/wg1/)
  - [Summary for Policy Makers](https://www.ipcc.ch/report/ar6/wg3/downloads/report/IPCC_AR6_WGIII_SummaryForPolicymakers.pdf)
  [Technical Summary](https://www.ipcc.ch/report/ar6/wg1/downloads/report/IPCC_AR6_WGI_TS.pdf),
  e.g., History of GHG emissions; Different kinds of GHG's; Historical impacts on climate;  "Climatic impact-drivers (CIDs)"
  - Interesting tool: [IPCC WGI Interactive Atlas](https://interactive-atlas.ipcc.ch/)
- IIASA [Shared Socioeconomic Pathways Scenario Database web pages](https://iiasa.ac.at/models-tools-data/ssp)
  - Shared Socioeconomic Pathways (SSPs) &amp; Relative Concentration Pathways (RCPs)
  - Radiative Forcing (e.g., see [MIT Explainers page on radiative forcing](https://climate.mit.edu/explainers/radiative-forcing))
- [United Nations Framework Convention on Climate Change (UFCCC) website](https://unfccc.int/)
- Carbon cycles and carbon sequestration: 
   [NASA site on The Carbon Cycle](https://earthobservatory.nasa.gov/features/CarbonCycle)
  - See also
   [US EPA on Climate Change Indicators](https://www.epa.gov/climate-indicators/climate-change-indicators-atmospheric-concentrations-greenhouse-gases);
   [Carleton College on Carbon in the Atmosphere](https://serc.carleton.edu/eslabs/carbon/3b.html)
  - Digression: [Wikipedia on Major Ice Ages](https://en.wikipedia.org/wiki/Timeline_of_glaciation)
  - ["ClimateBench v1.0: A Benchmark
    for Data-Driven Climate Projections", D. Watson-Parris et. al.,
    Journal of Advances in Modeling Earth Systems (JAMES), Sept, 2022](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021MS002954); see also the [ClimateBench github page](https://github.com/duncanwp/ClimateBench)
  - Digression: [Annual cycle of atmospheric CO2 variation](https://earthobservatory.nasa.gov/features/CarbonCycle 


#### Agriculture, Climate Change and the Environment


- Agriculture, Forestry and Other Land Uses (AFOLU): Chapter 7 (pp. 747-860) from 
     [IPCC Sixth Assessment -- Full Report (2022)](https://www.ipcc.ch/report/ar6/wg3/downloads/report/IPCC_AR6_WGIII_FullReport.pdf);
     see also [Summary for Policy Makers and Technical Summary]((https://www.ipcc.ch/report/ar6/wg3/))
- Agriculture and GHG's
  - FAO [Greenhouse gas emissions from agrifood systems (2000 - 2020)](https://www.fao.org/3/cc2672en/cc2672en.pdf)
  - [Ancient Farmers Spared Us From 
     Glaciers ...](https://www.sciencedaily.com/releases/2018/09/180906141507.htm); 
    see also 
    [Glacial Inception in Marine Isotope Stage 19 ...](https://www.nature.com/articles/s41598-018-28419-5) 
  - See also [UN Land Use, Land Use Change and Forestry (LULUCF)
    website](https://unfccc.int/topics/land-use/workstreams/land-use--land-use-change-and-forestry-lulucf)
- Carbon sequestration in agriculture
  - [UN Land Use, Land Use Change and Forestry (LULUCF) website](https://unfccc.int/topics/land-use/workstreams/land-use--land-use-change-and-forestry-lulucf)
  - FAO [Soil Organic Carbon: The Hidden Potential (2017)](https://www.fao.org/3/a-i6937e.pdf)
  - USDA [Grassland Carbon Management](https://www.fs.usda.gov/ccrc/topics/grassland-carbon-management)
- Fertilizer runnoff and eutrophication
  - EPA: [Nutrient Polution: The Sources and Solutions: 
            Agriculture](https://www.epa.gov/nutrientpollution/sources-and-solutions-agriculture)
  - [Eutrophication: An Ecological Vision (2005)](https://link.springer.com/article/10.1663/0006-8101(2005)071[0449:EAEV]2.0.CO;2#citeas)
  - [Recent advances in control technologies for non-point source pollution with nitrogen
     and phosphorous from agricultural runoff: current practices and future prospects
     (2020)](https://applbiolchem.springeropen.com/articles/10.1186/s13765-020-0493-6)

- Impacts of Climate Change on Agriculture
  - EPA: [Climate Change Impacts on Agriculture and Food Supply](https://www.epa.gov/climateimpacts/climate-change-impacts-agriculture-and-food-supply)
  - US Global Change Research Program: [Impacts of Climate Change on Food Safety, Nutrition and
           Distribution (2016)](https://health2016.globalchange.gov/low/ClimateHealth2016_07_Food_small.pdf)

#### Computing illustrations

- Working with [FAO GAEZ data](https://gaez.fao.org/)
  - [GAEZ data viewer](https://gaez.fao.org/pages/data-viewer): Tabs available on
    Land and Water Resources; Agro-climatic Resources (including future projections for 4 RCP's);
    Agro-climatic Potential Yield; Suitability and Attainable Yield; Actual Yields & Production;
    Yield & Production Gaps
  - Working with raster data
    - [Rasterio](https://rasterio.readthedocs.io/en/stable/): Accessing data in raster files
    - [GDAL](https://gdal.org/): Translator library for raster and vector geospatial data formats
- Creating maps with a Geographic Information System (GIS)
  - [QGIS](https://www.qgis.org/en/site/):
        An open-source Geographic Information System
  - [Natural Earth](https://www.naturalearthdata.com/): Open source map data,
        including, e.g., 
        [maps for countries, states/provinces, developed areas](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/)
  - See also [Ryan Abernathey's Tutorial on Python Cartopy package](https://rabernat.github.io/research_computing_2018/maps-with-cartopy.html)

- Use of APSIM to illustrate how climate change would affect ag production
  at a fairly localized scale. 
  Using existing soil data, and translating various climate change weather forecasts
  into .met files

#### Student Exercise

-  Modeling with APSIM (part 2): Incorporating climate change.
    In this exercise students extend their previous modeling with APSIM
    to incorporate the impact of projected climate change.
    In particular, students will use the Agro-climatic Resources tab
    within the [GAEZ Data Portal](https://gaez.fao.org/pages/data-viewer)
    about future weather projections to create simulated .met files for
    use in their APSIM models.  The idea is to develop examples of
    how climate change might impact yields of specific crops in specific regions,
    and compare with forecasts based on recent historical weather.


## 5. Forecasting agricultural productivity: Macro

#### Intro to applied machine learning (this material will be interleaved with material from the next subsection)

- Cross Industry Standard Process for Data Mining (CRISP-DM), e.g., 
    [from healthcare](https://www.researchgate.net/publication/228651042_Specialised_Tools_for_Automating_Data_Mining_for_Hospital_Management)
- Representative ML pipelines
  - [Generic](https://ml-ops.org/content/end-to-end-ml-workflow)
  - [For crop forecast](https://reader.elsevier.com/reader/sd/pii/S2772375522000168)
- Selections from [The Elements of Statistical Learning: Data Mining, Inference, and Prediction, by Hastie, Tibshirani, Friedman, 2nd Edition, 12th printing (2017)](https://hastie.su.domains/ElemStatLearn/printings/ESLII_print12_toc.pdf)
  - Overview of Supervised Learning (see chapters 1 and 2)
  - Linear methods for regression (see chapter 3); see also 
     [analyticsvidhya on gradient descent](https://www.analyticsvidhya.com/blog/2020/10/how-does-the-gradient-descent-algorithm-work-in-machine-learning/)
  - Random Forest (see chapter 15)
  - Boosting (see chapter 10), e.g., [XGBoost](https://xgboost.readthedocs.io/en/stable/tutorials/model.html),
      LightGBM
  - Neural Networks (see chapter 11); see also
    - [ML for Beginners: An Introduction to Neural Networks (2019)](https://victorzhou.com/blog/intro-to-neural-networks/)
    - See also these neural network playgrounds:
        [tensorflow](https://playground.tensorflow.org/),
        [karpathy](https://cs.stanford.edu/people/karpathy/convnetjs/index.html)

#### Machine Learning for crop yield forecast: Selected papers (Part 1)
- [Coupling machine learning and crop modeling improves crop yield prediction in the US Corn 
      Belt (2021)](https://www.nature.com/articles/s41598-020-80820-1), including discussion of:
  - Data pre-processing
  - Overfitting & Feature engineering
  - Feature reduction & Permutation importance
  - Hyperparameter selection, see, e.g., 
      [Hyperparameter Tuning](https://medium.com/analytics-vidhya/hyperparameters-80cb4f442e5),
      [Bayesian Hyperparameter Optimization](https://towardsdatascience.com/a-conceptual-explanation-of-bayesian-model-based-hyperparameter-optimization-for-machine-learning-b8172278050f)
  - [Ensemble Models](https://machinelearningmastery.com/stacking-ensemble-machine-learning-with-python/)
  - Metrics for ML performance, including RMSE, RRMSE, Coefficient of determination (R^2), MBE
- [A CNN-RNN Framework for Crop Yield Prediction](https://www.frontiersin.org/articles/10.3389/fpls.2019.01750/full)

#### Remote Sensing for crop yield analysis
- Intro to remote sensing satellites, e.g., 
   [Landsat](https://www.nasa.gov/mission_pages/landsat/overview/index.html),
   [Sentinel 1](https://sentinel.esa.int/web/sentinel/missions/sentinel-1),
   [Sentinel 2](https://sentinel.esa.int/web/sentinel/missions/sentinel-2)
- [Sun Synchronous Orbits](https://en.wikipedia.org/wiki/Sun-synchronous_orbit)
  - [Orbital coverage of Sentinel-2](https://www.esa.int/ESA_Multimedia/Videos/2016/08/Sentinel-2_global_coverage)
- Sensor wavelengths, indexes (combinations of wavelengths), e.g., 
  - [Sentinel 2 Bands and Combinations](https://gisgeography.com/sentinel-2-bands-combinations/))
  - [GISGeography on Spectral Bands in Remote Sensing](https://gisgeography.com/spectral-signature/)
  - [USDS Spectroscopy Lab](https://www.usgs.gov/labs/spectroscopy-lab)
- [Image Classification Techniques](https://gisgeography.com/image-classification-techniques-remote-sensing/)

#### Machine Learning for crop yield forecast: Selected papers (Part 2)
- [Crop yield prdiction based on machine learning models: Case of West African 
     Countries (2022)](https://reader.elsevier.com/reader/sd/pii/S2772375522000168)
- [Smallholder maize area and yield mapping at national scales with Google Earth 
     Engine (2019)](https://www.sciencedirect.com/science/article/abs/pii/S0034425719301610)
- [Crop yield prediction using machine learning: A systematic literature
     review (2020)](https://www.sciencedirect.com/science/article/pii/S0168169920302301)
  - Includes challenges in using ML for crop forecast



#### Programming illustrations

- ML pipeline for Crop yield forecast based on soil and history of weather and yields
  - Fetching yield data from 
     [USDA NASS historical crop data](https://quickstats.nass.usda.gov/)
  - Fetching county by county latitude-longitude using 
     [geopy.geocoders.nominatim](https://geopy.readthedocs.io/en/stable/)
  - Fetching soil data for counties using [GAEZ Data Portal](https://gaez.fao.org/pages/data-viewer)
  - Fetching historical weather data for counties from 
        [NASA POWER](https://power.larc.nasa.gov/)
  - Data transformations
  - Applying several ML algorithms and evaluating predictive capability
- ML pipeline that incorporates NDVI sensor data about crop growth through each year  
  - Identification of where soybean fields were, using 
       [USDA NASS historical cropland data](https://www.nass.usda.gov/Research_and_Science/Cropland/Release/index.php)
  - Fetching historical NDVI values for soybean fields, using
      [SentinelHub](https://sentinelhub-py.readthedocs.io/en/latest/index.html)
  - Data transformations
  - Applying the ML models as before, but using the additional NDVI data


## 6. The Road Forward

#### Key Themes

- Importance of our understanding of both agricultural productivity and possible
  climate change pathways as the basis for pro-actively working towards
  mitigation of the climate change impacts
- The challenges of moving an industry, in this case agriculture, in a direction
  that will mitigate climate change impacts, in terms of public policy (government
  incentives, etc.), stakeholder education, large and small landholder investments, ...


#### Introduction to Climate Smart Agriculture (CSA)

- World Economic Forum on [why](https://www.weforum.org/agenda/2020/11/why-we-must-scale-up-climate-smart-agriculture-csa-climate-hunger-population-resilience/)
- FAO [homepage on CSA](https://www.fao.org/climate-smart-agriculture/en/)
- FAO {Climate Smart Agriculture Sourcebook](https://www.fao.org/climate-smart-agriculture-sourcebook/en)
- Deloitte insight paper
  [Transforming Food Systems with Farmers: A Pathway for the
     EU (April 2022)](https://www2.deloitte.com/content/dam/Deloitte/us/Documents/consulting/us-transforming-food-systems-farmers.pdf)
- EU website [Climate Smart Agriculture](https://ec.europa.eu/eip/agriculture/en/news/climate-smart-agriculture)"


#### Simultaneously optimizing productivity and carbon sequestion

- [Trading carbon for food: Global comparison of carbon stocks
    vs. crop yields on agricultural
    land (2010)](https://www.pnas.org/doi/10.1073/pnas.1011078107)
- [Relocating croplands could drastically reduce the environmental
  impacts of global food production (2022)](https://doi.org/10.1038/s43247-022-00360-6)


#### Cropland Nutrient Budgets

- FAO on [Cropland Nutrient Budgets (2022)](https://www.fao.org/newsroom/detail/new-data-to-measure-cropland-nutrient-budgets/en)
- [Exploring Trade-Offs Between Profit, Yield, and the Environmental
  Footprint of Potential Nitrogen Fertilizer Regulations in the US
  Midwest (2022)](https://www.frontiersin.org/articles/10.3389/fpls.2022.852116/full)
- [How Does Crop Rotation Influence Soil Moisture, Mineral Nitrogen,
   and Nitrogen Use
   Efficiency? (2022)](https://www.frontiersin.org/articles/10.3389/fpls.2022.854731/full)

#### Alternative foods and agricultural practices

- FAO on [Mixed Crop-Livestock Farming](https://www.fao.org/3/Y0501E/y0501e00.htm)
- Agroforestry: growing livestock and/or crops under a managed tree canopy
  - [Agroforestry a model for ecological sustainability (2022)](https://www.sciencedirect.com/science/article/pii/B9780128229767000028)
  - The Guardian: [12 year agroforestry trial in
       UK (2021)](https://www.theguardian.com/environment/2021/may/16/im-seen-as-the-fool-the-farmers-putting-trees-back-into-the-uks-fields)
  - Historical snapshots:
    - [An Introduction to
        Agroforestry (1993)[https://apps.worldagroforestry.org/Units/Library/Books/PDFs/32_An_introduction_to_agroforestry.pdf?n=161]
    - [USDA Natl. Agroforestry Newsletter
       from 2003](https://www.fs.usda.gov/nac/assets/documents/insideagroforestry/2003summerfall.pdf)
- Aquaponics, a closed loop involving fish and vegetables:
  The Guardian [A new way of raising fish -- and
  vegetables (2023)](https://www.theguardian.com/environment/2023/sep/07/oko-farms-brooklyn-aquaponics-fish)

#### Note: There will not be a programming exercise with this topic area



