[edit me](https://github.com/andkov/about/edit/master/2016/mar/2016-03-14-weekly-update.md)

Progress report

TECH SUPPORT 

A. [ialsa-2015-portland](https://github.com/IALSA/IALSA-2015-Portland)   
- .next steps. more time on the design of the dynamic table for model look up. [issue](https://github.com/IALSA/IALSA-2015-Portland/issues/117) the basics are sketched, but in current form its use is not practical. 

B. [ialsa-2015-portland-stencil](https://github.com/IALSA/ialsa-2015-portland-stencil)  
- 1. progress.  met with W.Beasly and M.Shahid to advance the scribe/parser. [log](https://github.com/IALSA/ialsa-2015-portland-stencil/issues/30). We focused on the parser for the wave-inclusion (see [example](https://github.com/IALSA/wave-inclusion/tree/master/sandbox/01-univariate-linear)). Next meeting is scheduled for 2016-03-15-12:30 Pacific.  
- 2. progress. Working scripts were develop to generate Mplus script and extract estimated results for a [univariate case](https://github.com/IALSA/wave-inclusion/tree/master/sandbox/01-univariate-linear). However, during our meeting, it was decided to abandon this path. We don't really need to involve MPlus in model estimation. However, the considerable progress made in these scripts will be transfered to the stencil production. 
- next steps. verify the domain map (over which we met briefly with A.Piccinin on 2016-03-09) , so that the `.csv` could be sent out for people (Phillipe, Scott) to comment on and agree on the same structure.   
- next step. start testing REDCap survey.     

C. [ialsa-study-curator](https://github.com/IALSA/ialsa-study-curator)   
- .blocks. MAP.  We don't have a record of how the data is obtained from the source. Such description should be added to the README. I created a separate [issue ](https://github.com/IALSA/MAP/issues/18) to track the discussion. 
-  1. progress. OBAS.  Met with R.Vendittelli [log](https://github.com/IALSA/OBAS/issues/4), together we worked on systematized the description of the OBAS files ([contents.md](https://github.com/IALSA/OBAS/blob/master/data-unshared/contents.md)) and learning relevant R syntax to advance in data preparation.  The next meeting is scheduled for 2016-03-14-10:00.    
-  2. progress. LASA. Met with R.Graham. [log](https://github.com/IALSA/LASA/issues/6). We worked through importing the raw data ([see script](https://github.com/IALSA/LASA/blob/master/scripts/users/r-graham/0-import-raw-graham.R)), now we are ready to start assembling the analysis ready dataset (using this [script](https://github.com/IALSA/LASA/blob/master/scripts/users/r-graham/1-compose-dataframes-graham.R) ). R.Graham will contact me when she is ready for another session.  



SCIENCE   
 
A. [ialsa-car-methods](https://github.com/IALSA/ialsa-car-methods)    
  
B. [wave-inclusion](https://github.com/IALSA/wave-inclusion)  
 - 1. progress.  met with G.Muniz, A.Robittaille, and C.Brown for the update on the wave-inclusion project. [log](https://github.com/IALSA/wave-inclusion/issues/16).  We realized during the meeting that if we keep it to the univariate case, we can obviate the need for R-to-Mplus-to-R translation, which is responsible for a sizeable chunk of project's complexity. It was originally planned that I will adapt scripts from ialsa-2015-portland to fit the needs of this project, but if Mplus is eliminated for our analytic ecosystem that makes things much easier.  
 - next steps. We decided that we should start with demonstrating the issue of wave inclusion for the **univariate** case first, using only R to keep things in the same ecosystem. This will allow us to focus on the models and graphs themselves. Once a univariate case is demonstrated we can start thinking whether expansion to MPlus would be justified further advance the project, which does not have to end after the first publication. next meeting is scheduled for 2016-03-23-09:30 Pacific. 
 
C. [portland-physical-cognitive](https://github.com/IALSA/Portland-physical-cognitive)   

VIHA    

A. [viha-de-id](https://github.com/IHACRU/viha-de-id)    

B. [viha-programs](https://github.com/IHACRU/VIHA-programs)    

C. [viha-3t-mhsu](https://github.com/IHACRU/viha-3t-mhsu)    
