# TopologyProject
Compute and analyze topological features of a real-world dataset
 To run this code and reproduce results
 
 1.) create TDA envrionment with conda env create -f tda.yml
 
 2.) if on the william and mary bg lab machine, use source /opt/anaconda/bin/activate
 
 3.) activate with conda activate tda
 
 4.) pip install matplotlib, gudhi, scipy, and sci-kit learn
 
 5.) DataEngineering.py can be used to create embedding data from download_urls.json. That data is saved to /scratch/mwojdak/data/ and should already be present on the bg13 machine.

 Needed Files:
 - download_url.json, tda.yml, and unixcoder.py for utility
 - DataEngineering.py for code fragment embedding extraction
 - AnalyticalEngineering.ipynb for EDA and topological feature analysis

In this Repo, results from topological feature analysis are all stored in figs folder. However, exploratory data analysis results are located in AnalyticalEngineering.ipynb notebook as well as the topological feature analysis results for the class level.

Results seen in figs come from code functionally identical to AnalyticalEngineering.ipynb notebook, but are Cynthia Xiong and Michael Wojdak's work. Their githubs are attached.

https://github.com/CynthiaTheGriffin/topology_project/blob/main/AnalyticalEngineering2.ipynb

https://github.com/Michael-Wojdak/tda_project/tree/main/figures

Ohter Contributors include Cooper Ferguson and Zherui Zhang

