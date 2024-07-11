

# On the Importance of Initialization in Active Learning
This code accompanies the paper `On the Importance of Initialization in Active Learning` and utilizes the Python package `ALPBench`. We compare the effect on the performance of different active learning pipelines when being differently initialized.


# 🛠️ Install
To run the code, you need to install `ALPBench`, which is intended to work with **Python 3.10 and above**.

```
# The base package can be installed via pip:
pip install alpbench

# Alternatively, you can install the full package via pip:
pip install alpbench[full]

# Or you can install the package from source:
git clone https://github.com/ValentinMargraf/ActiveLearningPipelines.git
cd ActiveLearningPipelines
conda create --name alpbench python=3.10
conda activate alpbench

# Install for usage (without TabNet and TabPFN)
pip install -r requirements.txt

# Install for usage (with TabNet and TabPFN)
pip install -r requirements_full.txt
```

Documentation at https://activelearningpipelines.readthedocs.io/en/latest/


# Experiments
To reproduce our results, run `Small.py` inside alpbench/evaluation/experimenter/.
We aggregated the results into saved_dictionary.pkl inside alpbench/evaluation/analysis/. There you also find the notebook `evaluation_ecai_workshop.ipynb` to generate the figures and tables.
