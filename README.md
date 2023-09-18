# Large-scale Generative AI for Science and Engineering

In this graduate-level course, we will investigate large generative AI models for scientific and engineering problems: machine learning models that can generate outputs, such as hypotheses, designs, or simulations, based on patterns learned from scientific and engineering data. They. In more detail:

* **Generative**: The model can produce new content based on patterns and structures learned during training. In the science and engineering context, it could generate predictions about untested physical phenomena, propose new design configurations for a mechanical system, or simulate the performance of a new material, to name a few examples.
* **AI model**: It uses machine learning algorithms that the model uses to learn from data and generate outputs. These algorithms are designed to identify patterns and make predictions or decisions without being explicitly programmed to perform a specific task.
* **Large**: The model has many parameters, i.e., elements that are learned from the data during training. More parameters allow the model to learn more complex patterns, but also requires more computational resources to train and use.
* **For Science and Engineering**: Training data might include scientific articles, textbooks, lab reports, CAD models, numerical simulation data, experimental data, or any other type of data that is relevant to these fields. Training the model on this type of data equips it to generate outputs that are relevant to scientific and engineering tasks.

This course is directly relevant to the AuroraGPT project, which is developing a trillion-parameter generative AI model to be trained on Argonne's new 64,000-GPU [Aurora supercomputer](https://www.alcf.anl.gov/aurora). It also connects to the work of the Trillion Parameter Consortium, which engages researchers worldwide seeking to apply generative AI to scientific problems.

The course will take place as **CMSC 35200-1: Deep Learning Systems** in the fall quarter of 2023 at the University of Chicago, on Tuesdays and Thursdays, 3:30-4:50pm. For more information, please contact Profs [Ian Foster](mailto:foster@uchicago.edu) and [Rick Stevens](mailto:stevens@cs.uchicago.edu).
  
<!--Such models may be useful in accelerating research, generating novel hypotheses, optimizing designs, and much more.-->

## Topics

We will study theoretical underpinnings of such models, their training paradigms, and applications. 
We will explore how these models can generate new data that are statistically similar to their training data, including text, images, and potentially more abstract representations, and how this capacity can be harnessed for scientific discovery and engineering solutions.
Key topics include:
*	Fundamentals of machine learning and deep learning
*	Overview of large-scale generative models
*	Deep dive into generative models like GPTs, GANs, VAEs
*	Training and fine-tuning strategies for generative models
*	Use cases of generative AI in various scientific fields like physics, chemistry, and biology, and in engineering disciplines such as materials science and electrical engineering
*	Practical sessions on implementation of these models with popular deep learning frameworks
*	Exploration of the limitations and ethical considerations of using AI in science and engineering
  
By the end of the course, students will have an understanding of how to implement and use generative AI models, how to apply them to problems in science and engineering, and how to navigate the ethical considerations that arise with the use of AI in these fields.


## Practical 

We will spend much time reading and discussing key papers in this area. In addition, the course will have a strong practical component, with students working to train models, apply them to science and engineering problems, evaluate their performance, etc. Initial ideas of things to cover:
* Experiment with use of LLMs for simple scientific problems.
* LLM definition and training: Define and train a small LLM from scratch.
* Fine-tuning/specialization for various tasks.
* Extend AutoGPT or similar for a scientific problem.


## *Potential* topics with relevant readings

(A work in progress!)

### Concepts 

