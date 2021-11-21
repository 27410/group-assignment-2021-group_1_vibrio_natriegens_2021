[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/group-assignment-2021-group_1_vibrio_natriegens_2021/main)

# 27410 - Group assignment - Group 1 - GSM reconstruction for *Vibrio Natrigens* producing Violacein

> Keep `requirements.txt` up to date -> pip freeze > requirements.txt

## Project summary
The aim of this project is to build a genome-scale model (GSM) of *Vibrio natriegens*, applying and validating manually devised cell factory engineering strategies. The heterologous production of Violacein from *Chromobacterium violaceum* is added to the GSM of *V. natriegens*, leveling its flux with Deoxyviolacein. All four models have been run with Memote to assess its quality, showing improvement when Violacein is added. The model is used to assess the growth rate and Violacein production rate on different media and different carbon sources, as well as applying some knocking out strategies. The outcomes are summarised on phenotypic phase planes. Heterologous pathways to Violacein have been studied but no results have been found.

## Project overview
The outline and steps followed to apply strain engineering strategies to a GSM can be found in *Report.ipynb* file. 
On this repository one will find a folder called *Models* with the different GSMs: *model_VN_LB_vio-fad.xml* (Vibrio Natrigens in LB media with violacein pathway), *model_VN_LB.xml* (Vibrio Natrigens in LB media without violacein pathway), *model_VN_M9_vio-fad.xml* (Vibrio Natrigens in M9 media with violacein pathway included), and *model_VN_M9.xml* (Vibrio Natrigens in M9 media without violacein pathway).
The models mentioned before which do not include violacein, are created in *Creation_models.ipynb*, file found on the principal directory. And validated later with memote (the corresponding files can be found on *Memote* folder). The models including violacein are created in *violacein_added_to_VN-LB.ipynb* and *violacein_added_to_VN-M9.ipynb*, where the different reactions and metabolites of violacein pathway are included and adjusted, to be later saved in files. 
In the file *Side_reactions_and_searching.ipynb* we ensure that side reaction metabolites are properly balanced. 
Different substrates have been examined during this project under the file called *Substrates_study.ipynb*, where growth rate, production rate and yields are assessed. Furthermore, some plots supplement it.
The phenotypic phase plane plots can be found in *Phenotypic_phase_planes_plotting.ipynb*, where Violacein, Oxygen, Growth and Glucose are studied.
Finally, in *Optimizations_and_Knockouts.ipynb* we have tried some gene knockout strategies, plus in *Heterologous_pathways.ipynb* we did search for alternative pathways. However, no way to improve this pathway has been found. 

