# DeepLense_SSL

Directory Structure:-
Root directory
├── task1_models
│	├── best.pth
├── task2_models
│	├── best_encoder.pth
│	├── classifier_logreg.pkl
├── common_task.ipynb
├── preds_ct.csv
├── README.md
├── requirements.txt
├── roc_auc_results_task1.csv
└── specific_task6.ipynb


For the replication of results obtained:-
 1. Clone this repository.
 2. Open the cloned directory.
 3. Open the terminal and execute "pip install -r requirements.txt"
 4. Ensure that you extract the common dataset and task 6 dataset in this directory itself. Please look at the directory structure above to ensure files are placed correctly.
 5. Open the folders "task1_models" and "task2_models" and download the models from the given drive link. The drive links are present in the REAMDE.md file in the folders.
 6. The Jupyter Notebook named "common_task.ipynb" corresponds to the common task, and the one called "specific_task6.ipynb" corresponds to the specific task 6.
 7. Open the notebooks and run them. The notebook is filled with comments for explaining the approach. NOTE: If you want to perform inference only, you can just skip the cells corresponding to training loops (mentioned in the notebook as well).

The drive link for the models and dataset zip files is given below:-

https://drive.google.com/drive/folders/1TPOi9csL53reiHre1ejHPUkjgni2NwOY?usp=sharing

NOTE: The links for models in their directory and the one given here are same.
