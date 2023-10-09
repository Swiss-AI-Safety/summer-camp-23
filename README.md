# Summer Camp 2023

## Program

<details>
  <summary>
    <h3>Day 1 - Intro</h3>
  </summary>

#### Technical

Run the notebook in Google Colab:
1. [Exercise 1 Pytorch Introduction](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day01/ex_1_numpy_to_pytorch.ipynb)
2. [Exercise 2 Optimization](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day01/ex_2_optimization.ipynb)
3. [Exercise 3 Einops Basics](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day01/ex_3_einops-basics.ipynb)
4. [Exercise 4 Einops for Deep Learning](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day01/ex_4_einops-for-deep-learning.ipynb)
5. [Exercise 5 Bonus Hyperparameters](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day01/ex_5_bonus_hyperparameters.ipynb)

#### Conceptual

[Introduction to AI Safety](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/conceptual/1._Introduction_to_AI_Safety.pdf)

#### Governance

[Introduction to AIS and AI Governance](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/governance/1.Introduction_to_AIS_and_AI_Gov.pdf)

</details>

<details close>
  <summary>
    <h3>Day 2 - RL</h3>
  </summary>

#### Technical

1. Theory Reinforcement Learning: [overleaf](https://www.overleaf.com/read/gtbwdmkgkpjq) | [pdf](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/tree/main/day02/theory_1_RL_Lecture_Swiss_AI_Safety_Camp-3.pdf) | [book reference](https://www.andrew.cmu.edu/course/10-703/textbook/BartoSutton.pdf)
2. Exercice Deep Q Learning: [google colab](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day02/ex_1_reinforcement_q_learning.ipynb)
3. Reading (chapter 13 til the end of 13.3): [RL Intro Policy Optimization](https://www.andrew.cmu.edu/course/10-703/textbook/BartoSutton.pdf) 
4. Exercice Policy Gradient: [google colab](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day02/ex_2_Policy_Gradient_with_Cartpole_and_PyTorch.ipynb)

#### Conceptual

[RL and problems](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/conceptual/2._RL_and_problems.pdf)


</details>

<details close>
  <summary>
    <h3>Day 3 - Transformers</h3>
  </summary>

#### Technical

[Introduction to Transformers](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day03/transformer.ipynb)

[Play with Tokenizer](https://platform.openai.com/tokenizer)

#### Governance

[2.Understanding_the_ecosystem](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/governance/2.Understanding_the_ecosystem.pdf)

</details>

<details close>
<summary>
    <h3>Day 4 - Prediction and Interpretability</h3>
</summary>
 

#### Conceptual

[3. Prediction](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/conceptual/3.Prediction.pdf)

#### Technical

[Induction Circuits](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day04/induction-circuits.ipynb)

</details>

<details close>
<summary>
    <h3>Day 5 - RLHF and Adversarial attacks</h3>
</summary>

#### Conceptual

[4. Scalable Oversight](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/conceptual/4.Scalable_Oversight.pdf)

#### Technical Policy Gradient and RLHF

[Slides: Policy Gradient and RLHF from Page 23 ](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/tree/main/day05/RL_Lecture_Swiss_AI_Safety_Camp-7.pdf)

[Ex 1: RLHF](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day05/ex1_RLHF.ipynb)

[Reading: Secrets of RLHF in Large Language Models Part I: PPO](https://arxiv.org/pdf/2307.04964.pdf)

[Reading: Learning to summarize from human feedback](https://arxiv.org/pdf/2009.01325.pdf)

#### Technical Adversarial attacks

[Slides: Adversarial attacks introduction](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/tree/main/day05/Adversarial_attacks.pdf)

[Ex 2: Fast Gradient Sign Method notebook](https://colab.research.google.com/github/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/day05/ex2_adversarial_attacks.ipynb)

[Challenge: Gandalf Jailbreak challenge](https://gandalf.lakera.ai/)

[Reading + code: LLM attacks automatic jailbreak](https://llm-attacks.org/)

</details>

<details close>
<summary>
    <h3>Day 6 - Governance Projects</h3>
</summary>

[Project](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/governance/3.Big-day.pdf)

</details>

<details>
<summary>
    <h3>Day 7 - Conceptual Interpretability and Compute Governance</h3>
</summary>

#### Conceptual

[Interpretability](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/conceptual/5.Interpretability.pdf)

#### Governance

[Compute Governance](https://github.com/Swiss-AI-Safety/swiss-summer-camp-23/blob/main/governance/4.Compute-governance.pdf)

</details>

## Installation

You can run the notebook in [Google Colab](https://githubtocolab.com/Swiss-AI-Safety/swiss-summer-camp-23) or [locally](#run-locally).

### Run locally

If you want to run them locally, you can clone the repository

```bash
git clone https://github.com/Swiss-AI-Safety/swiss-summer-camp-23.git
cd swiss-summer-camp-23
conda create --name SAIS python=3.9 -y
conda activate SAIS
conda install pytorch torchvision torchaudio cpuonly -c pytorch -y
pip install -r requirements.txt
```
