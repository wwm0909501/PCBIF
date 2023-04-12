# PCBIF
Printed Circuit Board Ion Funnel 
Genetic Algorithm Optimized Printed Circuit Board Ion Funnel tandem Subambient Pressure Ionization with Nanoelectropray (SPIN) for High Sensitivity Mass Spectrometry

1. Confirm you had installed the SIMION 8.2 or above;

2. First step, loaded the .iob file;

3. Refine

4. OK, just fly the ion, then the software will refine and optimize CPs (characteristic parameters in ion funnel) automatically, and the final result would be presented in the log window in the SIMION




Caution:  
        1. four CP are tuned in the program including the exit electrode radius r (mm), electrode spacing d (mm), RF amplitude (V), DC gradient (V/mm)
        2. the final optimal CPs cannot obtain once a time. fortunately, SIMION supports multiple processes, 10 GA processes can be completed in parallel within 4 hours.
        3. Detail principle and operation will be introduced in a article soon

        4. Lua language is used, and programmed to control the simulation process. 

        5. During Fly'm, an additional "fast scalable" electrode solution array file (pa+) was used to tune the electrical parameters and an API was used to tune the dimensional parameters

 
Thanks

                                                                       --Ningbo University  Weimin Wang, Chaohui Qiu, Fuxing Xu*, Li Ding, Chuan-Fan Ding*
