[add entry](https://github.com/andkov/about/edit/master/2016/mar/README.md)

##### Week 86 in Victoria
Mar 24, Thursday
- held telecon for multi-state workshop with Iva Cukic and Johan Skoog. [log](https://github.com/IALSA/ialsa-2016-amsterdam/issues/6)

Mar 23, Wednesday 
- met with R.Vendittelli. [log](https://github.com/IALSA/OBAS/issues/6) 
- met with R.Graham. [log](https://github.com/IALSA/LASA/issues/7)

Mar 22, Tuesday
- met with W.Beasley. [log](https://github.com/IALSA/ialsa-2015-portland-stencil/issues/40). 

Mar 21, Monday
- spent the day developing the [collector script](https://github.com/IALSA/IALSA-2015-Portland/blob/master/scripts/mplus/collect-results.R) for Portland. Made some good progress. 

spend the weekend working on Portland, Amsterdam, and Groningen


##### Week 85 in Victoria

Mar 18, Friday
- met with S.Hofer about Harmonization and Multi-State studies.   

Mar 17, Thursday
- to busy to log  

Mar 16, Wednesday
- to busy to log  

Mar 15, Tuesday 
- met with W.Beasley to work on Portland stencil. [log](https://github.com/IALSA/ialsa-2015-portland-stencil/issues/38). Made major progress in script development. The scribe-parser suite is almost ready for testing. Needs a second fresh look after the break. 

Mar 14, Monday  
- 1. met with R.Vendittelli regarding OBAS data. [log](https://github.com/IALSA/OBAS/issues/5).  
- 2. initialized repository for the upcoming harmonization workshop [ialsa-2016-groningen](https://github.com/IALSA/ialsa-2016-groningen). Organized the materials from emails into a GitHub styled documentation. Created the basic import ([/manipulation/studies-ellis.R](https://github.com/IALSA/ialsa-2016-groningen/blob/master/manipulation/studies-ellis.R)). 
- 3. made major progress in setting up [ialsa-2016-groningen](https://github.com/IALSA/ialsa-2016-groningen). Created an [elis-island](https://github.com/IALSA/ialsa-2016-groningen/blob/master/manipulation/0-ellis-island.R) script that imports the data files and conducts early modifications.


##### Week 84 in Victoria

Mar 11, Friday  
- travelled to Vancouver to visit the Dutch Consulate. 
- attended dinner party at S.Hofer and A.Piccinin house hosting the APA Div 5 2016 meeting finale. Fun times.   

Mar 10, Thursday
- attended  Symposium on Psychological Methods (APA	Div. 5). Notable speakers: Joe Rodgers and William Revelle. Listen to the recording on the iphone.    
- was preparing the document for a Dutch visa the rest of the day  

Mar 9, Wednesday
- met with G.Muniz, A.Robittaille, and C.Brown for the update on the wave-inclusion project. [log](https://github.com/IALSA/wave-inclusion/issues/16). We realized during the meeting that if we keep it to the univariate case, we can obviate the need for R-to-Mplus-to-R translation, which is responsible for a sizeable chunk of project's complexity. We decided that we should start with demonstrating the issue of wave inclusion for the univariate case first, using only R to keep things in the same ecosystem. This will allow us to focus on the models and graphs themselves. Once a univariate case is demonstrated we can start thinking whether expansion to MPlus would be justified further advance the project, which does not have to end after the first publication. 
- met with C.Brown to work on HRS data grooming. [log](https://github.com/IALSA/HRS/issues/5)

Mar 8, Tuesday
- attended the COAG colloquium to hear [Patan Mehta](http://www.norc.uab.edu/people/tmehta) who spoke on ***From Health Promotion Studies to Population-level Obesity-Mortality Studies: Research Landscape of the Biostatistics***. ![patan mehta](http://www.norc.uab.edu/sites/norc.uab.edu/files/people/TMehta/TMehta.jpg)

Mar 7, Monday
-  1. progress. OBAS.  Met with R.Vendittelli [log](https://github.com/IALSA/OBAS/issues/4), together we worked on systematized the desdription of the OBAS files ([contents.md](https://github.com/IALSA/OBAS/blob/master/data-unshared/contents.md)) and learning relevant R syntax to advance in data preparation.  The next meeting is scheduled for 2016-03-14-10:00.    
-  2. progress. LASA. Met with R.Graham. [log](https://github.com/IALSA/LASA/issues/6). We worked through importing the raw data ([see script](https://github.com/IALSA/LASA/blob/master/scripts/users/r-graham/0-import-raw-graham.R)), now we are ready to start assembling the analysis ready dataset (using this [script](https://github.com/IALSA/LASA/blob/master/scripts/users/r-graham/1-compose-dataframes-graham.R) ). R.Graham will contact me when she is ready for another session.  




##### Week 83 in Victoria.

Mar 4, Friday
- met with K.Moselle, together we made some good progress at shaping the VIHA program census. [log](https://github.com/IHACRU/viha-programs/issues/20). Specifically, we arrived at the following form of assembling a "healthy" population of programs. We start with the proposition : `Facility_Key`, `Building_Key`, and `Site_Key` uniquely define a health program within VIHA.  All programs for which this is the case are automatically admitted in the pool of healthy programs. The rest of the programs are delt with systematically (like with PES) or manually.   

Mar 3, Thursday
- attended "REDCap day" event at VIHA. [notes](https://github.com/andkov/about/blob/master/2016/mar/2016-03-03-notes.md)

Mar 2, Wednesday
- S.Hofer invited me to the workshop on multistate modeling at Amsterdam in April 14-16, 2016.  
- reorganized the Portland repository [#118]() and modernized the extraction flow [#119]()   
- met with W.Beasley [log](https://github.com/IALSA/IALSA-2015-Portland/issues/120) to work on the Portland parser. 

Mar 1, Tuesday
- 1. worked on modernizing the reproduction of Portland [log](https://github.com/IALSA/IALSA-2015-Portland/issues/119)
- 2. attended a talk by Iris Gordon who applied for a senior instructor for quant psychology at UVic. 

Feb 29, Monday. 
- 1. met with R.Vendittelli regading OBAS curatorship. [log](https://github.com/IALSA/OBAS/issues/2)  
- 2. met with W.Beasley regarding Portland stencil. [log](https://github.com/IALSA/ialsa-2015-portland-stencil/issues/28). Need to focus on the parser more, so we can move on. Agreed to meet Wednesday, March 2, at 14:00 Pacific Time.  
- 3. worked on cleaning the main Portland repository. Restructured file architecture a bit, renamed, deleted obsolete. [log](https://github.com/IALSA/IALSA-2015-Portland)
