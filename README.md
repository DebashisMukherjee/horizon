# horizon
The repository "https://github.com/DebashisMukherjee/horizon"
includes code for proof-of-concept validation for an work submitted to a journal.


horizonpoint.ipynb: It is the main source file for the reported work title "Reducing Two-Dimensional Data for Speeding up Convex Hull Computation", that is to be submitted for review.

01.BugattiAtlantic.csv, 02.Formica.csv, 03.Flight.csv, 04.T-800-Head.csv, 05.Al.csv, dgen1.csv, dgen2.csv: These are the individual dataset each of which are used for validation of the algorithm reported in the submission.

jarvis.ipynb: An opensource reference implementation of the "Jarvis GiftWrap" algorithm, found in the github repository "https://github.com/RodolfoFerro/ConvexHull"

quickhull.ipynb: An opensource reference implementation of the "QuickHull" algorithm, found in the github repository "https://github.com/theremintourette/quickhull"

  
The files, horizonpoint.ipynb, jarvis.ipynb, quickhull.ipynb, could be run, with the given dataset, by giving link to the path to the input dataset files (i.e.,01.BugattiAtlantic.csv, 02.Formica.csv, 03.Flight.csv, 04.T-800-Head.csv, 05.Al.csv, dgen1.csv, dgen2.csv), hardcode in a single line in the code.

A relative comparison in the time taken by the "horizon" scan, with reference to equivalent of the opensource of the "jarvis", and "quickhull" implementation could be evaluated.

The implementation, used "Anaconda" with Python 3.8 installation. The .ipynb files could be run from Jupyter Notebook.

Steps for validation:
1) Install latest version of Anaconda (https://www.anaconda.com/products/individual), if not installed.
2) Start Jupyter Notebook.
3) Download the zip (horizon-master.zip) into a folder
4) Extract the zip.
5) Copy the files (.csv and .ipynb files) into a folder browsable from Jupyter Notebook 
6) Open the horizonpoint.ipynb file in Jupyter Notebook, and click Kernel->Restart & Run All.
7) To Run for another dataset, Goto line "In [6]: df2 = pd.read_csv('<File>.csv')", and change '<File>' with the name of the file.
8) To compare with Jarvis, open the file jarvis.ipynb in Jupyter Notebook, and click Kernel->Restart & Run All. To Run for another dataset Goto "In [4]" and change '<File>' with the name of the file .
 
