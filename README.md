Data for the paper: Wizard-of-Oz++: A Path to Autonomy
===============================================================================

Preprocessed data and analyser file for the paper.
Contains all the requirement to regenerate each graph in the paper.

These preprocessed data were obtained using direct logging from
the rosbag file accumulated in the study. However, the bags are not
provided for privacy reason.

Structure
---------

- Main file: script.ipynb
- Data file 1: sup_event.csv (game events in the supervised condition)
- Data file 2: aut_event.csv (game events in the autonomous condition)
- Figs folder: where figures are generated

How to use:
----------

Run ``jupyter notebook`` in the folder and then execute cells one by one.
To save graphs, set: ``saving = True`` and run all the cells.
