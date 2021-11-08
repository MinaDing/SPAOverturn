# SPAOverturn

This repository includes source data for the Figures and Extended Data Figures of our submitted manuscript. These data are generated by iSALE-3D and CitcomS softwares. 
The format of all data files are: longitude, latitude, value. 

Content of this repository: 
1. Fig1c_TiO2.txt, Fig1d_Th.txt: Modeled TiO2 and Th content of our reference model (Fig. 1).
2. Fig2_I420_deg60_v-2D50a(a-h): Source data for Fig. 2 (i.e., our reference case). It is 3D ASCII data compressed by software 7-zip and split into eight pieces to satisfy the size limit of github repository. The files can be resembled using cat command.
3. Fig3a.txt, Fig3b.txt: Source data for the compositional evolution of our reference model in Fig. 3a, and source data for the IBC shape in Fig. 3b.
4. ExtDataFig1a_mantle_uplift_I420_deg60.txt, ExtDataFig1b_mantle_uplift_I315_deg60.txt, ExtDataFig1c_mantle_uplift_I420_deg45.txt, ExtDataFig1d_mantle_uplift_I420_deg30.txt: Modeled tracer points with mantle uplift from iSALE-3D models in Extended Data Fig. 1. Locations of these points (currently centered at 52ºS, 180ºE) should be shifted and rotated to be consistent with the location of SPA. This can be conducted using MatLab commands distance & reckon. 
5. ExtDataFig2b_I315_deg60_v-2a(a-d), ExtDataFig2c_I420_deg45_v-2a(a-d), ExtDataFig2d_I420_deg30_v-2a(a-d), ExtDataFig2e_I420_deg60_v-3a(a-c), ExtDataFig2f_I420_deg60_v-1a(a-d), ExtDataFig2g_I420_deg60_v-2_NoImpacta(a-d), ExtDataFig2h_I420_deg60_v-2_NoDensitya(a-c): Source data for plotting Extended Data Fig. 2b-h. The data source for Extended Data Fig. 2a is the same with that for Fig. 2. It is 3D ASCII data compressed by software 7-zip, which is then split into 3-4 files to satisfy the size limit of github repository. 
6. ExtDataFig3a_I420_deg60_v-2.txt, ExtDataFig3b_I315_deg60_v-2.txt, ExtDataFig3c_I420_deg45_v-2.txt, ExtDataFig3d_I420_deg30_v-2.txt, ExtDataFig3e_420_deg60_v-3.txt, ExtDataFig3f_I420_deg60_v-1.txt, ExtDataFig3g_v-2.txt, ExtDataFig3h_noDensity.txt: Modeled IBC distribution from CitcomS shown in Extended Data Fig. 3. 
7. ExtDataFig4a_ObsTiO2_degree1.txt, ExtDataFig4b_ModelTiO2_degree1.txt: Degree-1 components of observed and modeled TiO2 content (Extended Data Fig. 1). 

Labeling scheme for our models: For example, I420_deg60v-2 has an impactor size of 420 km, an impact angle of 60 deg, IC viscosity contrast of 10^(-2) with respect to the surrounding mantle. 

