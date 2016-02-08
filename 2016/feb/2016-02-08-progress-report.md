##  Looking back
Evaluating the assigned tasks from the previous week of Feb-01 to Feb-05
 
 1) new branch of Portland repo, cleaned for stencil ( project: [ialsa-2015-portland](https://github.com/IALSA/IALSA-2015-Portland))  
	- not done. reformulated. instead of cleaning the entire stencil, our discussion on [2016-02-04](https://github.com/IALSA/ialsa-2015-portland-stencil/issues/15) suggested I focus on the `./reports` folder   
	
 2) create a [dynamic table](https://github.com/IALSA/IALSA-2015-Portland/issues/117) for retrieving model estimates from output files. (advances two projects: [ialsa-2015-portland](https://github.com/IALSA/IALSA-2015-Portland) and [portland-physical-cognitive](https://github.com/IALSA/Portland-physical-cognitive))     
	- not done. now this objective has been move in priority. We have to verify the accuracy of the parsing script before building the front end. THis, still will remain relevant, but can wait.    
	
 3) Read Coulombe et al. paper and start developing literature review for wave-inclusion paper   
	- Done. Coulombe et al (2015) turned out to be a poor fit as a key paper. Focus has shifted to Rast and Hofer (2014) as Hertzog (2006, 2008) papers. See log : https://github.com/IALSA/wave-inclusion/issues/10    
	
 4) complete the transfer of the original MAP presentation and prepare to go over it with C.Brown, so that she may develop independent skills necessary to produce/maintain dynamic documents in this project   
	- Almost done. The wave-inclusing repository has been shaped up very well and C.Brown got some scripting homework to go through. 


## Detailed Account 
of my professional activity from 2016-02-01 to 2016-02-07. 


## TECH SUPPORT

## [ialsa-study-curator](https://github.com/IALSA/ialsa-study-curator)
**description**: Peparing the data from longitudinal studies for use by the members of the iLifespan lab.      
**progress**:  spent quite some time on [grooming LASA](https://github.com/IALSA/LASA/issues/5) and [grooming MAP](https://github.com/IALSA/MAP/issues/16)   
**roadblocks**: time      
**next steps**: R.Graham will contact me and arrange the next meeting, likely to occur on Feb 15 or Feb 16.  R.Vandetelli expressed interest in joining R.Graham in learning about LASA processing and seems to be joining the meeting.  
**notes**:


## [ialsa-2015-portland](https://github.com/IALSA/IALSA-2015-Portland)  
**description**: A script development. Developing reporting tools for coordinated analysis with replication (CAR) workshop, conducted in Portland on Feb 22-23, 2015.    
**progress**:  In a conversation with W.Beasely and M.Shahid, I identified a new objective: solidify parsing scripts. Accuracy of result extraction must be made verifiable to isolate human processing errors and explore methodological reason for aberrant values. see [log](https://github.com/IALSA/ialsa-2015-portland-stencil/issues/15)        
**roadblocks**: none    
**next steps**: 1) prepare the environment to solidify the parser using IalsaSynthesis.  *Objective*: create a place for M.Shahid and W.Beasley to refine and test the parser. This advances  [ialsa-2015-portland](https://github.com/IALSA/IALSA-2015-Portland), however, it should be developed in the stencil to keep manageable; transfer the solution later.     2) Go through `IALSA-2015-Portland/reports` folder and determine what is worth keeping and what needs to be cleaned. Leave only the reports with valuable contributions. Put sandbox items into a sandbox. See discussion on [2016-02-04](https://github.com/IALSA/ialsa-2015-portland-stencil/issues/15).         
**notes**:  


## [ialsa-2015-portland-stencil](https://github.com/IALSA/ialsa-2015-portland-stencil)
**description**: Applying lessons from the Feb 2015 Portland workshop (and its repo) to a newer architecture.  Basically, we want to recreate Portland, but now to be ready for what is coming, so we can see whether the tool that we have developed can accommodate the complexity of the workshop.     
**progress**:  had a productive meeting with W.Beasley and M.Shahid. Focusing on the parser right now. The [log](https://github.com/IALSA/ialsa-2015-portland-stencil/issues/15).    
**roadblocks**: The original Portland repo contains a lot of junk code, legacy of time-pressured development. These "junk" files block the stencil progress, requiring Maleeha to go through and annotate more files        
**next steps**: [issues](https://github.com/IALSA/ialsa-2015-portland-stencil/issues) for the full scope. tactical = 1) create a Syntax Creator - a system for generating Mplus model scripts to be executed. The parser will reference this Syntax Creator, getting instructions on what to look for in the text output.    
**notes**:  



## SCIENCE

## [ialsa-car-methods](https://github.com/IALSA/ialsa-car-methods)
**description**: A manuscript production. Paper on implementing the CAR methods pioneers in Portland.  
**progress**:  none    
**roadblocks**: more time       
**next steps**: 1) create a diagram depicting the flow of information through the work environment.      
**notes**: 

### [portland-physical-cognitive](https://github.com/IALSA/Portland-physical-cognitive)
**description**:  A manuscript production. Focuses on the models from the [Portland CAR workshop](https://github.com/IALSA/IALSA-2015-Portland)  in which *physical* and *cognitive* outcomes form a bivariate linear structure.     
**progress**:  none   
**roadblocks**:  Requiring input from A.Piccinin. Some tactical decisions are still required: as the original taxonomy was revised during the last meeting with A.Piccinin, new domains have crystallized:  `perception` and `verbal reasoning`. They need to be incorporated into the continuum to finalize the current state of the graph.   See [issue #4](https://github.com/IALSA/Portland-physical-cognitive/issues/4). This of all things, justifies a meeting. WOuld be nice to review/verify this classification again. If no meeting is arranged, please provide the feedback in the comments of the referenced issue.       
**next steps**:   create a [dynamic table](https://github.com/IALSA/IALSA-2015-Portland/issues/117) for retrieving model estimates from output files. This coincide with the tech support task for the Portland project.    
**notes**: 


### [wave-inclusion](https://github.com/IALSA/wave-inclusion)
**description**: How does the number of waves included into the analysis affect the conclusions from a longitudinal study?    
**progress**:  made advances on shaping up MAP data and its repo for Data Curator. Discussed literature. see [log](https://github.com/IALSA/wave-inclusion/issues/10)   
**roadblocks**: none apparent        
**next steps**: new paper in focus: Rast and Hofer (2014), Hertzog et al (2006, 2008)   
**notes**:  



### What needs to be done   
*ranked according to perceived importance/impact*     
*implementation will favor this order, unless explicitly overwritten*   
*tasks will carry over to the new week, if not completed or deprecated*    

1 -(TECH)- prepare the environment to solidify the parser using IalsaSynthesis package.  *Objective*: a reliable procedure to minimize parsing errors from estimation extraction. (advances [ialsa-2015-portland](https://github.com/IALSA/IALSA-2015-Portland) and [ialsa-2015-portland-stencil](https://github.com/IALSA/ialsa-2015-portland-stencil)) 

2 -(TECH)- Engineer a Syntax Creator -  system for generating Mplus model scripts to be executed. *Objective*: template Mplus script is fed to R, which produces modified Mplus scripts, designed for optimized parsing. The parser will reference this Syntax Creator, getting instructions on what to look for in the text output. (advances [ialsa-2015-portland-stencil](https://github.com/IALSA/ialsa-2015-portland-stencil))   

3 -(SCIENCE)- Read Rast and Hofer (2014),  skim through  Hertzog et al (2006, 2008). Prepare to discuss with C.Brown. (advances [wave-inclusion](https://github.com/IALSA/wave-inclusion))       

4 -(TECH)- Prepare `wave-inclusion` repo to describe to C.Brown the built-in reproducibility. (advances [wave-inclusion](https://github.com/IALSA/wave-inclusion))  

5 -(TECH)- Go through `IALSA-2015-Portland/reports` folder and determine what is worth keeping and what needs to be cleaned. Leave only the reports with valuable contributions. Put sandbox items into a sandbox. See discussion on [2016-02-04](https://github.com/IALSA/ialsa-2015-portland-stencil/issues/15).   (advances [portland-physical-cognitive](https://github.com/IALSA/Portland-physical-cognitive), [ialsa-2015-portland](https://github.com/IALSA/IALSA-2015-Portland), and  [ialsa-2015-portland-stencil](https://github.com/IALSA/ialsa-2015-portland-stencil) )   

6 -(TECH)- create a [dynamic table](https://github.com/IALSA/IALSA-2015-Portland/issues/117) for retrieving model estimates from output files. (advances two projects: [ialsa-2015-portland](https://github.com/IALSA/IALSA-2015-Portland) and [portland-physical-cognitive](https://github.com/IALSA/Portland-physical-cognitive)). *Objective*:  flexible dynamical system of reviewing the numerical values of models from the estimation. (advances [portland-physical-cognitive](https://github.com/IALSA/Portland-physical-cognitive))       


7 -(SCIENCE)- create a diagram depicting the flow of information through the work environment (advances [ialsa-car-methods](https://github.com/IALSA/ialsa-car-methods)) 
