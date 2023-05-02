# SEIRD-model-based-Covid-19-simulation
## There are two ipynb files.
* CPT_591_ABM_SEIRD_with_RIDGE_PREDICTION_VER2.ipynb.

    import st_99 to draw US map and mark abbreviated state name
    import Covid-19 epidmic data of all US states including confirmed_cases.csv, recovered_cases.csv, and death_cases.csv
    import population data, pop_age_prop_ver2.csv
    Implement epidmic simulator
* CPT_S-591-Graph.ipynb

    Preprocess the air flight information, 336781026_T_T100D_SEGMENT_US_CARRIER_ONLY.
    Store it in flight_inf_adjacency_matrix.npy file
    Build a graph network and show important nodes
    
To use these codes, please unzip 336781026_T_T100D_SEGMENT_US_CARRIER_ONLY.
Download all file in your local machine or google dirve.
Change the file path to match your location of the downloaded files.
Run CPT_S-591-Graph.ipynb first to crate a new flight_inf_adjacency_matrix.npy and a new graph network
Or skip running CPT_S-591-Graph.ipynb 
Don't care create a new graph network by yourself
and you can use my flight_inf_adjacency_matrix.npy to directly run CPT_591_ABM_SEIRD_with_RIDGE_PREDICTION_VER2.ipynb
