# BLM 5109 Collective Learning Course Capstone Project {Ensemble with In Context Learning } at YTU

In Context Learning’de (CNL) Ensemble: cosmos-DPO île 3 veri kümesi üzerinde (ARC, Hellaswag, GMSK8K) 10 shot sonuçlarını (400 örnek üzerinde) elde edip raporlayın. Aşağıdaki 3 yöntemle ensemblelar (ensemble size=10) üretip karşılaştırın.  
A- 10 örnekten 10’lu seçimler  
B- 10 örnekten 5’li seçimler 
C- 10 örneğin sıralarını değiştirmek
ensemble içindeki tekil öğrenicilerin her birinin performansını ve ensemble performansını raporlayın. Karşılaştırma için araç: https://github.com/EleutherAI/lm-evaluation-harness

## Project Details
> **Description:** - & More Details: KolektifÖğrenme-ProjeÖnerileri_20241.pdf  
> **Course Name:** BLM5109 - Collective Learning  
> **Course Url:** http://bologna.yildiz.edu.tr/index.php?r=course/view&id=6047&aid=3  
> **Course Page:** https://sites.google.com/view/mfatihamasyali/kolektif-%C3%B6%C4%9Frenme  

## Installation
**Step-1.1:** Create Env. 
```
conda create --name "py_env_312" python=3.12  
conda activate py_env_312  
python -V
```

**Step-1.2:** Remove the environment if necessary
```
conda remove --name py_env_312 --all
```

**Step-2:** Install Libraries & Frameworks
```
# https://jupyter.org/install
pip install jupyterlab

# https://www.tensorflow.org/install
pip install tensorflow

# https://pytorch.org/
pip install torch torchvision torchaudio

# Install Requirements File
pip install -r requirements.txt
```

**Step-3:** Start Jupyter IDE
```
# Start Jupyter Lab / Notebook
jupyter lab
jupyter notebook
```

## Datasets
    malhajar/arc-tr - https://huggingface.co/datasets/malhajar/arc-tr
    malhajar/gsm8k_tr-v0.2 - https://huggingface.co/datasets/malhajar/gsm8k_tr-v0.2
    malhajar/hellaswag-tr - https://huggingface.co/datasets/malhajar/hellaswag-tr

    HuggingFace Collection: https://huggingface.co/collections/metinuslu/capstone-6769c22ed8c54b90132030da

## Models
    ytu-ce-cosmos/Turkish-Llama-8b-DPO-v0.1 - https://huggingface.co/ytu-ce-cosmos/Turkish-Llama-8b-DPO-v0.1

## Evolution
    Language Model Evaluation Harness - https://github.com/EleutherAI/lm-evaluation-harness  

## Preprocess & Modelling
    Not Ready Yet

## Contact
    - Metin Uslu - 235B7014