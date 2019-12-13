# Data-assimilation-schemes
Sample application of different DA schemes

The Notebook (DA_smoothers_sample_application) demonstrates a sample application of four ensemble smoother data assimilation (DA) schemes for assimilating MODIS fractional snow cover area (fSCA) into a hydrological model. Here the main goal is to get an improved estimate of snow water equivalent (SWE) during the maximum accumulation period. 

The DA schemes used are:
 1. Particle batch smoother (Pbs)
 2. LoA (adopted from GLUE LoA)
 3. Pbs_F (fuzzy logic based variant of Pbs)
 4. LoA_F (fuzzy logic based variant of LoA)

The last three DA schemes were newly introduced in the following paper and for details about the conceptual background and for further information about the implementation strategy of these DA schemes the reader is referred to this paper.

<a href="https://www.mdpi.com/2072-4292/11/1/28"><Teweldebrhan, A., Burkhart, J., Schuler, T., and Xu, C.-Y.: Improving the Informational Value of MODIS Fractional Snow Cover Area Using Fuzzy Logic Based Ensemble Smoother Data Assimilation Frameworks, Remote Sensing, 11, 28, 2019. </a>

Teweldebrhan, A., Burkhart, J., Schuler, T., and Xu, C.-Y.: Improving the Informational Value of MODIS 
Fractional Snow Cover Area Using Fuzzy Logic Based Ensemble Smoother Data Assimilation Frameworks, Remote 
Sensing, 11, 28, 2019. https://www.mdpi.com/2072-4292/11/1/28
