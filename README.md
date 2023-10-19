# :mortar_board: MSc_PGTKEP_GroupRepo

This repository consists of the contents for my PGTKEP project. 

Below description illustrates in details. 

:file_folder: Data files

* restEnzyme.json
  > Dataset of all restriction enzymes selected by Linear Diagnostics Limited

:bookmark_tabs: Experiments
  
The `PGTKEP_LDpipeline_SequenceChoice.ipynb` is the key file to identify the template sequence(s) and trigger sequence(s) to be used in development. And the `PGTKEP_LDpipeline_SampleProcessing.ipynb` is the file containing the following steps for optimizing assay through the identified sequence(s). To run both files, you need to prepare Python environment as below:
* Create a python virtual environment named .venv  `python -m venv .venv`
  
* Activate your python virtual environment 

  Mac/Linux `source .venv/bin/activate`
    
  Windows `.venv/Scripts/activate.bat`


**Due to security reason**,the computational pipeline for  the development of a Point-of-Care (PoC) testing procedure for sexually transmitted infections (STIs) at Linear Diagnostics Limited is private. Please contact me or Jean-Louis Duprey (Head of R&D at Linear Diagnostics) for the further questions. :speech_balloon:
