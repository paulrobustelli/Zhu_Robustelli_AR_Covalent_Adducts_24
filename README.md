# Zhu_et_al_Covalent_2024
Code Accompanying "Covalent adducts formed by the androgen receptor transactivation domain and small molecule drugs remain disordered" by Zhu and Robustelli

Trajectories For This Manuscript Can Be Downloaded Here:
(./trajectory)

1.Download the covalent_env.yml file and activate the environment by "conda env create -f covalent_env.yml"

2.Download the trajectory from the attached link, put them in the a folder called 'trajectory', and all the scripts are available to run from there. Folders will be created for result figures from analysis.

Files:
cluster_function.py is for all the functions needed to perform t-SNE and K-means clustering.
cluster_com_E2E7.ipynb is for clustering the combined trajectory of non-covalent trajectory $Tau-5_{R2\_R3}$ in the presence of EPI-002 and EPI-7170 with 4 clusters.
cluster_com_E2E7_C20.ipynb is for clustering the combined trajectory of non-covalent trajectory Tau-5$_{R2_R3}$ in the presence of EPI-002 and EPI-7170 with 18 clusters.
cluster_com_CYECYE7.ipynb is for clustering the combined trajectory of Tau-5$_{R2_R3}$ CYS404:EPI-002 and Tau-5$_{R2_R3}$ CYS404:EPI-7170
