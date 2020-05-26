# sparse_attentive_backtracking_release
Code for our paper "Sparse Attentive Backtracking: Sparse Attentive Backtracking: Temporal Credit Assignment Through Reminding" 
https://papers.nips.cc/paper/7991-sparse-attentive-backtracking-temporal-credit-assignment-through-reminding.pdf


Create environment using 

    conda env create -f env.yml

Need: 
- pytorch 1.4.0
- CUDA 10.1
- cuDNN 7.6

To run experiment, use the following command

    python train_copying_torch.py -T 100 --model sparseattn --trunc 5 --topk 5
