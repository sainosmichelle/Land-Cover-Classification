<h1> Land cover classification </h1>
<br/>
<img src="https://github.com/sainosmichelle/TerraWare-HV/blob/master/images/eurosat.png"
  width="1000"
  height="500">

<p>Python notebooks made to classify land cover crops of satellite images from <a href="https://github.com/phelber/EuroSAT" title="Title">EuroSat dataset</a> in Python 3. </p>

<p>The task has been done in two main approaches to evaluate their performance: classification using shallow learning techniques and using deep learning.</p>
<p>For the shallow learning approach, a local and global feature has been done and also a feature selection using a ranking technique. For the classification I´ve used Random Forest with high variance decision trees. For the deep learning I´ve used the raw RGB images and the ResNet50 architecture with transfer learning as suggested in <a href="https://arxiv.org/abs/1709.00029" title="Title">
Helber, et al. 2019.</a></p>

<h2>Getting Started</h2>
The code is developed in python 3, you can run it in Colab or in your local Anaconda Enviroment.

<p>If you run it in your local enviroment make sure to use your GPU and verify if the following packages are installed</p>

```
pip install tensorflow==1
pip install keras==2.2
conda install numpy
conda install pandas
conda install matplotlib
conda install scikit-learn
conda install scikit-image
conda install opencv-python
```

<h3>Colab ussage</h3>
<p>Run the first .ipynb to download the dataset in your Google Drive session from the <a href="https://www.kaggle.com/apollo2506/eurosat-dataset" title="Title">
Kaggle repository</a>. </p>

<h2>Running the notebooks</h2>
<p>Run the notebooks one by one and modify them to get to the results you want.</p>


<h2>Contributing</h2>
<p>Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.</p>
<h2>Authors</h2>
<ul>
<li> <b>Michelle Sainos Vizuett</b> <em>- Coder</it></em> </li>
</ul>
