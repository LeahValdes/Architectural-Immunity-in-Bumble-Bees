#### Code: <br/>

#### Outhouse_Project_Rmk_paper.Rmd - all code pertaining to statistical analyses for paper

#### Data: <br/>

### Question 1: <br/>
#### Nest_modification.csv - <br/>
  Colony - unique microcolony ID <br/>
  Rep - which of 2 repeated measures the measurement was from <br/>
  ID - unique identifier for the measurement <br/>
  Location - whether measurement was taking from area under nest, or under foam block <br/>
  Total_pixels - total number of pixels in area estimated in Image J <br/>
  Green_pixels - number of green pixels (feces) estimated in ImageJ <br/>

### Question 2: <br/>
#### Micro_Liners.csv - quantification of feces in nest vs. peripheral cavity (for colonies without access to foraging arena) <br/> 
  Round - the block that the experiments were performed during <br/> 
  Source - full Biobest colony that the microcolony bees were sourced from <br/> 
  Micro - unique microcolony ID <br/>
  Cavity - whether the measurement is from the nest cavity, or peripheral cavity (outhouse) <br/>
  Treatment - whether the colony was inoculated with C. bombi (Crithidia) or a sham inoculum (Control) <br/> 
  Replicate - which of 3 repeated measures the measurement was from <br/> 
  Green_Pixels - number of green pixels (feces) estimated in ImageJ <br/> 
  Total_Pixels - total number of pixels in area estimated in Image J <br/> 
  Prop_Green - Green-Pixels / Total_Pixels <br/>

#### Greenhouse_Liners.csv - defecation results from experiment testing defecation behavior in colonies with access to foraging cage <br/> 
  Block - block during which experiment was performed <br/>
  Source - full Biobest colony that the microcolony bees were sourced from <br/>
  Micro - unique microcolony ID <br/>
  Treatment - whether the colony was inoculated with C. bombi (Crithidia) or a sham inoculum (Control) <br/> 
  Area - whether measurement was taking from nest cavity (Nest), peripheral cavity (Outhouse), or artificial flower feeder (Feeder) <br/> 
  Red_Pixels - total number of colored pixels (feces) estimated in ImageJ <br/>
  Total_Pixels - total number of pixels in area estimated in Image J <br/>
  Proportion_Red - Red_Pixels / Total_Pixels Sucrose_Consumption - difference in amount of sucrose in feeder at end of experiment vs. when first put in foraging cage <br/>
  Survivors - number of live bees at end of experiment <br/>
  Mortality - number of dead bees at end of experiment <br/>

#### Greenhouse_Final.csv - results from end of experiment testing defecation behavior in colonies with access to foraging cage <br/> 
  Date - when observations were made (end of experiment) <br/>
  Set - matched colony group identifier <br/>
  Source - which biobest source colony the microcolonies were created with bees from <br/>
  Micro - unique microcolony ID <br/>
  Treatment - whether the colony was inoculated with C. bombi (Crithidia) or a sham inoculum (Control) <br/>
  Alive_Nest - number of workers alive at the end of the experiment <br/>
  Dead_Nest - number of corpses in the nest box at the end of the experiment <br/>
  Dead_Outhouse - number of corpses in the peripheral cavity at the end of the experiment <br/>
  Dead_Outside - number of corpses int he foraging cage at the end of the experiment <br/>
  Nest_weight - weight of the built wax structure (pupae, honeypots, wax) at the end of the experiment <br/> 
  Honeypots - number of honeypots <br/>
  Pupae - number of pupae <br/>
  Males - number of males <br/>
  Sucrose consumption - difference in amount of sucrose in feeder at end of experiment vs. when first put in foraging cage <br/>
  Prop_Feeders - estimated area with feces on feeder / total area of feeder <br/>
  Prop_Nest - estimated area with feces in nest cavity / total area of nest cavity <br/>
  Prop_Outhouse - estimated area with feces in peripheral cavity / total area of peripheral cavity <br/>

### Question 3: 
#### Colony_mechanism.csv - infection data from experiment testing whether removal of feces/corpses contribute to social immunity <br/>
  Bee - unique ID for bee sample <br/>
  Colony - full source colony ID <br/>
  Location - whether inoculum was added to nest box (Nest) or peripheral cavity (Outhouse) <br/>
  Inoculum - whether inoculum was contaminated Feces or Corpse <br/>
  Crithidia - count of number of C. bombi cells in 5 squares of hemocytometer (infection intensity) <br/>

#### Colony_mech_video.csv - data from experiment testing how often workers touch infected feces or corpses in nest vs. peripheral cavity <br/> 
  Video - name of video file <br/>
  Colony - full source colony ID <br/>
  Location - whether inoculum was added to nest box (Nest) or peripheral cavity (Outhouse) <br/>
  Inoculum - whether inoculum was contaminated Feces or Corpse <br/>
  Contacts - number of times bees touched the contaminated inoculum in 20 minute observation period <br/>
  Start_time - time of beginning of observation period in video <br/>
  Stop_time - time of end of observation period in video <br/>

