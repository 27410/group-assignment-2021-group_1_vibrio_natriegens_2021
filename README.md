[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/group-assignment-2021-group_1_vibrio_natriegens_2021/main)

# 27410 - Group assignment - Group 1 - GSM reconstruction for *Vibrio Natrigens* producing Violacein

> For this to work you will also have to keep `requirements.txt` up to date (by running `pip freeze > requirements.txt`).
> Furthermore, this will only work if you decide to make your repository public (which you can do under Settings -> Options),
> which I would encourage you to do – up to you. A lot of good science happens out in the open these days.
> Good luck!

## Project summary (<300 words)
The aim of this project is to build a genome-scale model (GSM) of *Vibrio natriegens*, applying and validating manually devised cell factory engineering strategies. The heterologous production of Violacein from *Chromobacterium violaceum* is added to the GSM of *V. natriegens*, leveling its flux with Deoxyviolacein.  The model is used to assess the growth rate and Violacein production rate on different media and different carbon sources, as well as knocking out some genes. Some of the outcomes summarised on phenotypic phase planes. Heterologous pathways to Violacein have been studied but no results have been found.


>ADJUST THIS TEXT. MAYBE SOMETHING MISSING? SOMETHING WE WANT TO EMPHASISE?

## Project overview
The outline and steps followed to apply strain engineering strategies to a GSM can be found in *Report.ipynb* file. 
On this repository one will find a folder called Models with the different GSMs: *model_VN_LB_vio-fad.xml* (Vibrio Natrigens in LB media with violacein pathway included using FAD), *model_VN_LB_vio-o2.xml* (Vibrio Natrigens in LB media with violacein pathway included using O2), *model_VN_LB.xml* (Vibrio Natrigens in LB media without violacein pathway), *model_VN_M9_vio-fad.xml* (Vibrio Natrigens in M9 media with violacein pathway included using FAD), *model_VN_M9_vio-o2.xml* (Vibrio Natrigens in M9 media with violacein pathway included using O2), *model_VN_M9.xml* (Vibrio Natrigens in M9 media without violacein pathway).
The models mentioned before which do not include violacein, are created in *Creation_models.ipynb*, file found on the principal directory. The models including violacein are created in *violacein_added_to_VN-LB.ipynb* and *violacein_added_to_VN-M9.ipynb*, where the different reactions and metabolites of violacein pathway are included and adjusted, to be later saved in files. 
All files starting by *Side_reactions...* check that side reaction metabolites are properly balanced. 
Different substrates have been examined during this project under the file called *Substrates_study.ipynb*.
The phenotypic phase plane plots can be found in *Phenotypic_phase_planes_plotting.ipynb*.

>HAS TO BE REVIEWED! WHY H2O2 FILES AND SIDE REACTIONS FILES? ONLY 1-2 FILES, THE GENE KNOCKOUT MISSING, THE HETEROLOGOUS PATHWAYS MISSING
