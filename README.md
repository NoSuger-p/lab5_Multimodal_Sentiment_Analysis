# 多模态情感分析

这是当代人工智能的第五次实验作业，基于 TextCNN 和 CNN 来实现多模态融合模型

## Setup

This implemetation is based on Python3. To run the code, you need the following dependencies:

- numpy==1.25.4
  
- tensorflow==2.13.0
  
- pandas==1.3.5

- keras==2.13.1

- nltk==3.8.1

- torch==2.0.1 

- torchvision==0.15.2

- sklearn==1.0.1

You can simply run 

```python
pip install -r requirements.txt
```

## Repository structure
We select some important files for detailed description.

```python
|-- data # training and testing data (.txt & .jpg)
|-- data_json # data after data preprocessing
    |-- test.json # test data
    |-- train.json # train data
    |-- val.json # val data
|-- results
    |-- results.txt # final testing results
|-- README.md
|-- lab5.ipynb # all code 
|-- requirements.txt # packages required
|-- test_without_label.txt # testing data
|-- train.txt # train data label
```

## Run

按照 notebook 顺序运行即可，分为数据预处理、构建词汇表、消融实验：仅文本训练、消融实验：仅图片训练、多模态融合模型五个部分

