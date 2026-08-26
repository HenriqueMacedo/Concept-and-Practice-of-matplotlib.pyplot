# Concept-and-Practice-of-matplotlib.pyplot
Este repositório reúne conceitos teóricos e implementações práticas da biblioteca matplotlib.pyplot integrada a numpy, pandas, scipy.stats, statsmodels e sympy. O projeto abrange desde os fundamentos da plotagem, passando por análises estatísticas e ANOVA, integração numérica até a resposta em frequência de sistemas contínuos e discretos.


---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Python 3.x**
* **NumPy** — Operações vetoriais e cálculos matemáticos.
* **Matplotlib** — Visualização de dados e plotagem de gráficos de magnitude/fase.
* **SciPy** — Testes de hipótese estatística (`f_oneway`).
* **Statsmodels** — Análise de Variância (ANOVA modelo OLS).
* **SymPy** — Computação simbólica e derivadas analíticas.

---

## 📂 Estrutura do Repositório

```text
├── tempo-continuo/
│   └── sistemas_tempo_continuo.ipynb  # Resposta em frequência (dB/rad) - Questões 1 a 4
├── tempo-discreto/
│   └── sistemas_tempo_discreto.ipynb # Análise de frequência em Z (stem plots) - Questões 5 a 8
├── estatistica/
│   └── estatistica-e-anova.ipynb     # Testes f_oneway e ANOVA de dois fatores
├── integracao-numerica/
│   └── integracao-numerica-trapezios.ipynb # Método dos Trapézios (simples, composto e erro)
└── plotagem/
    └── plotagem-graficos.ipynb        # Exemplos e manipulação com Matplotlib
