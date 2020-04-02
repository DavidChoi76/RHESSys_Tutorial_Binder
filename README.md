# RHESsys Model Simulation in Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DavidChoi76/Binder_test.git/master)
[![Documentation Status](https://readthedocs.org/projects/mybinder/badge/?version=latest)](https://mybinder.readthedocs.io/en/latest/?badge=latest)
[![Join the chat at https://gitter.im/jupyterhub/binder](https://badges.gitter.im/jupyterhub/binder.svg)](https://gitter.im/jupyterhub/binder?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This GitHub repository developed to simulate RHESsys Model as an example of Coweeta subwatershed 18, NC, USA.

Try out RHESsys Model Simulation with a brief interactive tutorial by clicking the Launch Binder button above. It will launch a "Binder" application using the code in this repository.

When JupyterHub starts, you can find "rhessys_example_download.ipynb".
1) Open "rhessys_example_download.ipynb" notebook and execute codes.
 - Get notebooks, source code etc from HydroShare resource :https://www.hydroshare.org/resource/f974fcd6f7c9404fba1c63fd7857ce18/
2) Open 1_Preprocessing_to_Create_RHESsys_Model_Input_using_GRASS_GIS_and_R-script_on_Collaborative_Modeling_Framework.ipynb notebook
 - The notebook include
   1. Create Project Directory and Download Raw GIS Data from HydroShare
   2. Set GRASS Database and GISBASE Environment
   3. Preprocessing GIS Data for RHESsys Model using GRASS GIS and R script
   4. Preprocess Time series data for RHESsys Model
   5. Construct worldfile and flowtable to RHESSys

3) Open 2_RHESsys_Model_Simulation_on_Collaborative_Modeling_Framework.ipynb notebook
   1. Download and compile RHESsys Execution file
   2. Simulate RHESsys model
   3. Plotting RHESsys output
   
