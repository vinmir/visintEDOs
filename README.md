# visintEDOs
Projeto de modelagem computacional de sistemas dinâmicos acoplados utilizando NumPy e Matplotlib. A simualção é interativa, ou seja, os parâmetros iniciais para cada sistema são escolhidos com um clique ẽm qualquer região do quiver plot.

# Requisitos
+ Python: Matplotlib, Numpy e Jupyter (Lab)
  + Utilizo Anaconda 2021+ em todos os meus projetos de desenolvimento Python. Esta distribuição atutomaticamente inclui a maior parte das bibliotecas de *Python científico*.

# Imagens
GIFs gravados com `byzanz` e `xwininfo`.
## $\dot{x} = -x,\quad \dot{y} = -y$
![fig_1](https://github.com/vinmir/visintEDOs/assets/133194350/ff72169e-f15f-4f71-a746-7890087311f8)

## $\dot{x} = x,\quad \dot{t} = 1$
![fig_2](https://github.com/vinmir/visintEDOs/assets/133194350/2d0ae03e-3539-42ae-8784-7d7da29af2d0)

## $\dot{x} = x - x^2,\quad \dot{t} = 1$
![fig_3](https://github.com/vinmir/visintEDOs/assets/133194350/4ea203c2-6743-4ca8-a608-6ce0a81f00a8)

## Lotka-Volterra: $\dot{x} = x - xy,\quad \dot{y} = -y + xy$
![fig_4](https://github.com/vinmir/visintEDOs/assets/133194350/69521769-26a7-4c5a-8dbf-d0cc18f23666)

## $\dot{x} = y,\quad \dot{y} = -x$
![fig_5](https://github.com/vinmir/visintEDOs/assets/133194350/c64c6108-3c00-4aac-9d82-eebc28d031d4)

## $\dot{x} = y,\quad \dot{y} = -x -0.4y$
![fig_6](https://github.com/vinmir/visintEDOs/assets/133194350/3152072c-06a2-42ff-aa0f-c51c6168c0d5)

# Referências
+ [Visualizing the 'Content' of Differential Equations (CDT-16)](https://www.researchgate.net/publication/336839290_Visualizing_the_%27Content%27_of_Differential_Equations_CDT-16)
  + Este texto trata de material complementar que apenas discute os diferentes sistemas dinâmicos. Todas as visualizações e simulações interativas presentes neste projeto são de autoria própria.
