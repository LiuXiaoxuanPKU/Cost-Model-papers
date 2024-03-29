## Open Source Projects
- Cost Model
  - [nn-Meter: Towards Accurate Latency Prediction of Deep-Learning Model Inference on Diverse Edge Devices](https://github.com/microsoft/nn-Meter)
  - [Paleo: A Performance Model for Deep Neural Networks](https://github.com/TalwalkarLab/paleo)
- Distributed Training
  - [ZeRO-Infinity: Breaking the GPU Memory Wall for Extreme Scale Deep Learning](https://github.com/microsoft/DeepSpeed)
  - [Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://github.com/NVIDIA/Megatron-LM)
  - [Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning](https://github.com/alpa-projects)

## Memory Cost Model
- [Estimating GPU Memory Consumption of Deep Learning Models](https://www.microsoft.com/en-us/research/uploads/prod/2020/09/dnnmem.pdf) by Yanjie Gao et al., ESEC/FSE 2020

## Computation Cost Model
- Cost Model for NAS/Cloud
  - [Daydream: Accurately Estimating the Efficacy of Optimizations for DNN Training](https://www.usenix.org/system/files/atc20-zhu-hongyu.pdf) by Hongyu Zhu et al., USENIX ATC 2020
  - [Habitat: A Runtime-Based Computational Performance Predictor for Deep Neural Network Training](https://www.usenix.org/system/files/atc21-yu.pdf) by Geoffrey X. Yu et al., USENIX ATC 2021
  - [To bridge neural network design and real-world performance: A behaviour study for neural networks](https://proceedings.mlsys.org/paper/2021/file/02522a2b2726fb0a03bb19f2d8d9524d-Paper.pdf) by Xiaohu Tang et al., MLSys 2021
  - [perf4sight: A toolflow to model CNN training performance on Edge GPUs](https://arxiv.org/pdf/2108.05580.pdf) by Aditya Rajagopal et al., ArXiv 2021
  - [nn-Meter: Towards Accurate Latency Prediction of Deep-Learning Model Inference on Diverse Edge Devices](https://dl.acm.org/doi/pdf/10.1145/3458864.3467882?casa_token=x0qNEhcP_wAAAAAA:uCTMD3yLynIaS7PwFvxzT65oxmrKz6EyOClSjYNCr-t036yn8VsqJcNjygQDkhR_04NeyZvRWS0e) by Li Lyna Zhang et al., MobiSys 2021
  - [Empirical Analysis and Modeling of Compute Times of CNN Operations on AWS Cloud](https://ieeexplore.ieee.org/abstract/document/9251263) by Ubaid Ullah Hafeez et al., IISWC 2020
  - [Paleo: A Performance Model for Deep Neural Networks](https://openreview.net/pdf?id=SyVVJ85lg) by Hang Qi et al., ICLR 2017
  - [Augur: Modeling the Resource Requirements of Convolutional Neural Networks on Mobile Devices](https://arxiv.org/pdf/1709.09503.pdf) by Zongqing Lu et al., Proceedings of the 25th ACM international conference on Multimedia 2017
  - [Performance Modelling of Deep Learning on Intel Many Integrated Core Architectures](https://arxiv.org/pdf/1906.01992.pdf) by Andre Viebke et al., ArXiv 2019
 
- Cost model for kernel compilation
  - [A learned Performance Model for Tensor Processing Units](https://arxiv.org/abs/2008.01040) by Samuel J. Kaufman et al., MLSys 2021

## Communication Cost Model
- [Iteration Time Prediction for CNN in Multi-GPU Platform: Modeling and Analysis](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8713989) by Ziqian Pei et al., IEEE Access 2019

## Distributed Training
- [Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning](https://arxiv.org/pdf/2201.12023.pdf) by Lianmin Zheng et al., ArXiv 2022
- [Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://arxiv.org/pdf/1909.08053.pdf) by Mohammad Shoeybi et al., ArXiv 2019
- [ZeRO-Infinity: Breaking the GPU Memory Wall for Extreme Scale Deep Learning](https://arxiv.org/pdf/2104.07857.pdf) by Samyam Rajbhandari et al., SC 2021
- [Improving the Accuracy, Scalability, and Performance of Graph Neural Networks with Roc](https://cs.stanford.edu/~zhihao/papers/mlsys20.pdf) by Zhihao Jia et al., MLSys 2020
- [A Distributed Multi-GPU System for Fast Graph Processing](http://www.vldb.org/pvldb/vol11/p297-jia.pdf) by Zhihao Jia et al., VLDB 2017

## Device Placement
- [Device Placement Optimization with Reinforcement Learning](https://arxiv.org/pdf/1706.04972.pdf) by Azalia Mirhoseini et al., ICML 2017
- [DUET: A Compiler-Runtime Subgraph Scheduling Approach for Tensor Programs on a Coupled CPU-GPU Architecture](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9460468&casa_token=2gAY08LpV_oAAAAA:CPc0zg6FF4hQ9AfoW2X5SpyxYWcQQpn0G_kxQ-5QXwCHYhD--lf5A4-ELiSlXrKcDTXbsI2sEKg) by Minjia et al., IEEE IPDPS 2021

## Memory Optimization for Training
- gradient checkpoint
  - [Training Deep Nets with Sublinear Memory Cost](https://arxiv.org/pdf/1604.06174.pdf) by Tianqi Chen et al., arXiv 2016
  - [Efficient Rematerialization for Deep Networks](https://proceedings.neurips.cc/paper/2019/file/ffe10334251de1dc98339d99ae4743ba-Paper.pdf) by Ravi Kumar et al., NeurIPS 2019
  - [Checkmate: Breaking the Memory Wall with Optimal Tensor Rematerialization](https://arxiv.org/pdf/1910.02653.pdf) by Paras Jain et al., MLsys 2020
  - [Dynamic Tensor Rematerialization](https://arxiv.org/pdf/2006.09616.pdf) by Marisa Kirisame et al., ICLR 2021
- gradient checkpoint + distributed training
  - [Reducing Activation Recomputation in Large Transformer Models](https://arxiv.org/pdf/2205.05198.pdf) by Vijay Korthikanti et al., arXiv 2022
- kernel fusion
  - [Data movement is all you need: A case study on optimizing transformers](https://proceedings.mlsys.org/paper/2021/file/c9e1074f5b3f9fc8ea15d152add07294-Paper.pdf) by Andrei Ivanov et al., MLSys 2021
- compression/quantization
  - [Gist: Efficient Data Encoding for Deep Neural Network Training](https://www.microsoft.com/en-us/research/uploads/prod/2018/04/fiddle-gist-isca18.pdf) by Animesh Jain et al., ISCA 2018 
  - [Gradient Compression Supercharged High-Performance Data Parallel DNN Training](https://www.ruichuan.org/papers/hipress-sosp21.pdf) by Youhui Bai et al., SOSP 2021
  - [GACT: Activation compressed training for generic network architectures](https://proceedings.mlr.press/v162/liu22v/liu22v.pdf) by Xiaoxuan Liu et al., ICML 2022
  - [On the Utility of Gradient Compression in Distributed Training Systems](https://proceedings.mlsys.org/paper/2022/hash/cedebb6e872f539bef8c3f919874e9d7-Abstract.html) by Saurabh Agarwal et al., MLsys 2022
- swapping
  - [Optimal GPU-CPU Offloading Strategies for Deep Neural Network Training](https://hal.inria.fr/hal-02316266/document) by Olivier Beaumont et al., European Conference on Parallel Processing 2020
  - [SwapAdvisor: Push Deep Learning Beyond the GPU Memory Limit via Smart Swapping](http://www.news.cs.nyu.edu/~jinyang/pub/swapadvisor-asplos20.pdf) by Huang et al., ASPLOS 2020
  - [Harmony: Overcoming the hurdles of GPU memory capacity to train massive DNN models on commodity servers](https://arxiv.org/pdf/2202.01306.pdf) by Youjie Li et al., VLDB2022.
  - [STRONGHOLD: Fast and Affordable Billion-Scale Deep Learning Model Training](https://github.com/strongh2/sc22-ae) by Xiaoyang Sun et al., SC2022
  - [ZeRO-Offload: Democratizing Billion-Scale Model Training](https://www.usenix.org/conference/atc21/presentation/ren-jie) by Jie Ren et al., USENIX ATC'21
- swapping + pipeline parallelism
  - [Harmony: Overcoming the hurdles of GPU memory capacity to train massive DNN models on commodity servers](https://arxiv.org/pdf/2202.01306.pdf) by Youjie Li et al., VLDB 2022.
- swapping + gradient checkpointing
  - [Capuchin: Tensor-based gpu memory management for deep learning](https://dl.acm.org/doi/pdf/10.1145/3373376.3378505?casa_token=Fa8ZayNjRk0AAAAA:8Bc7PzTe0SrH_edARFzh1vi7ll7CNzUDHsk4pHiOu8dwbmHExYFtYeQGKCKIqtPhS-tSXN1q_kn1KA) by Peng, Xuan, et al., ASPLOS 2020
  - [Efficient Combination of Rematerialization and Offloading for Training DNNs](https://proceedings.neurips.cc/paper/2021/file/c8461bf13fca8a2b9912ab2eb1668e4b-Paper.pdf) by Olivier Beaumont et al., NeurIPS 2021
  - [POET: Training Neural Networks on Tiny Devices with Integrated Rematerialization and Paging](https://proceedings.mlr.press/v162/patil22b.html) by Shishir G. Patil, ICML 2022
 - Memory Allocator
   - [OLLA: Optimizing the Lifetime and Location of Arrays to Reduce the Memory Usage of Neural Networks](https://arxiv.org/abs/2210.12924) by Benoit Steiner et al., Arxiv 2022
 - Efficient Optimizer
   - [ZeRO: Memory Optimizations Toward Training Trillion Parameter Models](https://arxiv.org/abs/1910.02054) by Samyam Rajbhandari et al., SC'20
   - [1-bit Adam: Communication Efficient Large-Scale Training with Adam's Convergence Speed](http://proceedings.mlr.press/v139/tang21a.html) by Hanlin Tang et al., ICML 2021
 - Hardware related
   - [FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/abs/2205.14135) by Tri Dao et al., NeurIPS 2022
  
## Framework Introduction
- [PyTorch Internal](http://blog.ezyang.com/2019/05/pytorch-internals/)
- [Profiler Trace File](https://docs.google.com/document/d/1CvAClvFfyA5R-PhYUmn5OOQtYMH4h6I0nSsKchNAySU/preview)
- [Characterizing Deep Learning Training Workloads on Alibaba-PAI](https://arxiv.org/pdf/1910.05930.pdf) by Mengdi Wang et al., IISWC 2019
