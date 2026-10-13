<div align="center">

# Jinyu Cong · 丛津宇

**Master's student in Machine Learning for Data Science · Université Paris Cité**
Multimodal LLMs · Preference alignment (RLHF / DPO) · Generative recommendation

<img src="https://img.shields.io/badge/Paris-France-1f2937?style=flat-square" alt="Paris" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />

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

**ML**: PyTorch · Hugging Face Transformers · scikit-learn · Gymnasium
**Languages**: Python · C# · Java · JavaScript
**Infra**: Docker · Kubernetes · Istio · gRPC · FastAPI · PostgreSQL
**Languages spoken**: 中文 · English · Français

---

## Get in touch

I am happy to talk about multimodal alignment, preference optimization, or research collaboration.

[![GitHub](https://img.shields.io/badge/GitHub-JinyuCong-181717?style=flat-square&logo=github)](https://github.com/JinyuCong)

<div align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JinyuCong&layout=compact&hide_border=true&langs_count=6" alt="Top languages" />
</div>
