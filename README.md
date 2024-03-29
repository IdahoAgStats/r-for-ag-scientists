
### Repo for Introduction to R for Ag Scientists


https://idahoagstats.github.io/r-for-ag-scientists/


#### Course progression:

* Main goal: teach lessons 1-13
* If time is running out, skip lesson 14, do lesson 15, then decide if there is time to cover 14 or lesson 16. Poll the class to see what they want. 
* Lessons 3, 6 and 12 are special lessons that are lecture-based (no live coding) and to impart larger lessons on R programming (RStudio, R functions & documentation, reproducible research)
* in lessons 01 & 02, use the console 
* introduce and use .R files for lessons 14 & 15
* Introduce .qmd files in lesson 03 and use that for the remainder of the class (except the plotting lessons)
* regarding teaching quarto: 
  - first start with the example file provided for lessons 04 & 05
  - for lesson 07, have them make a new quarto file. Mention the visual editor and yaml header
  
* Starting at lesson 13, switch to using R on people's systems (rather than Posit cloud)
  * step 1: make an R project - in a dedicated directory


#### Using Posit Cloud

* A posit classroom is set up with only one project. At the time of writing this, we will use that project for the entire class.
* The R session should be restarted at the end of each lesson / beginning of the following lesson to wipe objects, packages loaded, etc

* All tidyverse packages were installed to the project prior to sharing it.

* currently, invitations can only be sent one-at-a-time. The workaround is to share an open link, then later change the access setting to "invitation only"

* In the initial set-up, the project contains these directories and files:

  * data      
    * field_trial_2009.xlsx   
    * genotypic_data.txt      
    * genotypic_data_rotated.txt      
    * trial_data.csv      
    * trial_metadata.csv      
    * weather_data.csv      
  * outputs   
    * plots     
  * scripts     
    * example_quarto_file.qmd     
  * project.Rproj      

* Every student should make a permanent copy of this project. Over time, we will create more files and save them to this project.

* students need to encouraged to visit my posit R project as often as they wish and to use Posit cloud outside of class time. 


#### Other notes:

* This is intended to be delivered as a live coded class
* There are special lessons that are largely lecture and hence exceptions to the live-coded format: 
  * RStudio (lesson 3)
  * R functions & R help (lesson 6)
  * R for reproducible research (Lesson 13)
  
Perhaps considering have a class long project to motivate people more. 


