# Walrus_from_space
This GitHub is the code used for the Masters of Research Project for the Cambridge AI4ER, titled:

**Walrus from space, using satellite images to monitor walrus haul-ours across Svalbard.**

## Use
### Installing dependencies

You may want to install the dependencies in a virtual environment of your choice.

```shell
pip install -r requirement.txt
```

## Where to start?

## Structure

### Data
The data has been collected and is under .......

Data should place in a folder called `data`, in the same folder as `notebooks`.

### Notebooks
The notebooks show all the different explorations taken.
The main structure is the following:  

```
notebooks
│
├── 1_open_explore_data
│   │  This for exploring the data, and a sandbox to understand how to handle the satellite data. 
│   │
│   ├──1.1_data_analysis
│   │       notebooks that looks at the data, as well as some PCA analysis.
│   └──1.2_image_enhancement
│           is for the notebooks that try some classical image enhancement to see if they could work at detecting walruses.
│
├── 2_spectral_profiles
│       Collection of notebooks that shows the spectral analysis and profiles of the different region of interests in the images.
│       As well as exploring what class to group together.
│
├── 3_class_imbalance
│       Explores different way to the class imbalance present, using methods like SMOTE and ADASYN.
│
├── 4_random_forest
│       Mutliple runs of Random Forest, form different preprocessing to location.
│
├── 5_knn
│       Some tries with KNNs.
│
├── 6_xgboost
│       A notebook for the implementation with XGBoost
│
├── 7_ensemble
│       An essemble model, and using some ocean buffer
│
├── 8_cnn
│       Some try at CNNs and UNET
│
└── 9_compare_model
        Multiple notebooks to compare all the different models.
```

Some noteworthy notebooks are:
`1_open_explore_data/1.1_data_analysis/PCA_Analysis_cluster_labels` which shows some of the PCA of the data.
Include images?


`3_class_imbalance/class_imbalance_using_spectral.ipynb` shows Welch's t-test, ANOVA, and Kruskal-Wallis H Test for 
.... and include a table.


`4_random_forest/smart_RF_up_down_samp_allislands.ipynb` Tomek  Links under-sampling


## Results


## License


## Acknowledgements
