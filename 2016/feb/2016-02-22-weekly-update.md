Progress report

TECH SUPPORT 

A. [ialsa-2015-portland](https://github.com/IALSA/IALSA-2015-Portland)   

B. [ialsa-2015-portland-stencil](https://github.com/IALSA/ialsa-2015-portland-stencil)  
  1. progress. conceptualized the pipeline for the first REDCap survey: the Pre-conference survey. see [log](https://github.com/IALSA/ialsa-2015-portland-stencil/issues/21) for details.
  2. progress. debugged the syntax-creator. now it works. discussed with W.Beasley the naming rules for the flexible elements in the MPlus prototype, from which MPlus syntax will be generated using the R scripts we are developing.  
  3. next steps. play with syntax-creator script to understand how to optimize it.    
  4. next steps. be ready to test-drive the PCS to offer the feedback during the next meeting.   
  
C. [ialsa-study-curator](https://github.com/IALSA/ialsa-study-curator)   
  1. progress. Went through folder structure of MAP and LASA to see the similarities. From these two instances I have abstracted a [template](https://github.com/IALSA/ialsa-study-curator/tree/new-study-template) for adding new longitudinal studies to the curatorship project. This template would have to be modified as new studies are added, but it's a start.    
  2. progress.  Shaped up [HRS](https://github.com/IALSA/HRS) for Study curatorship. Cleaned .gitignore. started a new architecture in order to fit into the current template.  
  3. next steps. Go over the scripts that prepare HRS data, edit, optimize, and documente them,  creating a `reproduce.R` script that would automate the data creation from the raw files.   
  4. progress. test of new data replication scripts is successful. C.Brown created an analysis ready data of MAP from the raw csv files using the current version of the [ialsa-study-curator: MAP](https://github.com/IALSA/MAP) script.
  5. next steps. Meeting with C.Brown on Tue, Feb 23 to incorportate her later [data transformations](https://github.com/IALSA/MAP/blob/master/scripts/data/2-transformations.R) into the grooming pipeline. 


SCIENCE   
 
A. [ialsa-car-methods](https://github.com/IALSA/ialsa-car-methods)    
  

B. [wave-inclusion](https://github.com/IALSA/wave-inclusion)    
  1. progress. established data provisioning chain from [ialsa-study-curator: MAP](https://github.com/IALSA/MAP) repository.
  2. next steps. calibrate example mplus scripts to estimate the models based on the structure of the provisioned data. test model specification for both long and wide data.
  3. next steps. more time with rast-hofer-2014 paper.

C. [portland-physical-cognitive](https://github.com/IALSA/Portland-physical-cognitive)   
  1. progress. Clarified the role of the domain map as the privary information display in the course of PCS (pre-conference survey). This map will be solidified as much as possible during the PCS. see [log](https://github.com/IALSA/ialsa-2015-portland-stencil/issues/21) for details. 


VIHA    

A. [viha-de-id](https://github.com/IHACRU/viha-de-id)    

B. [viha-programs](https://github.com/IHACRU/VIHA-programs)    

C. [viha-3t-mhsu](https://github.com/IHACRU/viha-3t-mhsu)    
