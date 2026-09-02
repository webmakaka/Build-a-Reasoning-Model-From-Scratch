# [Книга][Рашка С.] Создание рассуждающей модели (с нуля) [ENG, 2026]

<img src="./img/Build-A-Reasoning-Model-From-Scratch-Cover.webp" alt="Build A Reasoning Model (From Scratch)" height="256px" align="right">

**Оригинальные искодные коды:**  
https://github.com/rasbt/reasoning-from-scratch

<br>

**Build A Reasoning Model Scratch 1: Motivation & Code Setup**  
https://www.youtube.com/watch?v=Kh9mqTzjuEQ

<br>

```shell
$ uv sync
$ uv run python -c "import sys; print(sys.executable)"
// $ uv run jupyter lab
$ vscode .
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

В книге «Создание модели рассуждения (с нуля)» вы изучите и поймете принципы работы большой языковой модели (LLM) с функцией рассуждения.

Рассуждение — одно из наиболее важных и перспективных достижений в улучшении LLM за последнее время. Однако этот термин легко понять неправильно, если изучать его только теоретически. Поэтому книга ориентирована на практику. Процесс начнется с предобученной базовой LLM, к которой пошагово в коде будут добавлены возможности рассуждения для наглядной демонстрации механизмов работы.

Описанные методы пошагово проводят через процесс разработки собственной небольшой, но функциональной модели рассуждения в образовательных целях. Этот подход копирует методы создания крупномасштабных моделей рассуждения, таких как DeepSeek R1, GPT-5 Thinking и других. Дополнительно книга содержит код для загрузки весов существующих предобученных моделей.


<br>

### Представленная ниже ментальная модель обобщает основные методы, рассматриваемые в этой книге.

<img src="./img/mental-model.webp" alt="Build A Reasoning Model (From Scratch)" width="650px">
