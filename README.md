# BLM 5109 Collective Learning Course Capstone Project at YTU

## Comparison of 3 Different Ensemble Methods Using 10 Shot In-Context Learning (ICL) on YTU Cosmos Turkish Llama 8B DPO Model

**Tasks**  
> Step-1: Her bir veri seti içerisinden 10'er adet sabit örnek belirle. (10 Shot)  
> Step-2: Her bir veri seti içerisinden 400'er adet örnek seç. 400 tane örneğin her biri buradaki 11. soru olacak. (400 Sample)  
> Step-3: 11. örnekler bu 400 tane örneğin her biri olacak. 400'ün içerisinden bir tanesi (11 örnek olarak) koydun ve cevabı aldın. 400'ün içerisinden 2. ciyi aldın koydun ve cevabı aldın. Taki 400. örneğe gelene kadar.  
> Step-4: 10 Shot Sonuçları tmmlandı.  
> Step-5: Ensemble (Size=10)  
>> A: 10'ar kere olmak üzere 10'lu örnekten 10 tane rasgele Yerine Koymalı seçeceksin. (Farklı farklı 10'luklar ile Yani 1 tane örnek için 10 tane cevap alacan)  
>> B: 10'ar kere olmak üzere 10 örnekten 5 tane (replacement yok) seçeceksin.  
>> C: 10'ar kere olmak üzere 10'lu örneğin sıralarını değiştirerek (karıştırarak) seçeceksin. Yer değiştirmek farklı sonuçlar değiştirecek mi?  

> Step-6: Evaluation - https://github.com/EleutherAI/lm-evaluation-harness  
> Step-7: Reporting - IEEE Conference Template  

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

## In-Context Learning(ICL)
    Not Reay Yet

## Evolution
    Language Model Evaluation Harness - https://github.com/EleutherAI/lm-evaluation-harness  

## Preprocess & Modelling
    Not Ready Yet

## Contact
    - Metin Uslu - 235B7014