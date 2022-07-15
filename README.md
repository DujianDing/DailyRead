# DailyRead

June 14, 2022
- **BlinkML: Approximate Machine Learning with Probabilistic Guarantees**, Yongjoo Park, Jingyi Qing, Xiaoyang Shen, Barzan Mozafari. **SIGMOD 2019** ([arxiv](https://arxiv.org/abs/1812.10564)) (Citations **13**) 
  - Estimate the deviation of model outputs `m(x;\theta_{N})` from `m(x;\theta_{n})` where `\theta_{N}` (resp. `\theta_{n}`) is the parameter instance trained on `N` (resp. `n`) samples, using a model trained on the initial sample of size `n_0`, for any `N` and `n`. 
  - Only support models relying on **maximum likelihood estimation** with **convex optimization objectives**.

July 2, 2022
- **Declarative Machine Learning Systems**, Piero Molino, Christopher Ré, **ArXiv 2021** ([arxiv](https://arxiv.org/abs/2107.08148)) (Citations **5**)
- **Personalized Benchmarking with the Ludwig Benchmarking Toolkit**, Avanika Narayan, Piero Molino, Karan Goel, Willie Neiswanger, Christopher Ré. **NeurIPS 2021** ([arxiv](https://arxiv.org/abs/2111.04260)) ([code](https://github.com/HazyResearch/ludwig-benchmarking-toolkit)) (Citations **4**)
- **Overton: A Data System for Monitoring and Improving Machine-Learned Products**, Christopher Ré, Feng Niu, Pallavi Gudipati, Charles Srisuwananukorn. **CIDR 2020** ([CIDR](https://www.cidrdb.org/cidr2020/papers/p33-re-cidr20.pdf)) (Citations **28**)
  - Systems (e.g., Overton, Ludwig) that allow users to build end-to-end ML pipelines through a declarative configuration. 
  - Such pipelines include data preprocessing, the model architecture building, the training loop, the prediction and the evaluation of pipelines. 
  - Especially, Ludwig supports multi-objective evaluation (e.g., accuracy, latency, training speed, model size, carbon footprint) and provides APIs to generate visualizations and reports.

July 15, 2022
- **Using Sampling to Estimate and Improve Performance of Automated Scoring Systems with Guarantees**, Yaman Kumar Singla, Sriram Krishna, Rajiv Ratn Shah, Changyou Chen, **AAAI 2022** ([paper](https://www.aaai.org/AAAI22Papers/EAAI-00074-SinglaY.pdf)) (Citations **2**)
