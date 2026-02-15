# Marine Biology — Comprehensive Self-Study Curriculum

> From foundational biology through PhD-level marine research. Organized by three knowledge types:
> - **Declarative** — taxonomy, ecological terms, chemical/physical facts (spaced repetition / Anki)
> - **Procedural** — lab techniques, field methods, data analysis, identification (learning by doing)
> - **Theory** — lectures, textbooks, research papers (building understanding)

---

## Table of Contents

### Foundations
1. [General Biology & Cell Biology](#general-biology)
2. [Chemistry for Marine Science](#chemistry)
3. [Ecology & Evolution](#ecology-and-evolution)
4. [Statistics for Marine Science](#statistics)

### Ocean Sciences
5. [Physical Oceanography](#physical-oceanography)
6. [Chemical Oceanography](#chemical-oceanography)
7. [Geological Oceanography](#geological-oceanography)
8. [Biological Oceanography](#biological-oceanography)

### Marine Organisms
9. [Marine Microbiology](#marine-microbiology)
10. [Marine Botany (Algae & Seagrasses)](#marine-botany)
11. [Marine Invertebrate Zoology](#marine-invertebrate-zoology)
12. [Ichthyology (Fish Biology)](#ichthyology)
13. [Marine Mammals, Seabirds & Reptiles](#marine-megafauna)

### Marine Ecosystems
14. [Coral Reef Ecology](#coral-reef-ecology)
15. [Deep-Sea Biology](#deep-sea-biology)
16. [Estuarine & Coastal Ecology](#estuarine-and-coastal)
17. [Polar Marine Ecology](#polar-marine-ecology)
18. [Pelagic Ecology (Open Ocean)](#pelagic-ecology)

### Applied Marine Science
19. [Marine Conservation & Policy](#marine-conservation)
20. [Fisheries Science & Management](#fisheries)
21. [Aquaculture](#aquaculture)
22. [Marine Biotechnology](#marine-biotechnology)
23. [Climate Change & Ocean Acidification](#climate-change)

### Advanced / Research
24. [Marine Genetics & Genomics](#marine-genetics)
25. [Paleoceanography & Paleobiology](#paleoceanography)
26. [Bioacoustics](#bioacoustics)
27. [Research Methods & Field Skills](#research-methods)
28. [Key Journals & PhD Resources](#phd-resources)

---

## General Biology

### Declarative
- Cell structure: prokaryotic vs eukaryotic, organelles, membranes
- Central dogma: DNA → RNA → protein, transcription, translation
- Genetics: Mendelian, molecular, population genetics basics
- Biochemistry: amino acids, nucleotides, lipids, carbohydrates, enzyme kinetics
- Phylogenetics: tree thinking, cladistics, molecular clocks

### Procedural
- Microscopy techniques (light, fluorescence, confocal, electron)
- PCR, gel electrophoresis, DNA extraction protocols
- Campbell Biology — end-of-chapter exercises
- MIT 7.013 problem sets

### Theory
- **MIT 7.013 — Introductory Biology**: https://ocw.mit.edu/courses/7-013-introductory-biology-spring-2018/
- **MIT 7.014 — Introductory Biology (ecology focus)**: https://ocw.mit.edu/courses/7-014-introductory-biology-spring-2005/
- **Textbook**: *Campbell Biology* by Urry et al. — the standard intro bio text
- **Textbook**: *Molecular Biology of the Cell* by Alberts et al. — the cell biology bible
- **Textbook**: *Molecular Biology of the Gene* by Watson et al.
- **Textbook**: *Lehninger Principles of Biochemistry* by Nelson & Cox

---

## Chemistry

### Declarative
- Seawater chemistry: salinity, major ions, pH, alkalinity, buffer system
- Carbonate system: CO2, HCO3-, CO3^2-, saturation states (omega)
- Nutrient chemistry: N, P, Si, Fe cycling
- Redox chemistry in marine sediments

### Theory
- **Textbook**: *Chemical Oceanography and the Marine Carbon Cycle* by Emerson & Hedges
- **Textbook**: *General Chemistry* by Atkins (or Zumdahl) for foundations
- **Textbook**: *Organic Chemistry* by Clayden et al. — for biochemistry connections

---

## Ecology and Evolution

### Declarative
- Population ecology: growth models (exponential, logistic), carrying capacity, r/K selection
- Community ecology: species interactions (competition, predation, mutualism, parasitism), niche theory, island biogeography
- Ecosystem ecology: energy flow, trophic levels, nutrient cycling, primary productivity
- Evolution: natural selection, genetic drift, gene flow, speciation, phylogeography, adaptive radiation
- Biodiversity metrics: species richness, Shannon index, Simpson index, beta diversity

### Procedural
- Build and analyze population models in R
- Construct phylogenetic trees from sequence data (MEGA, RAxML, BEAST)
- Design sampling protocols for diversity surveys
- Gotelli & Ellison — exercises (ecological statistics)

### Theory
- **Textbook**: *Ecology* by Cain, Bowman, Hacker — standard undergrad
- **Textbook**: *Evolutionary Analysis* by Herron & Freeman
- **Textbook**: *The Theory of Island Biogeography* by MacArthur & Wilson — classic
- **Textbook**: *The Ecology of Adaptive Radiation* by Schluter
- **Textbook**: *An Introduction to Behavioural Ecology* by Davies, Krebs, West

---

## Statistics for Marine Science

### Declarative
- Experimental design: controls, replication, randomization, pseudoreplication
- Parametric tests: t-test, ANOVA, regression, ANCOVA
- Non-parametric: Mann-Whitney, Kruskal-Wallis, Spearman correlation
- Multivariate: PCA, NMDS, PERMANOVA, ANOSIM, cluster analysis
- GLMs, GAMs, mixed-effects models, Bayesian approaches
- Spatial statistics, geostatistics, kriging

### Procedural
- **R tutorials**: https://www.r-project.org/
- PRIMER-e for multivariate ecological analysis
- Zuur et al. — worked examples in R
- Practice with real marine datasets (NOAA, OBIS)

### Theory
- **Textbook**: *Experimental Design and Data Analysis for Biologists* by Quinn & Keough — excellent for ecologists
- **Textbook**: *Mixed Effects Models and Extensions in Ecology with R* by Zuur et al. — essential for modern marine ecology
- **Textbook**: *Numerical Ecology* by Legendre & Legendre — the multivariate bible
- **Textbook**: *The Analysis of Biological Data* by Whitlock & Schluter — accessible intro
- **Free**: *R for Data Science* by Wickham & Grolemund — https://r4ds.had.co.nz/

---

## Physical Oceanography

### Declarative
- Ocean circulation: wind-driven (Ekman, Sverdrup, western boundary currents), thermohaline (AMOC, NADW, AABW)
- Water mass properties: T-S diagrams, potential temperature, potential density
- Waves: surface gravity waves, internal waves, Rossby waves, Kelvin waves
- Tides: diurnal, semidiurnal, spring/neap, tidal constituents
- Coriolis effect, geostrophic balance, Ekman transport, upwelling/downwelling
- El Nino/La Nina (ENSO), PDO, NAO, IOD
- Sea level rise mechanisms: thermal expansion, ice sheet contribution

### Procedural
- Analyze CTD profiles, T-S diagrams
- Calculate geostrophic currents from hydrographic data
- Use satellite data (SST, SSH, chlorophyll) from NASA/NOAA
- Ocean data tools: Ocean Data View, Python (xarray, cartopy)

### Theory
- **MIT 12.003 — Atmosphere, Ocean and Climate Dynamics**: https://ocw.mit.edu/courses/12-003-atmosphere-ocean-and-climate-dynamics-fall-2008/
- **Textbook**: *Introduction to Physical Oceanography* by Robert Stewart — free: https://www.colorado.edu/oclab/sites/default/files/attached-files/stewart_textbook.pdf
- **Textbook**: *Descriptive Physical Oceanography* by Talley, Pickard, Emery, Swift — comprehensive modern text
- **Textbook**: *Atmosphere, Ocean and Climate Dynamics* by Marshall & Plumb — accessible
- **Textbook**: *Ocean Circulation: Wind-Driven and Thermohaline Processes* by Huang
- **Textbook**: *Geophysical Fluid Dynamics* by Pedlosky — advanced/theoretical
- **Textbook**: Open University: *Ocean Circulation* — excellent self-study

---

## Chemical Oceanography

### Declarative
- Major and minor dissolved constituents, conservative vs non-conservative elements
- Carbonate chemistry: Bjerrum diagram, alkalinity, DIC, pCO2
- Nutrient distributions: nitrate, phosphate, silicate profiles, Redfield ratio (C:N:P = 106:16:1)
- Trace metals: iron limitation, iron hypothesis (Martin)
- Dissolved oxygen: oxygen minimum zones, biological oxygen demand
- Biogeochemical cycles: carbon, nitrogen (N fixation, denitrification, anammox), sulfur, phosphorus
- Stable isotopes: delta-13C, delta-18O, delta-15N as tracers
- Ocean acidification chemistry: declining pH, carbonate saturation

### Procedural
- Seawater sampling and analysis techniques (Winkler titration, spectrophotometry)
- Use CO2SYS software for carbonate system calculations
- Analyze nutrient profiles from World Ocean Atlas data

### Theory
- **Textbook**: *Chemical Oceanography and the Marine Carbon Cycle* by Emerson & Hedges — modern standard
- **Textbook**: *Introduction to the Chemistry of the Sea* by Pilson
- **Textbook**: *Marine Chemistry* by Millero — comprehensive
- **Textbook**: *Tracers in the Sea* by Broecker & Peng — classic
- Open University: *Seawater: Its Composition, Properties and Behaviour*

---

## Geological Oceanography

### Declarative
- Plate tectonics and ocean basin formation, mid-ocean ridges, subduction zones
- Marine sediments: terrigenous, biogenic, authigenic, cosmogenic
- Continental margins: shelves, slopes, abyssal plains, trenches
- Coral reef geomorphology: fringing, barrier, atoll (Darwin's subsidence theory)
- Sea floor spreading, hydrothermal vents, black/white smokers
- Paleoclimate proxies: foram shells, ice cores, coral records

### Theory
- **Textbook**: *Marine Geology* by Kennett
- **Textbook**: *The Floors of the Oceans* by Heezen & Tharp (historical)
- Open University: *The Ocean Basins: Their Structure and Evolution*

---

## Biological Oceanography

### Declarative
- Primary production: photosynthesis, chemosynthesis, gross vs net production
- Phytoplankton groups: diatoms, dinoflagellates, coccolithophores, cyanobacteria, picoeukaryotes
- Zooplankton: copepods, krill, salps, jellyfish, pteropods, meroplankton
- Microbial loop: bacteria, archaea, viruses, protists, DOM cycling
- Biological pump: export production, remineralization, marine snow
- Spring bloom dynamics, critical depth hypothesis (Sverdrup), iron fertilization
- Food webs: grazing, size-structured, microbial, classical

### Procedural
- Identify plankton under microscopy (FlowCam, traditional)
- Measure chlorophyll-a (fluorometry, spectrophotometry, satellite remote sensing)
- Calculate primary production (14C method, oxygen evolution)
- Analyze satellite ocean color data (NASA Ocean Color)

### Theory
- **Textbook**: *Biological Oceanography* by Miller & Wheeler
- **Textbook**: *Marine Ecology: Processes, Systems, and Impacts* by Kaiser et al. — excellent overview
- **Textbook**: *Dynamics of Marine Ecosystems* by Mann & Lazier — essential, connects physics to biology
- **Textbook**: *Marine Ecological Processes* by Valiela — comprehensive
- **Textbook**: *Aquatic Photosynthesis* by Falkowski & Raven
- **Textbook**: *Microbial Ecology of the Oceans* by Kirchman — essential modern reference

---

## Marine Microbiology

### Declarative
- Marine bacteria: SAR11, Prochlorococcus, Synechococcus, Vibrio, Roseobacter
- Marine archaea: Thaumarchaeota (ammonia oxidizers), DPANN, Asgard
- Marine viruses: phage dynamics, viral shunt, giant viruses
- Metabolic diversity: phototrophy, chemolithotrophy, heterotrophy, mixotrophy
- Nitrogen cycling microbes: nitrogen fixers (Trichodesmium), nitrifiers, denitrifiers, anammox
- Microbial biogeography, rare biosphere, seed bank hypothesis

### Procedural
- Flow cytometry for microbial enumeration
- 16S/18S rRNA amplicon sequencing (QIIME2, DADA2)
- Metagenomics and metatranscriptomics analysis
- Culturing marine microbes, dilution-to-extinction

### Theory
- **Textbook**: *Microbial Ecology of the Oceans* by David Kirchman — the standard
- **Textbook**: *Marine Microbiology: Ecology and Applications* by Munn
- **Textbook**: *Processes in Microbial Ecology* by Kirchman
- **Papers**: DeLong & Pace (2001) on uncultured marine diversity; Giovannoni (2017) on SAR11

---

## Marine Botany

### Declarative
- Macroalgae: Chlorophyta (green), Phaeophyta (brown, inc. kelp), Rhodophyta (red) — morphology, life cycles
- Seagrasses: Zostera, Posidonia, Thalassia — as ecosystem engineers
- Mangroves: species, adaptations, ecosystem services
- Salt marshes: zonation, Spartina, nutrient cycling
- Harmful algal blooms: red tides, Karenia, Pseudo-nitzschia, domoic acid, paralytic shellfish poisoning

### Theory
- **Textbook**: *Algae* by Graham, Graham, Wilcox — comprehensive
- **Textbook**: *Marine Botany* by Dawes
- **Textbook**: *Seagrass Ecology* by Hemminga & Duarte
- **Textbook**: *Biology of Mangroves and Mangrove Ecosystems* by Hogarth

---

## Marine Invertebrate Zoology

### Declarative
- Phyla: Porifera, Cnidaria, Ctenophora, Platyhelminthes, Annelida, Mollusca, Arthropoda (Crustacea), Echinodermata, Bryozoa, Brachiopoda, Chordata (tunicates)
- Body plans: diploblastic vs triploblastic, protostome vs deuterostome, coelomate vs acoelomate
- Key adaptations: cnidocytes, water vascular system, radula, compound eyes, metamorphosis
- Larval types: planula, trochophore, veliger, nauplius, zoea, pluteus, bipinnaria

### Procedural
- Invertebrate dissection and identification
- Plankton tow analysis (identifying meroplankton)
- Field surveys: quadrat sampling, transect methods

### Theory
- **Textbook**: *Invertebrates* by Brusca, Moore, Shuster — the standard
- **Textbook**: *Biology of the Invertebrates* by Pechenik — more accessible
- **Textbook**: *Marine Biology: Function, Biodiversity, Ecology* by Levinton
- **Textbook**: *The Invertebrates: A Synthesis* by Barnes, Calow, Olive

---

## Ichthyology

### Declarative
- Fish classification: Agnatha (jawless), Chondrichthyes (sharks, rays), Osteichthyes (bony fish)
- Anatomy: swim bladder, lateral line, operculum, gill structure, otoliths
- Physiology: osmoregulation, gas exchange, buoyancy, electroreception
- Life history: anadromous, catadromous, amphidromous, larval dispersal
- Coral reef fish ecology: cleaning stations, territoriality, sequential hermaphroditism

### Procedural
- Fish identification using dichotomous keys
- Otolith aging techniques
- Stomach content analysis, stable isotope analysis for trophic ecology
- Fish survey methods: BRUV, visual census, eDNA

### Theory
- **Textbook**: *The Diversity of Fishes* by Helfman, Collette, Facey, Bowen — the standard
- **Textbook**: *Biology of Fishes* by Bone & Moore
- **Textbook**: *Ecology of Fishes on Coral Reefs* by Sale

---

## Marine Megafauna

### Declarative
- Marine mammals: Cetacea (whales, dolphins, porpoises), Pinnipedia (seals, sea lions, walruses), Sirenia (manatees, dugongs), sea otters, polar bears
- Cetacean echolocation, baleen feeding strategies, dive physiology, migration patterns
- Sea turtles: 7 species, nesting behavior, navigation, threats
- Seabirds: Procellariiformes (albatrosses, petrels), Sphenisciformes (penguins), Charadriiformes (gulls, terns, auks)
- Marine reptiles: sea snakes, marine iguanas, saltwater crocodiles

### Procedural
- Photo-identification for cetaceans
- Satellite telemetry data analysis
- Stranding response protocols
- Population assessment: mark-recapture, distance sampling, line transect surveys

### Theory
- **Textbook**: *Marine Mammals: Evolutionary Biology* by Berta, Sumich, Kovacs — the standard
- **Textbook**: *The Biology of Marine Mammals* by Reynolds & Rommel
- **Textbook**: *Seabirds: An Identification Guide* by Harrison
- **Textbook**: *The Biology of Sea Turtles* by Lutz, Musick, Wyneken
- **Textbook**: *Whales, Dolphins, and Porpoises* (National Audubon Society)

---

## Coral Reef Ecology

### Declarative
- Coral biology: Scleractinia, zooxanthellae (Symbiodiniaceae) symbiosis, calcification
- Reef types: fringing, barrier, atoll, patch, mesophotic
- Reef zonation: reef flat, crest, slope, lagoon
- Coral bleaching: thermal stress thresholds, bleaching response, recovery
- Reef trophic structure: herbivory, corallivory, bioerosion
- Phase shifts: coral-dominated to algae-dominated states
- Reef connectivity: larval dispersal, gene flow, MPA network design

### Procedural
- Coral identification to genus level (skeletal morphology + molecular)
- Reef survey methods: line intercept transect, point intercept, quadrat, ReefCheck
- Bleaching assessment protocols (Coral Watch, Bleaching Response Index)
- Coral fragment transplantation and reef restoration techniques
- Underwater photography and photomosaicking

### Theory
- **Textbook**: *Coral Reefs: An Ecosystem in Transition* by Dubinsky & Stambler
- **Textbook**: *The Biology of Coral Reefs* by Sheppard, Davy, Pilling, Graham — modern comprehensive
- **Textbook**: *Coral Reef Ecology* by Sale (ed.) — advanced
- **Textbook**: *Corals of the World* by Veron — identification reference
- **Textbook**: *Reef-Building Corals* by Veron — biology and systematics
- **Free**: NOAA Coral Reef Conservation Program: https://coralreef.noaa.gov/
- **Free**: Coral Triangle Initiative resources

---

## Deep-Sea Biology

### Declarative
- Deep-sea zones: bathyal (200-2000m), abyssal (2000-6000m), hadal (>6000m)
- Hydrothermal vent communities: tubeworms (Riftia), vent shrimp, chemosynthetic bacteria, archaea
- Cold seeps: methane seeps, mud volcanoes, chemosynthetic communities
- Whale falls as succession habitats
- Bioluminescence: counterillumination, prey attraction, communication
- Adaptations: pressure tolerance, gigantism, reduced metabolism, unique sensory systems
- Abyssal plains ecology: deposit feeding, scavenging, extremely low density

### Procedural
- ROV and submersible operations (awareness)
- Deep-sea sampling: box cores, multicores, trawls, baited cameras
- Pressure-retaining sampling for deep-sea microbiology

### Theory
- **Textbook**: *The Ecology of the Deep-Sea Floor* by Gage & Tyler — the classic
- **Textbook**: *Deep-Sea Biology* by Herring — accessible introduction
- **Textbook**: *The Biology of the Deep Ocean* by Herring
- **Textbook**: *The Ecology of Deep-Sea Hydrothermal Vents* by Van Dover
- **Video**: MBARI lectures and footage: https://www.mbari.org/
- **Video**: Schmidt Ocean Institute: https://schmidtocean.org/
- **Video**: NOAA Ocean Exploration: https://oceanexplorer.noaa.gov/

---

## Estuarine and Coastal

### Declarative
- Estuary types: drowned river valley, bar-built, fjord, tectonic
- Estuarine circulation: salt wedge, partially mixed, well-mixed
- Intertidal zonation: splash, high, mid, low intertidal
- Coastal habitats: rocky intertidal, sandy beaches, mudflats, salt marshes, mangroves, seagrass beds
- Ecosystem services: nursery habitat, storm protection, carbon sequestration (blue carbon)

### Theory
- **Textbook**: *Estuarine Ecology* by Day, Crump, Kemp, Yanez-Arancibia
- **Textbook**: *The Ecology of Sandy Shores* by Brown & McLachlan
- **Textbook**: *Ecology of Estuaries* by Day et al.
- **Textbook**: *Between the Tides* by Bertness — intertidal ecology

---

## Polar Marine Ecology

### Declarative
- Arctic vs Antarctic: differences in geography, ice dynamics, fauna
- Sea ice ecology: ice algae, sympagic communities, ice edge blooms
- Polar adaptations: antifreeze proteins, lipid storage, metabolic cold adaptation
- Key species: Antarctic krill, emperor penguins, narwhals, polar bears, ice seals
- Climate change impacts: sea ice loss, ice shelf collapse, polar amplification

### Theory
- **Textbook**: *Polar Ecology* by Stonehouse
- **Textbook**: *The Biology of Polar Regions* by Thomas et al.
- **Textbook**: *Sea Ice* by Thomas & Dieckmann

---

## Pelagic Ecology

### Declarative
- Epipelagic, mesopelagic, bathypelagic, abyssopelagic zones
- Diel vertical migration: largest animal migration on Earth
- Mesopelagic fish biomass: role in carbon export
- Ocean gyres, oligotrophic vs eutrophic systems
- Convergence zones, fronts as biodiversity hotspots
- Sargasso Sea ecology

### Theory
- **Textbook**: *Dynamics of Marine Ecosystems* by Mann & Lazier
- **Textbook**: *Pelagic Ecology* by Lalli & Parsons
- **Textbook**: *Biological Oceanographic Processes* by Parsons, Takahashi, Hargrave

---

## Marine Conservation

### Declarative
- Marine Protected Areas: categories (IUCN I-VI), no-take zones, effectiveness evidence
- Endangered species: IUCN Red List, CITES, ESA
- Threats: overfishing, bycatch, pollution (plastics, oil, nutrients), habitat destruction, invasive species, noise, climate change
- International law: UNCLOS, CBD, UNFCCC, Paris Agreement, High Seas Treaty
- Ecosystem-based management, Marine Spatial Planning
- Blue carbon: mangroves, seagrass, salt marsh carbon sequestration

### Procedural
- Environmental Impact Assessment methods
- Population viability analysis (PVA)
- Designing MPA networks (connectivity, representation, replication)
- Citizen science: iNaturalist, Reef Check, eBird for seabirds

### Theory
- **Textbook**: *Marine Conservation Biology* by Norse & Crowder
- **Textbook**: *Marine Conservation: Science, Policy, and Management* by Ray & McCormick-Ray
- **Textbook**: *Marine Ecology: Conservation and Management* by Groombridge & Jenkins
- **Textbook**: *Fundamentals of Conservation Biology* by Hunter & Gibbs (general but excellent)
- **Free**: IUCN publications: https://www.iucn.org/resources/publications

---

## Fisheries

### Declarative
- Stock assessment: biomass estimation, catch per unit effort (CPUE), virtual population analysis
- Population dynamics: surplus production models, age-structured models (Beverton-Holt, Ricker)
- Maximum sustainable yield (MSY), fishing mortality, spawning stock biomass
- Gear types: trawl, purse seine, longline, gillnet, pot/trap — selectivity and bycatch
- Fisheries management tools: TAC, ITQ, seasonal closures, gear restrictions, MPAs
- Overfishing: growth overfishing, recruitment overfishing, ecosystem overfishing

### Procedural
- Stock assessment modeling (R packages: FLR, SS3, JABBA)
- Fish aging (otolith analysis)
- Bycatch monitoring and mitigation

### Theory
- **Textbook**: *Fisheries Biology, Assessment and Management* by King — accessible
- **Textbook**: *Quantitative Fisheries Stock Assessment* by Hilborn & Walters — the standard
- **Textbook**: *An Introduction to the Biology of Marine Life* by Sumich & Morrissey
- **Textbook**: *Fisheries Ecology and Management* by Wootton & Smith

---

## Aquaculture

### Declarative
- Culture systems: extensive, semi-intensive, intensive, RAS, offshore cages
- Key species: salmon, shrimp, tilapia, oysters, mussels, seaweed
- Feed and nutrition, FCR (feed conversion ratio)
- Disease management: viral, bacterial, parasitic
- Environmental impacts: effluent, escapees, disease transfer, habitat conversion
- Sustainable aquaculture: IMTA (Integrated Multi-Trophic Aquaculture), ASC certification

### Theory
- **Textbook**: *Aquaculture: Farming Aquatic Animals and Plants* by Lucas & Southgate
- **Textbook**: *Introduction to Aquaculture* by Stickney
- **Textbook**: *Fish Diseases and Disorders* by Woo & Bruno (3 vols)

---

## Marine Biotechnology

### Declarative
- Marine natural products: pharmaceutical compounds from sponges, tunicates, mollusks
- Bioprospecting: discovery pipeline, drug leads (cytarabine, ET-743)
- Marine enzymes: extremophilic enzymes, industrial applications
- Biofouling and antifouling
- Marine genetic resources and access/benefit sharing (Nagoya Protocol)

### Theory
- **Textbook**: *Marine Biotechnology* by Colwell
- **Textbook**: *Drugs from the Sea* by Fusetani (ed.)
- **Textbook**: *Marine Pharmacology* by Bhakuni & Rawat

---

## Climate Change

### Declarative
- Ocean heat uptake: >90% of excess heat, marine heat waves
- Ocean acidification: pH decline (~0.1 units since pre-industrial), impacts on calcifiers
- Deoxygenation: expanding oxygen minimum zones
- Sea level rise: thermal expansion + ice melt
- Species range shifts: tropicalization, poleward migration
- Coral bleaching: mass events (1998, 2010, 2016, 2017, 2020, 2024)
- Tipping points: AMOC slowdown, ice sheet collapse, coral reef loss

### Procedural
- Analyze ocean temperature and pH trends from NOAA/IPCC datasets
- Use CO2SYS for carbonate chemistry projections
- Species distribution modeling under future scenarios (MaxEnt, BIOMOD)

### Theory
- **IPCC Reports**: Ocean and Cryosphere chapter (SROCC): https://www.ipcc.ch/srocc/
- **Textbook**: *Ocean Acidification* by Gattuso & Hansson
- **Textbook**: *Climate Change Biology* by Hannah
- **Textbook**: *The Oceans and Climate* by Bigg

---

## Marine Genetics

### Declarative
- Population genetics: Hardy-Weinberg, Fst, gene flow, genetic drift in marine populations
- Phylogeography: barriers to gene flow, cryptic species
- eDNA: environmental DNA sampling, metabarcoding, species detection
- Genomics: whole genome sequencing, RADseq, transcriptomics, epigenetics
- Conservation genetics: effective population size, inbreeding, genetic rescue, captive breeding

### Procedural
- DNA extraction from marine tissues
- Bioinformatics: BLAST, alignment, phylogenetic tree construction, population genetics software (Arlequin, STRUCTURE, ADMIXTURE)
- eDNA sampling protocols and analysis
- R packages: pegas, adegenet, PopGenome

### Theory
- **Textbook**: *Marine Population Genetics* by Palumbi
- **Textbook**: *Molecular Ecology* by Freeland, Kirk, Petersen
- **Textbook**: *Principles of Population Genetics* by Hartl & Clark (general but essential)
- **Textbook**: *Bioinformatics and Functional Genomics* by Pevsner

---

## Paleoceanography

### Declarative
- Proxies: foraminifera (delta-18O, Mg/Ca), ice cores, coral banding, alkenones, TEX86
- Major events: Snowball Earth, PETM, K-Pg extinction, Messinian salinity crisis
- Ocean circulation changes through geological time
- Sea level fluctuations: glacial-interglacial cycles
- Marine extinctions: causes, patterns, recovery timescales

### Theory
- **Textbook**: *Paleoceanography of the Atlantic Ocean* by Hsü
- **Textbook**: *Climate Change: An Interdisciplinary Approach* by Ruddiman
- **Textbook**: *Earth's Climate: Past and Future* by Ruddiman — excellent overview
- **Textbook**: *Paleoclimatology* by Bradley

---

## Bioacoustics

### Declarative
- Sound propagation in water: speed of sound, SOFAR channel, deep sound channel
- Cetacean vocalizations: whale song, echolocation clicks, signature whistles
- Fish sounds: swim bladder drumming, stridulation
- Snapping shrimp as dominant ocean sound source
- Anthropogenic noise: shipping, sonar, seismic surveys, pile driving
- Impacts: masking, behavioral disturbance, physiological stress, strandings

### Procedural
- Passive acoustic monitoring (PAM) setup and analysis
- Spectrogram analysis (Raven, Audacity, PAMGuard)
- Sound exposure level (SEL) calculations

### Theory
- **Textbook**: *Marine Bioacoustics* by Au & Hastings
- **Textbook**: *Principles of Marine Bioacoustics* by Au
- **Textbook**: *Marine Mammals and Noise* by Richardson et al.

---

## Research Methods

### Field Skills
- SCUBA diving (AAUS scientific diving certification)
- Small boat handling and seamanship
- CTD deployment and data processing
- Plankton net tows and sample preservation
- Underwater visual census and photo/video transects
- Sediment coring and benthic sampling (grabs, box cores)

### Data & Tools
- **R for ecology**: vegan, ggplot2, dplyr, tidyverse
- **Python**: xarray, cartopy, scipy, scikit-learn for ocean data
- **GIS**: QGIS, ArcGIS for marine spatial analysis
- **Remote sensing**: NASA Ocean Color, Copernicus Marine Service, Google Earth Engine
- **Databases**: OBIS (https://obis.org/), WoRMS (https://www.marinespecies.org/), GenBank, GBIF
- **Ocean data**: World Ocean Atlas, Argo floats, NOAA buoy data

---

## PhD Resources

### Key Journals
- *Nature* and *Science* (marine papers)
- *Marine Ecology Progress Series* (MEPS)
- *Limnology and Oceanography*
- *Coral Reefs*
- *Deep-Sea Research* (Parts I & II)
- *Journal of Experimental Marine Biology and Ecology*
- *Marine Biology*
- *Global Change Biology*
- *ICES Journal of Marine Science*
- *Frontiers in Marine Science*
- *Annual Review of Marine Science*
- *Proceedings of the Royal Society B* (marine papers)
- *Molecular Ecology*
- *Conservation Biology*
- *Fish and Fisheries*

### Top Graduate Programs
- **MIT/WHOI Joint Program**: https://mit.whoi.edu/ — the premier US program
- **Scripps Institution of Oceanography (UCSD)**: https://scripps.ucsd.edu/
- **University of Washington — School of Oceanography**
- **Stanford — Hopkins Marine Station**
- **University of Hawaii at Manoa — SOEST**
- **Oregon State University — CEOAS**
- **University of Southampton — National Oceanography Centre** (UK)
- **University of Plymouth** (UK)
- **James Cook University** (Australia) — coral reef specialization
- **University of Tasmania — IMAS** (Australia)
- **Oxford & Cambridge** — marine biology/zoology programs

### Essential Textbooks Summary (The Core Shelf)
1. *Marine Biology: Function, Biodiversity, Ecology* — Levinton
2. *Oceanography: An Invitation to Marine Science* — Garrison (or Trujillo & Thurman)
3. *Marine Ecology: Processes, Systems, and Impacts* — Kaiser et al.
4. *Dynamics of Marine Ecosystems* — Mann & Lazier
5. *Marine Ecological Processes* — Valiela
6. *The Diversity of Fishes* — Helfman et al.
7. *Invertebrates* — Brusca et al.
8. *Chemical Oceanography* — Emerson & Hedges
9. *Descriptive Physical Oceanography* — Talley et al.
10. *Designing Data-Intensive Applications* — just kidding. *Quantitative Fisheries Stock Assessment* — Hilborn & Walters

### Free Online Resources
- **NOAA Education**: https://www.noaa.gov/education
- **Smithsonian Ocean**: https://ocean.si.edu/
- **MarineBio**: https://marinebio.org/
- **Monterey Bay Aquarium Research Institute**: https://www.mbari.org/
- **Ocean Biogeographic Information System**: https://obis.org/
- **Census of Marine Life**: https://www.coml.org/
