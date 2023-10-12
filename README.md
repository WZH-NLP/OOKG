# VNC
This repo is a PyTorch implementation of "[Iteratively Learning Representations for Unseen Entities with Inter-Rule Correlations](https://arxiv.org/pdf/2305.10531.pdf)" (CIKM 2023).

## Introduction


## Get started
We list commands with different hyperparameters in ```run.sh```. For example, you can train and evaluate VNC with the following command:
```python
python -u main_run.py --gpu 0 --penalty 0.5 --epochs 4000 --model "distmult" --embedding-dim 100 --evaluate-every 50  --data fb15k  --sub-data subject-10 --isSigmoid True  --n-bases 100  --batch-size 30000  --n_epochs_aux 200
```

## Reference
```
@inproceedings{wang2023Iterative,
  author    = {Zihan Wang, Kai Zhao, Yongquan He, Zhumin Chen, Pengjie Ren, Maarten de Rijke, and Zhaochun Ren},
  title     = {Iteratively Learning Representations for Unseen Entities with Inter-Rule Correlations},
  booktitle = {{CIKM} '23: the 32nd ACM International Conference on Information and Knowledge Management, October 21–25, 2023, Birmingham, UK.},
  year      = {2023}
}
```