* [A jargon-free explanation of how AI large language models work](https://arstechnica.com/science/2023/07/a-jargon-free-explanation-of-how-ai-large-language-models-work/), Timothy Lee and Sean Trott, 7/31/2023
* [On the Opportunities and Risks of Foundation Models](https://arxiv.org/pdf/2108.07258.pdf?utm_source=morning_brew), Rishi Bommasan et al., 2020.
* [4 Charts That Show Why AI Progress Is Unlikely to Slow Down](https://time.com/6300942/ai-progress-charts/), Time, August 2, 2023.

### State of the art in large language models

* test [rick, need to add. Attention paper, GPT-3 and GPT-4 paper, Claude Paper, Falcon and Llama 2 papers]

### Scientific discovery and AI

* [Scientific discovery in the age of artificial intelligence](https://www.nature.com/articles/s41586-023-06221-2), Hanchen Wang et al., 2023.

### Training data considerations

* [The Pile: An 800GB Dataset of Diverse Text for Language Modeling](https://arxiv.org/pdf/2101.00027.pdf), Leo Gao et al., 2020.
* [The RefinedWeb Dataset for Falcon LLM: Outperforming Curated Corpora with Web Data, and Web Data Only](https://arxiv.org/pdf/2306.01116.pdf), Guilherme Penedo et al., 2023.
* [Textbooks Are All You Need](https://arxiv.org/pdf/2306.11644.pdf), Suriya Gunasekar et al., 2023.

### Scaling 

* [Scaling TransNormer to 175 Billion Parameters](https://arxiv.org/pdf/2307.14995.pdf), Zhen Qin et al., 2023.
* TBD

### Model Evaluation

*  EluetherAI -- Evaluation harness
*  HELM paper
*  BIG paper
*  Elo cmparison and HF leaderboard

### Reinforcement Learning with Human Feedback

* [Llama Adapter] https://arxiv.org/pdf/2303.16199.pdf
*  [Open Problems and Fundamental Limitations of Reinforcement Learning from Human Feedback](https://arxiv.org/pdf/2307.15217.pdf), Stephen Casper et al., 2023.
* [DeepSpeed-Chat: Easy, Fast and Affordable RLHF Training of ChatGPT-like Models at All Scales](https://arxiv.org/pdf/2308.01320.pdf), Zhewei Yao et al., 2023.


### Memorization and copyright protection

* [On Provable Copyright Protection for Generative Models](https://arxiv.org/pdf/2302.10870.pdf), Nikhil Vyas et al., 2023.
* [Emergent and Predictable Memorization in Large Language Models](https://arxiv.org/pdf/2304.11158.pdf), Stella Biderman et al., 2023.
* [Speak, Memory: An Archaeology of Books Known to ChatGPT/GPT-4](https://arxiv.org/pdf/2305.00118v1.pdf), Kent K. Chang et al., 2023.

### Applications in chemistry and materials science

* [Generative Models as an Emerging Paradigm in the Chemical Sciences](https://pubs.acs.org/doi/10.1021/jacs.2c13467), Dylan M. Anstine et al., 2023.
* [GPT-4 Reticular Chemist for MOF Discovery](https://arxiv.org/abs/2306.14915) and [ChatGPT Chemistry Assistant for Text Mining and Prediction of MOF Synthesis](https://arxiv.org/pdf/2306.11296.pdf), Zhiling Zheng et al., 2023.
* [ChatMOF: An Autonomous AI System for Predicting and Generating Metal-Organic Frameworks](https://arxiv.org/abs/2308.01423), Yeonghun Kang et al., 2023.

### Optimizations

* [QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/pdf/2305.14314.pdf), Tim Dettmers et al., 2023.

### Autonomous LLM-based agents

* [Auto-GPT: An Autonomous GPT-4 Experiment](https://github.com/Significant-Gravitas/Auto-GPT)
* [ChemCrow: Augmenting large-language models with chemistry tools](https://arxiv.org/abs/2304.05376), Andres Bran et al., 2023.

### Robotics

* [RoboCat: A Self-Improving Foundation Agent for Robotic Manipulation](https://arxiv.org/pdf/2306.11706.pdf), Konstantinos Bousmalis et al., 2023.

### Risks

* [Can large language models democratize access to dual-use biotechnology?](https://arxiv.org/pdf/2306.03809.pdf), Emily Soice et al., 2023.
* [Harms from Increasingly Agentic Algorithmic Systems](https://arxiv.org/pdf/2302.10329.pdf), Alan Chan et al., 2023.

### Tabular data

* [TabR: Unlocking the Power of Retrieval-Augmented Tabular Deep Learning](https://arxiv.org/pdf/2307.14338.pdf), Yury Gorishniy et al., 2023

### Limitations

* [Reclaiming AI as a theoretical tool for cognitive science](https://psyarxiv.com/4cbuv), Iris van Rooij et al. (2023).

## Tools

* [minGPT](https://github.com/karpathy/minGPT) with [accompanying video](https://www.youtube.com/watch?v=kCc8FmEb1nY).
* [Dive into Deep Learning](http://d2l.ai) -- online textbook with notebooks.
* [ChatALL: Chat with ALL AI Bots Concurrently, Discover the Best](https://github.com/sunner/ChatALL)

This site is accessible at [https://tpc-ai.github.io/genAI-SE/](https://tpc-ai.github.io/genAI-SE/).

##  A four-stage path to creating a LLM for science

1. **Scientific Data Acquisition and Organization**: Robust data lies at the heart of any sophisticated model. Thus we first must curate large-scale scientific datasets, designing approximately 20 specialized “bundles” across domains like biology/biochemistry, materials/chemistry, physics/cosmology, and climate/environment. By addressing gaps in existing large language models (LLMs) tailored for intricate scientific challenges, our data collection aims to be highly targeted and efficient, enhancing the overall capabilities of our models.

1. **Model Evaluation Suite Development**: With the curated data in place, the second phase centers on constructing expansive model evaluation suites. These suites, tailored to specific dataset collections and subdomains, will validate data and lay the groundwork for model testing. We plan on utilizing current LLMs to shape problems that AuroraGPT can solve, targeting around 1,000 problems for each scientific subdomain, resulting in an infrastructure ready to evaluate models on a staggering 20,000 problem sets.

1. **Model Construction and Performance Analysis**: This pillar is about breathing life into our data through model building. We aim to construct models across diverse scales, from 7B to 1000B, leveraging general texts, code, and niche scientific data. Rigorous testing will be conducted on elite supercomputers Polaris and Aurora, ensuring optimal performance. The setup will harness technologies like [Megatron](https://github.com/NVIDIA/Megatron-LM) and [DeepSpeed](https://github.com/microsoft/DeepSpeed) to determine the best strategies for parallelism and fine-tuning hardware choices.

1. **Model Refinement and Deployment**: The final phase ensures that our models do not just exist but also thrive in real-world applications. Refinement processes will utilize post-processing tools such as “instruct,” “RLHF,” and “Chat” and might employ pipelines like [DeepSpeed RLHF](https://github.com/microsoft/DeepSpeed/blob/master/blogs/deepspeed-chat/README.md) or Alpaca. Automation will be a focus, especially for post-processing and safety checks. As the finishing touch, we plan on launching a Web and API platform for internal testing of AuroraGPT at Argonne before its broader release.

