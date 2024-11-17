# EMNLP 2024: How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning

## Introduction

This repo is for the EMNLP 2024 paper: [How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning](https://zepingyu0512.github.io/in-context-mechanism.github.io/)

This work explores the mechanism of in-context learning.

This work also uses the techniques and insights in:

[EMNLP 2024: Neuron-Level Knowledge Attribution in Large Language Models](https://zepingyu0512.github.io/neuron-attribution.github.io/)

[EMNLP 2024: Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis](https://zepingyu0512.github.io/arithmetic-mechanism.github.io/)

## Running code

Environment versions: please see **environment.yml**

First, please use modeling_llama.py to replace the original file in the transformers path, which is usually in anaconda3/envs/YOUR_ENV_NAME/lib/python3.8/site-packages/transformers/models/llama. This modified file is useful for extracting the internal vectors during inference time. **Please remember to save the original file.** 

Then, run the code in Llama_view_incontext.ipynb using jupyter notebook. This introduces how to analyze one in-context learning sentence.

## cite us: 

```
@article{yu2024large,
  title={How do Large Language Models Learn In-Context? Query and Key Matrices of In-Context Heads are Two Towers for Metric Learning},
  author={Yu, Zeping and Ananiadou, Sophia},
  journal={arXiv preprint arXiv:2402.02872},
  year={2024}
}
```


