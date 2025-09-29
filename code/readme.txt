This folder contains all materials to reproduce the analyses of the Chapter
"How Networks Facilitate Trust: A Synthesis on Control Effects" in the "Handbook
of Trust and Social Networks". The following material is included in this 
repository:
- /data: contains all data used in the final analyses in the handbook chapter
- /analysis_scripts: contains all R code to reproduce the analyses on the single
                     study data
- /data_cleaning_scripts: contains all R code that was used to clean the raw
                          data files. Because we do not have the rights to share
                          the raw data files, these files cannot actually be ran,
                          but we share the code to be as transparent as possible.
- /results: contains the output of the analyses included in '/analysis_scripts'
- results.qmd: contains the code to run AND aggregate the single-study results 
               and renders all results tables reported in the main text and 
               supplementary materials. Also the simulation study is executed 
	       in this file. The results.qmd can be considered the main 
               analysis file, and compiling it will render all results.
- results.docx: output of results.qmd

In case of questions and/or comments, please reach out to t.b.volker@uu.nl
