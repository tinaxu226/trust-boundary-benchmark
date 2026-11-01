
**Trust Boundary Benchmark
Code and data for the paper**

Ting Xu and Henry Leung. 
Does the Trust Boundary Hold over Time? A Long-Horizon Benchmark for Receiver-Directed Federated Learning. 2026.

**Status**

The code will be released here once the paper is accepted. This page will be updated at that time.

**What the benchmark measures**

In receiver-directed federated learning, each site judges, on its own data, whether a transfer from another site helps, harms or cannot yet be told. The benchmark asks whether these judgements stay correct over hundreds of rounds of training. It provides:

1. a semi-synthetic federation of thirteen sites, with minority groups whose outcome relationship differs from the majority;
an exact oracle for the benefit of every transfer, scored against both a fixed reference and the receiver's current model;
paired seeds and an attack protocol;

2. fourteen aggregation and admission methods on CPU, over 150 and 600 rounds;

3. a GPU tier with Qwen3-1.7B LoRA sites;

4. a terminal audit that decides, after training, whether each final model is deployed or the site falls back to local training.


**What will be released**

Configurations and seeds for every run in the paper, a run manifest, raw outputs of every run, aggregation scripts that produce the tables and figures, CPU-only reproduction mode, and citations


**Contact**

Ting Xu, University of Calgary (tina.xu1@ucalgary.ca)