### Question 4: 
#### Outhouse_Colonies.csv - 
  Colony - unique colony identifier <br/>
  Cavity_treatment - whether the colony had access to a peripheral cavity (Outhouse) or not (Control) <br/>
  Inoc_treatment - proportion of workers initially inoculated with C. bombi (3% or 30%) <br/>
  Inoc_Date - when colonies were inoculated (2024) <br/>
  Weight - weight of nest box at start of experiment (not including outhouse or tunnel) <br/>
  Pre-screen - number of bees with detected C. bombi infection in sample of 5 screened before inoculation <br/>
  Arrived - date colonies arrived at lab in Ithaca, NY <br/>
  Filename1 - filename of first image used to count number of workers <br/>
  Bee_count1_lily / Bee_count1_leah - number of workers counted in image from Filename1 by two observers <br/>
  Filename2 - filename of second image used to count number of workers <br/>
  Bee_count2_lily / Bee_count2_leah - number of workers counted in image from Filename2 by two observers <br/>
  Inoc_3% - number of bees to inocluate if in 3% inoculation condition <br/>
  Inoc_30% - number of bees to incoulate if in 30% inoculation condition <br/>
  Final_box_weight - weight of nest box (excluding outhouse and tunnel) at end of experiment (grams) <br/>
  Final workers_n - number of workers alive at end of experiment <br/>
  Final_workers_weight - weight of workers at end of experiment (grams) <br/> 
  Final_gynes_n - number of new queens alive at end of experiment <br/>
  Final_gynes_weight - weight of gynes at end of experiment (grams) <br/>
  Final_males_n - number of males alive at end of experiment <br/>
  Final_males_weight - weight of males alive at end of experiment (grams) <br/>
  Final_larvae_n - number of larvae alive at end of experiment <br/>
  Final_larvae_weight - weight of larvae alive at end of experiment (grams) <br/>
  Final_pupae_n - number of pupae alive at end of experiment <br/>
  Final_pupae_weight - weight of pupae alive at end of experiment (grams) <br/>

#### Outhouse_weekly.csv - weekly C. bombi infection measurements <br/>
  Week - week from start of experiment (1 represents 1 week after inoculation) <br/>
  Date - date when measurements were made <br/>
  Colony - unique colony identifier Sampling - number of sample (1-15) from each colony <br/>
  Bee_ID - unique identifier for each bee <br/>
  Cavity_treatment - whether the colony had access to a peripheral cavity (Outhouse) or not (Control) <br/>
  Inoc_treatment - proportion of workers initially inoculated with C. bombi (3% or 30%) <br/>
  No_crithidia - number of C. bombi cells counted in 5 squares of hemocytometer <br/>
  Marginal_cell - length of marginal cell (proxy for body size) <br/>
  screened_by - whether sample was screened by Leah (LV) or Lily (LB) <br/>

#### Outhouse_Weekly_Performance.csv - weekly measurements of colony growth <br/>
  Colony - unique colony identifier <br/>
  Inoc_treatment - proportion of workers initially inoculated with C. bombi (3% or 30%) <br/>
  Final_box_weight - weight of nest box (excluding outhouse and tunnel) at end of experiment (grams) <br/>
  Week - week from start of experiment (0: inoculation; 6: termination) <br/>
  Date - date of measurement <br/>
  Males - whether males are present (yes/no) <br/>
  Gynes - number of gynes in colony <br/>
  Gyne_pupae - whether gyne pupae are present (yes/no) <br/>
  Dead_nest - number of dead workers in nest cavity <br/>
  Dead_outh - number of dead workers in peripheral cavity <br/> 
  Weight - weight of colony nest box (excluding peripheral cavity and tunnel) <br/>

#### Aspergillus.csv - data on fungal infection from within-colony transmission experiment <br/>
  Aspergillus - number of dead individuals with visible A. flavus fruiting bodies <br/>
  Colony_ID - unique colony identifier <br/>
  Cavity_treatment - whether the colony had access to a peripheral cavity (Outhouse) or not (Control) <br/>
  Inoc_treatment - proportion of workers initially inoculated with C. bombi (3% or 30%) <br/>
  Final_box_weight - weight of nest box (excluding outhouse and tunnel) at end of experiment (grams) <br/>
  Final workers_n - number of workers alive at end of experiment <br/>
  Final_workers_weight - weight of workers at end of experiment (grams) <br/>
  Final_gynes_n - number of new queens alive at end of experiment <br/>
  Final_gynes_weight - weight of gynes at end of experiment (grams) <br/>
  Final_males_n - number of males alive at end of experiment <br/>
  Final_males_weight - weight of males alive at end of experiment (grams) <br/>
  Final_larvae_n - number of larvae alive at end of experiment <br/>
  Final_larvae_weight - weight of larvae alive at end of experiment (grams) <br/>
  Final_pupae_n - number of pupae alive at end of experiment <br/>
  Final_pupae_weight - weight of pupae alive at end of experiment (grams) <br/>
  Initial weight - weight of colony box (excluding outhouse and tunnel) at start of experiment (grams) <br/>

#### Climate.csv - temperature and relative humidity measurements for nest vs. peripheral cavity, for colonies with access to peripheral cavity
