<div align="center">

# Jinyu Cong · 丛津宇

**Master's student in Machine Learning for Data Science @ Université Paris Cité**

Multimodal LLMs · Preference alignment (RLHF / DPO) · Generative recommendation

</div>

---

## About me

I come from computational linguistics (NLP master's at INALCO) and now work on machine learning at Université Paris Cité. I like understanding methods by rebuilding them from scratch: the repositories below go from tabular RL to a GPT and a full PPO-based RLHF pipeline.

**Research interests**

- **Multimodal learning**: cross-modal alignment, latent-space prediction (JEPA lineage), mixture-of-experts fusion
- **Preference alignment**: RLHF with PPO, DPO and its variants, reward signals for reducing hallucination
- **Generative recommendation**: preference optimization with cross-modal consistency signals
- **Language models, from the ground up**: transformer internals, KV cache, training dynamics

**Currently**

- Working toward a first research paper on multimodal preference optimization
- Studying the JEPA family of self-supervised models
- Building a CPU ray tracer in C# as a side project

---

## Selected projects

### Alignment and language models

| Project | What it is |
|---|---|
| [**PPO-RLHF**](https://github.com/JinyuCong/PPO-RLHF) | RLHF framework written from scratch. Actor, critic, reference and reward models, GAE, PPO-clip, KL penalty, with GPT-2 as the example policy. |
| [**GPT**](https://github.com/JinyuCong/GPT) | Decoder-only transformer in PyTorch (about 17M parameters). Pre-LN blocks, KV-cached decoding, top-k sampling, trained on Alpaca, plus a standalone BPE tokenizer. |
| [**ReinforcementLearning**](https://github.com/JinyuCong/ReinforcementLearning) | Monte Carlo, TD, Sarsa, Q-learning, DQN, REINFORCE, Actor-Critic, A2C and PPO implemented from scratch, on GridWorld, CartPole and Atari Breakout. |

### Multimodal learning

| Project | What it is |
|---|---|
| [**M3-JEPA**](https://github.com/JinyuCong/M3-JEPA) | Study and evaluation of M3-JEPA (ICML 2025, Geely AI Lab), a multi-gate MoE predictor for latent-space multimodal alignment. The method is theirs; this repository holds my reading and evaluation work. |
| [**AirbnbMultimodal**](https://github.com/JinyuCong/AirbnbMultimodal) | Superhost prediction on 79k Paris listings, combining text and tabular data. Early and late fusion, logistic regression against a mixture of experts. Best model reaches AUC 0.913. |

### Systems and engineering

| Project | What it is |
|---|---|
| [**Financial-Scraper-Agent**](https://github.com/JinyuCong/Financial-Scraper-Agent) | LLM agent that calls analysis tools (ARIMA, RSI, MACD, Bollinger) through gRPC microservices, deployed on Kubernetes with Istio and mTLS. |
| [**kubernetes-minikube**](https://github.com/JinyuCong/kubernetes-minikube) | Docker to Kubernetes walkthrough: deployment, load balancing and ingress on Minikube. |
| [**hand_written_recognition**](https://github.com/JinyuCong/hand_written_recognition) | Handwritten character OCR with LeNet, served by FastAPI behind a web canvas front end. |

### Just for the love of it

| Project | What it is |
|---|---|
| [**RayTracerChallenge**](https://github.com/JinyuCong/RayTracerChallenge) | CPU ray tracer in C# following Jamis Buck's book. Reflection, refraction, patterns, groups, OBJ meshes, parallel rendering, test-driven. |

---

## Tech stack

<p align="center">
  <a href="https://www.python.org"><img src="https://skillicons.dev/icons?i=py" width="48" alt="Python" /></a>
  <a href="https://pytorch.org"><img src="https://skillicons.dev/icons?i=pytorch" width="48" alt="PyTorch" /></a>
  <a href="https://learn.microsoft.com/dotnet/csharp/"><img src="https://skillicons.dev/icons?i=cs" width="48" alt="C#" /></a>
  <a href="https://isocpp.org"><img src="https://skillicons.dev/icons?i=cpp" width="48" alt="C++" /></a>
  <a href="https://fastapi.tiangolo.com"><img src="https://skillicons.dev/icons?i=fastapi" width="48" alt="FastAPI" /></a>
  <a href="https://www.docker.com"><img src="https://skillicons.dev/icons?i=docker" width="48" alt="Docker" /></a>
  <a href="https://kubernetes.io"><img src="https://skillicons.dev/icons?i=kubernetes" width="48" alt="Kubernetes" /></a>
  <a href="https://www.postgresql.org"><img src="https://skillicons.dev/icons?i=postgres" width="48" alt="PostgreSQL" /></a>
  <a href="https://git-scm.com"><img src="https://skillicons.dev/icons?i=git" width="48" alt="Git" /></a>
  <a href="https://www.kernel.org"><img src="https://skillicons.dev/icons?i=linux" width="48" alt="Linux" /></a>
</p>

<p align="center">
  <a href="https://huggingface.co"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" /></a>
  <a href="https://scikit-learn.org"><img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" /></a>
  <a href="https://gymnasium.farama.org"><img src="https://img.shields.io/badge/Gymnasium-0081A5?style=for-the-badge&logo=openaigym&logoColor=white" alt="Gymnasium" /></a>
  <a href="https://istio.io"><img src="https://img.shields.io/badge/Istio-466BB0?style=for-the-badge&logo=istio&logoColor=white" alt="Istio" /></a>
  <a href="https://grpc.io"><img src="https://img.shields.io/badge/gRPC-244c5a?style=for-the-badge&logo=grpc&logoColor=white" alt="gRPC" /></a>
</p>

**Languages spoken**: 中文 · English · Français

---

## Get in touch

I am happy to talk about multimodal alignment, preference optimization, or research collaboration.

E-mail: congtaotao2001@gmail.com

[![GitHub](https://img.shields.io/badge/GitHub-JinyuCong-181717?style=flat-square&logo=github)](https://github.com/JinyuCong)
