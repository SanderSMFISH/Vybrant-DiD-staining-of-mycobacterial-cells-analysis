Analysis Hypoxia resyurcitation Experiment

to install python libraries use anaconda and requirements.yml file located in the notebooks folder.

TO install type in anaconda prompt type:
>cd '/path/to/dataframes folder'
>conda env create -f requirements.yml

Notebooks include script for segmentation, data extraction and plotting. We have already performed the full analysis, so these notebooks are only to indicate 'how' the analysis was performed. For acces to the extracted Dataframes used for plotting see the Data folder. 

Segmented 2D single-colony masks for the bacteria were created. Several timepoints were included in this resurcitation experiment = range(0,145, 15 mins).

Time until first division where manually annotated using the Napari-point layer. These manual annotation can be found in the folder Annotation_First_Division_points. The number of cells that did not divide within our experimental time frame range were also counted.

In order to redo the analysis, go through the notebooks in the Notebooks folder.

In the Figures folder you can find the figures produced in these notebooks. Some of the figures were used as well for publication. 

In the Results folder you find the raw experimental data used for the analysis.

In the main folder, there is also a powerpoint indicating the most important findings of this analysis.

The data for the analysis can be found on:
https://zenodo.org/records/10581851
