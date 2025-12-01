# QuantumChem-200K: A Large-Scale Open Organic Molecular Dataset for Quantum-Chemistry Property Screening and Language Model Benchmarking
We introduce QuantumChem-200K, a large-scale dataset of over 200,000 organic molecules annotated with eleven quantum-chemical properties, including two-photon absorption (TPA) cross sections, TPA spectral ranges, singlet–triplet intersystem crossing (ISC) energies, toxicity and synthetic accessibility scores, hydrophilicity, solubility, boiling point, molecular weight, and aromaticity. These values are computed using a hybrid workflow that integrates density function theory (DFT), semi- empirical excited-state methods, atomistic quantum solvers, and neural-network predictors.
Data is available at: https://huggingface.co/datasets/YinqiZeng704/200k_monomer_properties

# Two-photon absorption (TPA) lithography to fabricate advanced micro-optical devices:
<img width="422" height="447" alt="Screenshot 2025-11-30 at 18 30 53" src="https://github.com/user-attachments/assets/5eaba58a-f4c5-4345-8e71-f3651a7b353b" />

# Data curation process:
<img width="981" height="751" alt="Screenshot 2025-11-30 at 18 25 57" src="https://github.com/user-attachments/assets/7264ac7e-b3bf-4b61-a51e-7ee792d0e64d" />

# Fine-tuning and evaluation:
Using QuantumChem-200K, we fine-tuned the open-source Qwen-2.5-32B LLM to create a chemistry AI assistant capable of forward polymer property prediction from SMILES. It demonstrates that domain-specific fine-tuning significantly improves prediction accuracy over baselines such as GPT-4o, Llama-3.1-70B, and the base Qwen2.5- 32B model. The evaluation metric used is the wMAE:

<img width="499" height="217" alt="Screenshot 2025-11-30 at 18 31 14" src="https://github.com/user-attachments/assets/d774aa09-5ea5-45fc-8f6d-11975669b065" />

# Benchmarking:
<img width="1079" height="491" alt="Screenshot 2025-11-30 at 18 35 53" src="https://github.com/user-attachments/assets/24e8c983-2a75-4175-b248-fe570fd5e9ab" />


