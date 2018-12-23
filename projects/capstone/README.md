# Machine Learning Engineer Nanodegree
## Specializations
## Project: Capstone Proposal and Capstone Project

### **Software used**
Assumptions 
1. _Anaconda is already installed._

#### _Steps_
1. Create a folder named _capstone_ in your favorite location.
2. Extract the project submission into this folder. It should have project.ipynb available here. Download the dataset from [Kaggle][DonorChoose.org data]
3. Extract the contents of the zip folder into capstone/io folder.

_I used python virtualenv for this project.
Run the following commands in a **terminal window**._
<!--Create a virtual env called capstone with python 3.6.2 and anaconda-->
4. conda create -n capstone _python=3.6.2 anaconda_  
<!--activate this virtual environment -->
5. source activate capstone
<!--Ensure pip version is current -->
6. pip install _--upgrade pip_
<!--install sklearn package -->
7. pip install _sklearn_
<!--install tqdm package-->
8. pip install _tqdm_
<!--install  matplotlib package-->
9. pip install _matplotlib_
<!--install numpy package -->
10. pip install _numpy_
<!-- install ipython package -->
11. pip install _IPython_
<!--This is an optional package to run the jupyter notebook from the command line -->
12. pip install _runipy_
<!--start jupyter notebook -->
13. cd xxx/capstone folder.
<!--start jupyter notebook. Since there is bug with the current version an additional parameter was included -->
14. jupyter notebook --NotebookApp.iopub_data_rate_limit=1.0e10
<!--Navigate to the capstone folder -->
15. navigate to the capstone folder and open project.ipynb.
<!--run the project -->
16. Run the project with notebook


[DonorChoose.org data]: https://www.kaggle.com/donorschoose/io/downloads/io.zip/8
