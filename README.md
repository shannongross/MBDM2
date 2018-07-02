# Gelderland Decision Support on River IJssel Flood Management
Aashna Mittal			4739736 <br>
Merih Koray Karabulut		4754859 <br>
Mikhail Sirenko			4737881 <br>
Shannon M. Gross 		4735048 <br>
Shajeeshan Lingeswaran		4748883 <br>


__Main_Files and Instructions__:
 - problem_formulation_new_version.py : Contains a new 8-problem formulation
 - dike_model_open_exploration.ipynb : I step - perform Open Exploration
 - dike_model_sensitivity_analysis.ipynb : II step - perform Global and Local Sensitivity Analysis
 - dike_model_open_scenario_discrovery.ipynb: III step - perofrm Scenario Discovery
 - dike_model_directed_search_worst_case.ipynb : IV step - search for the worst case scenario and the finding optimal policies using Multi-objective Robust Optimization 
  - Comparing_Final_Policies.ipynb : Contains summary visualizations of final outcomes for policymakers 

To run the steps from I up to IV you can just open these files and run all lines one by one. All necessary results are saved for this purposes. There is a possibility to switch from 3 obj PF to 8 obj PF. To do this uncomment the lines of code related to it.

The secondary MORO analysis was done in parallel to enrich the finding in the MORDM and the poltical discussion.

- dike_model_directed_search_MORO_5_8Obj_gelcost.ipynb: step V.1 - find optimal policies using MORDM in favor of Gelderland (optimization over of 5 of 8 outcomes: Gelderland Investment Costs, Annual Damages in Gelderland and Overijssel, Expected Number of Deaths)
 - dike_model_directed_search_MORO_5_8obj_rfrcost_nfe500.ipynb: step V.2 - find optimal policies using MORDM without using RfR costs (optimization over of 5 of 8 outcomes: Gelderland Investment Costs, Annual Damages in Gelderland and Overijssel, Expected Number of Deaths)
 - Comparison of results for 3 objectives.ipynb: VI.1 - comparison of MORDM and MORO outcomes for 3 objectives 
 - Comparison of results for 8 objectives.ipynb: VI.2 - comparison of MORDM and MORO outcomes for 8 objectives

__Outcomes__:
 - The outcomes are aggregated using a new 8-problem formulation to reflect the interest of the client (Gelderland province) and its allies

__Locations__:
 - Gelderland (Upstream)
    - (A1) Doesburg -most upstream location
    - (A2) Cortenoever
 - Gelderland (Downstream)
   - (A3) Zutphen
   - (A4) Gorsset
 - Overijssel
   - (A5) Deventer -most downstream location

__Contributions__:
The code, model, and ema_workbench module are the work of Jan Kwakkel. See his GitHub repositories at https://github.com/quaquel/epa1361_open and https://github.com/quaquel/EMAworkbench for full documentation. 


