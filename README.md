
Trust Boundary Benchmark
Code and data for the paper

Ting Xu and Henry Leung. Does the Trust Boundary Hold over Time? A Long-Horizon Benchmark for Receiver-Directed Federated Learning. 2026.

Status
The code will be released here once the paper is accepted. This page will be updated at that time.

What the benchmark measures
In receiver-directed federated learning, each site judges, on its own data, whether a transfer from another site helps, harms or cannot yet be told. The benchmark asks whether these judgements stay correct over hundreds of rounds of training. It provides:

a semi-synthetic federation of thirteen sites, with minority groups whose outcome relationship differs from the majority;
an exact oracle for the benefit of every transfer, scored against both a fixed reference and the receiver's current model;
paired seeds and an attack protocol;
fourteen aggregation and admission methods on CPU, over 150 and 600 rounds;
a GPU tier with Qwen3-1.7B LoRA sites;
a terminal audit that decides, after training, whether each final model is deployed or the site falls back to local training.
What will be released
Configurations and seeds for every run in the paper
A run manifest
Raw outputs of every run
Aggregation scripts that produce the tables and figures
A CPU-only reproduction mode
Citation
A BibTeX entry will be added here once the preprint is online.

Contact
Ting Xu, University of Calgary (tina.xu1@ucalgary.ca)

