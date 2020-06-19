
## development Introdution
The Adaptive Network-Based Fuzzy Inference System (ANFIS) architecture is a long-established and popular approach to implementing fuzzy systems. In this paper, we implement ANFIS using PyTorch framework. PyTorch is an open-source deep learning platform for Python, featuring: (1) tensor computing. (2) automatic differentiation in recorded tensor operations. (3) libraries for neural nets, optimisers, and loss functions. For the experiment, we using Python v3.7.3, the Anaconda v4.7.12 distribution and PyTorch v1.5.0+cpu. The training was carried out on a computer with an Intel Xeon E5-2667 v4 processor running at 3.20 GHz using 16 GB of DDR4 RAM, running Ubuntu version 16.04.5 LTS (Xenial Xerus).


自適應神經模糊推理系統（ANFIS）架構是流行於早期模糊系統中所使用的方法。在本論文中我們將ANFIS使用Pytorch框架進行實作。PyTorch是Facebook AI研究團隊發布的一個深度學習框架，它能夠實現張量計算和動態神經網絡，以及自動計算每個張量中的梯度微分。並且具有很好的靈活性與易用性，因而廣受機器學習研究者歡迎。此外它還提供神經網路、優化器與損失函數的函式庫。在實驗中我們採用Python v3.7.3、Anaconda 4.7.12 (發行版)、PyTorch v1.5.0+cpu。電腦機器學習硬體使用Intel Xeon E5-2667 v4 3.20 GH處理器、16 GB的DDR4記憶體並運行於Ubuntu 16.04.5 LTS (Xenial Xerus)作業系統。 
