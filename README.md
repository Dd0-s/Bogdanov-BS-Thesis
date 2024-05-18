| Название исследуемой задачи | Применение стохастической аппроксимации нулевого порядка с техникой запоминания в алгоритме Франка-Вульфа |
| :---: | :---: |
| Тип научной работы | Баколаврский диплом |
| Автор | Богданов Александр Иванович |
| Научный руководитель | к.ф.-м.н. Безносиков Александр Николаевич |

# Description

This paper explores a convex optimization problem is based on a bound set with access only to the null oracle. To solve this problem, I suggest a modification of JAGUAR is proposed that use gradient approximation to calculate the conditional gradient.

# Installation

- Second way
1. `git clone` this repository.
2. Create new `conda` environment and activate it
3. Run 
```bash
pip install -r requirements.txt
pip install ipykernel
python -m ipykernel install --user --name <env_name> --display-name <env_name>
```

# Content

This repository provides code for reproducing experiments that were performed as part of scientific work in the fall semester of 2023. If you run [Experiments.ipynb](https://github.com/intsystems/Bogdanov-BS-Thesis/blob/main/code/Experiments.ipynb) in the code directory, you will reproduce the experimental results obtained in the article. 

![JAGUAR](./code/figures/Non-stochastics.png)

