# DailyRead

June 14, 2022
- **BlinkML: Approximate Machine Learning with Probabilistic Guarantees** Yongjoo Park, Jingyi Qing, Xiaoyang Shen, Barzan Mozafari. **SIGMOD 2019** ([arxiv](https://arxiv.org/abs/1812.10564)) (Citations **13**) 
  - Estimate the deviation of model outputs `m(x;\theta_{N})` from `m(x;\theta_{n})` where `\theta_{N}` (resp. `\theta_{n}`) is the parameter instance trained on `N` (resp. `n`) samples, using a model trained on the initial sample of size `n_0`, for any `N` and `n`. 
  - Only support models relying on **maximum likelihood estimation** with **convex optimization objectives**.
