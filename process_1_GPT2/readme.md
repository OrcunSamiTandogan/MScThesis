conda env remove -n bilimlan
conda create -n bilimlan python=3.12 -y 
conda activate bilimlan
conda install -c conda-forge pandas numpy scipy scikit-learn umap-learn transformers matplotlib ipykernel nbformat -y 
conda install torchvision -c pytorch -y 




conda install -c conda-forge imbalanced-learn


conda env remove -n bilimtext
conda create -n bilimtext python=3.12 -y 
conda activate bilimtext
conda install openai==0.28.1 -y
conda install -c conda-forge pandas numpy scipy pytorch ipykernel nbformat -y 
conda install torchvision -c pytorch -y 
conda install -c conda-forge imbalanced-learn