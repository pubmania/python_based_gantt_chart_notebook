# python_based_gantt_chart_notebook
The Jupyter notebook and associated sample can be used for creating gantt charts simply by updating the sample csv file.

# Usage

* Download the `Gantt Script.ipynb` file and `Sample.csv` in same directory.
* Run it on the local JupyterLab instance.
* If the outputs are generated, you are all set. If not install any missing dependencies.
* Once it all runs fine, make changes in Sample.csv and run the notebook again.
  * If you create a copy of `Sample.csv` and want to use that, just make sure that in second cell you change the assignment for variable `project_plan` to the new file name.

Once run, the notebook will create 3 `svg` files with static gantt using matplotlib and 1 `html` file for interactive gantt using plotly. Samples are in this repo.

## Sample Rollout
![Sample Rollout.svg](https://github.com/pubmania/python_based_gantt_chart_notebook/blob/main/Sample%20Rollout.svg)

## Sample Rollout Part 1
![Sample Rollout Part 1](https://github.com/pubmania/python_based_gantt_chart_notebook/blob/main/Sample%20Rollout%20Part%201.svg)

## Sample Rollout Part 2
![Sample Rollout Part 2](https://github.com/pubmania/python_based_gantt_chart_notebook/blob/main/Sample%20Rollout%20Part%202.svg)

To change the `threshold` for Part 1 and Part 2 of the gantt charts above, you will need to change threshold in Cell 8, as shown below:

![image](https://github.com/pubmania/python_based_gantt_chart_notebook/assets/1966557/3845f785-2937-466f-bc9d-0e3bc48ad821)

Finally, the html file is interactive and will show the gantt like shown below:

![image](https://github.com/pubmania/python_based_gantt_chart_notebook/assets/1966557/e142333c-cba6-4c28-8667-8fddf0531242)
