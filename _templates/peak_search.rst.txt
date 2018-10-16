Peak Search
======================================

Summary
--------------

Peak Search allows you to call peaks from a wig file and classify them. Initially peaks are only called on a single chromosome. From this the correct parameters and a model can be chosen in order to call peaks on the entire genome. The following steps are required:-

- **Parameter Sweep** Peaks are called on a supplied Wig file out using a number of different parameters. A bed file is created for each combination of parameters.
- **Initial Peak Calling** The initial peak calling can be analysed by looking at how changing different parameters effects the distribution of the peaks. From this, the appropriate parameters are chosen and images and stats are generated for all peaks generated with the chosen parameters
- **Tagging** From the peak images and stats, the peaks can be tagged (classified) by the user into different categories. These categories can then submitted to a machine learning step, which generates a model
- **Genome Wide Classification** The model and parameters generated from the initial steps are then used to call peaks on the entire genome

Parameter Sweep
-----------------


.. image:: img/peak_search/parameter_sweep.png
   :alt: alternate text
   :align: center

1. Type the name and description of the project into the inputs (1 and 2 above)
2. Enter the http address of the Wig file into the text box(3). It need to be publically accessible. Once you have pressed enter or lost focus, the path entered will be checked to see if it is indeed a wig file and the chromosomes displayed in the right hand drop down (4)
3. You can submit the job by pressing the appropriate button. An email will be sent once the initial peak calling has finished. You can also return the page to check the status
