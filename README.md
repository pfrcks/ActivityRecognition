# Activity Recognition

### An attempt to improve efficiency of Activity Recognition through accelerometer data.

A work in progress. 

#### Installation

* Requires Python (preferably v2.7)
* pip


Execute `pip install -r requirements.txt`

#### How-To

* Clone this repo on your local machine
* execute `jupyter-notebook file-name`
* Take a quick tour of [ipython](https://ipython.org/ipython-doc/rel-0.10.2/html/interactive/tutorial.html) and [jupyter-notebooks](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)
Note : DTW_ACT.ipynb does not work well in the jupyter notebook environment. Hence use `ipython DTW_ACT(1).py` for large datasets.

#### Explanation

* LSH_ACT : Approximate Nearest Neighbors using Locality Sensitive Hashing
* Annoy   : Approximate Nearest Neighbors using the Annoy Library
* DTW_ACT : Exact Nearest Neighbors using KNN-DTW and PCA

#### Contributing

* Clone this repo to your system
* Make changes/create new
* Do `git add file-name1 filename2 ... `
* Do `git commit -m "A short and meaningful message"`
* Do `git push -u origin master`

#### Milestones achieved

- [X] KNN - DTW on WISDM Dataset
- [X] KNN - DTW with PCA on WISDM Dataset
- [X] KNN - DTW on HAR Dataset
- [X] KNN - DTW with PCA on HAR Dataset
- [X] ANN using Annoy library on WISDM Dataset
- [X] ANN using Annoy library on HAR Dataset
- [ ] Apply these technologies on a dataset with dedicated accelerometer
- [ ] Comparison with approaches utilized in the original papers
- [ ] Making of new features and/or discarding features for inherent analysis
- [ ] Applying deep learning methods ?

