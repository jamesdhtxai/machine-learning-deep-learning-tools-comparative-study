# Current Presentation Content

This file is a text snapshot of the group's current A02 presentation content.

## Opening

**Comparative Analysis of Machine Learning & Deep Learning**  
Different tools solve different parts of AI/ML. We compared where each fits.

Presented by **DL_Group_4**  
Esther Odaibo • King Owusu • Louis Delgado • Zain Ahmed

---

## Scikit-learn vs. H2O

**Louis Delgado**

Current comparison focuses on Scikit-learn as a Python machine-learning library and H2O-3 as a distributed machine-learning platform. The slide distinguishes classic ML tasks and methods, compares usability, performance, support, and scalability, and emphasizes that the tools address similar ML goals with different workflow and scale priorities.

---

## TensorFlow vs. PyTorch

**Louis Delgado**

**Starting question:** What is a tensor?  
Scalar → Vector → Matrix → Higher-dimensional tensor

Both support the same learning process: input tensors → weighted calculations → prediction → measure error → update weights.

### TensorFlow
- Google introduced and open-sourced TensorFlow in 2015.
- Designed for flexible, large-scale use from smartphones to datacenters.
- Real-world examples include Google speech recognition, Smart Reply, and Google Photos search.

### PyTorch
- Facebook AI Research released PyTorch in 2016, building on Torch.
- Designed to make tensors and neural-network calculations natural within Python.
- Used for computer vision, NLP, voice control, and text-to-speech.

### Comparison
- **Usability:** PyTorch is commonly considered more Python-friendly; TensorFlow is more structured.
- **Performance:** Both support specialized hardware; neither is universally faster.
- **Support:** Both are open source with large developer and research communities.
- **Scalability:** Both support enterprise-scale work and distributed training/production.

**What I learned:** TensorFlow and PyTorch are two frameworks for the same underlying tensor mathematics and neural-network training process.

---

## Keras vs. FastAI

**King Owusu**

### Keras
- 2015 • François Chollet (Google)
- Multi-backend ecosystem across JAX, TensorFlow, and PyTorch.
- Suited for production services, cross-platform deployment, and standardized engineering pipelines.
- Key advantage: modularity and multi-backend flexibility.

### FastAI
- 2017 • Jeremy Howard & Rachel Thomas
- Built on PyTorch.
- Suited for rapid research validation, Kaggle competitions, and fast transfer-learning MVPs.
- Key advantage: high-level abstractions and automated heuristics for fast model development.

---

## JAX vs. NumPy

**King Owusu**

### NumPy
- Created in 2006 by Travis Oliphant.
- Primarily CPU-oriented numerical computing.
- Foundation for SciPy, Pandas, Matplotlib, and Scikit-learn.
- Imperative, mutable execution model.

### JAX
- Developed in 2018 by Google Brain.
- Supports CPUs, GPUs, and TPUs through OpenXLA.
- Uses JIT compilation and automatic differentiation.
- Functional and immutable execution model.

---

## AutoGluon vs. H2O AutoML

**Starting question:** What does AutoML automate?  
Model training • tuning • ensembling • evaluation • leaderboards

### AutoGluon
- Open-sourced by AWS AI researchers in 2020.
- Strong default accuracy through feature handling, bagging, stacking, and weighted ensembles.
- Used for fast prototypes across tabular, forecasting, text, image, and multimodal work.

### H2O AutoML
- Part of the H2O-3 distributed ML platform.
- Automates model and ensemble selection across GLM, GBM, XGBoost, deep learning, and stacked ensembles.
- Used for large tabular workloads.

### Comparison
- **Usability:** AutoGluon is Python-first; H2O supports Python, R, Flow UI, and cluster setup.
- **Performance:** AutoGluon emphasizes ensemble accuracy; H2O emphasizes parallel training.
- **Support:** Both are open source; H2O also has mature enterprise products/services.
- **Scalability:** AutoGluon commonly runs on one machine/cloud instance; H2O-3 is designed for multi-node distributed data.

**Bottom line:** Choose AutoGluon for fast Python prototypes and multimodal work; choose H2O when distributed tabular scale matters.

---

## NLTK vs. spaCy

**Starting question:** How do NLP toolkits differ?

Both turn raw text into tokens, linguistic features, entities, and structured data.

### NLTK
- Created by Steven Bird and Edward Loper and introduced in 2002.
- Strong for teaching, research, corpora, and visible step-by-step NLP algorithms.
- Used for education, linguistic research, stemming, tagging, parsing, and text exploration.

### spaCy
- Released in 2015 by Explosion.
- Designed as an industrial-strength Python library for applied NLP.
- Strong integrated pipelines, trained components, Doc objects, and custom/transformer models.
- Used for search, information extraction, NER, document processing, and classification.

### Comparison
- **Usability:** NLTK exposes modular building blocks; spaCy provides a cohesive pipeline.
- **Performance:** NLTK favors readability/experimentation; spaCy is optimized for larger-volume processing.
- **Support:** NLTK has academic resources; spaCy adds models, courses, plugins, and commercial backing.
- **Scalability:** NLTK fits learning/smaller analyses; spaCy supports batching, multiprocessing, GPUs, and deployment pipelines.

---

## GitHub Copilot vs. Tabnine

**Zain Ahmed**

### GitHub Copilot
- 2021 • GitHub + OpenAI
- AI coding assistant integrated across IDEs, GitHub, chat, and agent workflows.
- Features include inline completion, chat, explanations, tests, refactoring, and multiple model choices.
- Best suited for developers already using GitHub who want broad integration and general coding assistance.

### Tabnine
- 2018 • AI code assistant
- Focuses on developer productivity, privacy, and organization-aware context.
- Features include code completion, chat, code review, personalization, and SaaS/VPC/on-prem deployment.
- Best suited for teams with strict privacy, compliance, IP, or private-deployment requirements.

Sources include GitHub Blog/Docs and Tabnine platform/privacy documentation.

---

## Hugging Face Transformers vs. OpenAI GPT-4 API

**Zain Ahmed**

### Hugging Face Transformers
- Open-source model-definition framework for pretrained transformer models.
- Large model ecosystem, customizable checkpoints, fine-tuning, and multimodal support.
- Best suited for teams needing model choice, local control, customization, research, or self-hosting.
- Scales from local systems to cloud/GPU environments managed by the user/team.

### OpenAI GPT-4 API
- 2023 • Managed cloud API
- Hosted access to a high-capability language model without managing model weights or training infrastructure.
- Best suited for fast application development involving generation, summarization, assistants, and reasoning.
- OpenAI manages model serving; developers scale through API usage with less control over model internals.

---

## Conclusion

**The best tool depends on the problem, not the popularity.**

### Purpose first
These tools are not interchangeable. Libraries, frameworks, platforms, and specialized toolkits solve different parts of the AI/ML problem.

### Tradeoffs matter
Ease of use, control, performance, support, automation, and scalability change which tool is the better fit for a project.

### Tools can work together
Many of these technologies sit at different layers of the same workflow. Choosing one does not always mean replacing the others.

### Final takeaway
**Start with the task, the data, the team, and the scale — then choose the tool.**  
Choose the problem first. Choose the tool second.
