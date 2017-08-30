# DSX Local demo: Predicting Driver Type

**This repository contains the following assets for the DSX Local demo**
1. Presentation - replace *Use Case* slides from this repo in [this presentation](https://github.com/elenalowery/DSXLocal_TelcoChurn/tree/master/Presentation)
2. Notebook
3. Data
4. Shiny app

**Demo setup**
1. Create a DSX project
2. Import data and notebook
3. Add project token
4. Open **RStudio** and import *Shiny.zip*
   * Select Upload menu in the file explorer in the right corner <br>
   ![ImportShiny](images/ImportShiny.JPG?raw=true)
   * When loaded, you should see the following files <br>
   ![LoadedShiny](images/LoadedShiny.JPG?raw=true)
   * In the R console, run the following commands to load required libraries: 
    install.packages("DT")
    install.packages("randomForest") <br>
    ![InstallDT](images/InstallDT.JPG?raw=true)
    ![InstallRandomForest](images/InstallRandomForest.JPG?raw=true)
   * Click on *serverR* in the file explorer. After the application is loaded, click the *Run App* button. <br>
   ![ServerR_loaded](images/ServerR_loaded.JPG?raw=true)
   * If prompted, install the latest packages 
   * Select *Allow popups* to bring up the application
   * Test the application - both the Explore and Model tabs <br>
   ![App](images/App.JPG?raw=true)
   
**Demo**
1. Follow the agenda in this presentation
2. During the demo show capabilities of DSX in the context of Data Science for Automotive use case. 
   * Start with the overview of the use case
   * Log in to DSX Local and create a new project
   * Show collaboration features for the project
   * Load data and explain what type of data sources are supported
   * Create a notebook from File
   * Walk through the notebook
   * Explain the deployment process - via UI and API
3. Wrap up with architecture discussion 
