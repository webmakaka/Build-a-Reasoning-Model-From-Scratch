# [Книга][Рашка С.] Build A Reasoning Model (From Scratch) [ENG, 2026]

<img src="./img/Build-A-Reasoning-Model-From-Scratch-Cover.webp" alt="Build A Reasoning Model (From Scratch)" height="256px" align="right">

**Оригинальные искодные коды:**  
https://github.com/rasbt/reasoning-from-scratch

<br>

**Build A Reasoning Model Scratch 1: Motivation & Code Setup**  
https://www.youtube.com/watch?v=Kh9mqTzjuEQ

<br>

```shell
$ uv sync
$ uv run jupyter lab
```

<br>

```python
import sys

sys.prefix
sys.executable
```

<br>

```python
import torch

torch.__version__
torch.cuda.is_available()
torch.mps.is_available()
```

<br>

In Build a Reasoning Model (From Scratch), you will learn and understand how a reasoning large language model (LLM) works.

Reasoning is one of the most exciting and important recent advances in improving LLMs, but it’s also one of the easiest to misunderstand if you only hear the term reasoning and read about it in theory. This is why this book takes a hands-on approach. We will start with a pre-trained base LLM and then add reasoning capabilities ourselves, step by step in code, so you can see exactly how it works.

The methods described in this book walk you through the process of developing your own small-but-functional reasoning model for educational purposes. It mirrors the approaches used in creating large-scale reasoning models such as DeepSeek R1, GPT-5 Thinking, and others. In addition, this book includes code for loading the weights of existing, pretrained models.

<br>

### The mental model below summarizes the main techniques covered in this book.

<img src="./img/mental-model.webp" width="650px">
