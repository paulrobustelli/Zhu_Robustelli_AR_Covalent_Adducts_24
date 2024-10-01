# Zhu_et_al_Covalent_2024
Code Accompanying "Covalent adducts formed by the androgen receptor transactivation domain and small molecule drugs remain disordered" by Zhu and Robustelli

Trajectories For This Manuscript Can Be Downloaded Here:
(./trajectory)

1.Download the covalent_env.yml file and activate the environment by "conda env create -f covalent_env.yml"

2.Download the trajectory from the attached link, put them in the a folder called 'trajectory', and all the scripts are available to run from there. Folders will be created for result figures from analysis.

Files:
cluster_function.py is for all the functions needed to perform t-SNE and K-means clustering.

cluster_com_E2E7.ipynb is for clustering the combined trajectory of non-covalent trajectory $Tau-5_{R2-R3}$ in the presence of EPI-002 and EPI-7170 with 4 clusters.

cluster_com_E2E7_C20.ipynb is for clustering the combined trajectory of non-covalent trajectory $Tau-5_{R2-R3}$ in the presence of EPI-002 and EPI-7170 with 18 clusters.

cluster_com_CYECYE7.ipynb is for clustering the combined trajectory of $Tau-5_{R2-R3}$ CYS404:EPI-002 and $Tau-5_{R2-R3}$ CYS404:EPI-7170 with 4 clusters.

cluster_com_E2E7_C20.ipynb is for clustering the combined trajectory of $Tau-5_{R2-R3}$ CYS404:EPI-002 and $Tau-5_{R2-R3}$ CYS404:EPI-7170 with 20 clusters.

Zhu_AR_Ligands_Tau5R2R3_CYE_4.26.23.ipynb is for the analysis of Replica Exchange with Solute Tempering simulation of $Tau-5_{R2-R3}$ CYS404:EPI-002.

Zhu_AR_Ligands_Tau5R2R3_CYE7_4.26.23.ipynb is for the analysis of Replica Exchange with Solute Tempering simulation of $Tau-5_{R2-R3}$ CYS404:EPI-7170.

Zhu_AR_Ligands_Compare_Ensembles_covalent_all.ipynb is for comparing the simulation results of apo $Tau-5_{R2-R3}$, non-covalent trajectory $Tau-5_{R2-R3}$ in the presence of EPI-002 and EPI-7170, $Tau-5_{R2-R3}$ CYS404:EPI-002 and $Tau-5_{R2-R3}$ CYS404:EPI-7170.
