# Algoritmos de Busca Heurística e IA

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Colab](https://img.shields.io/badge/Google%20Colab-Compatible-F9AB00.svg?logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 📖 Visão Geral

Repositório focado em algoritmos de busca no espaço de estados, busca informada (A*), teoria dos jogos, árvores de decisão adversariais (Minimax) e estratégias de exploração em grafos.

Este repositório reúne projetos práticos desenvolvidos com foco em engenharia de dados e inteligência artificial, demonstrando desde fundamentos teóricos até implementações práticas com validação experimental e métricas salvas.

---

## 🌟 Destaques do Portfólio

### 🔹 [Busca Heurística A* (A-Star)](./01_busca_heuristica_a_star.ipynb)
Implementação do algoritmo A* utilizando fila de prioridades (`heapq`), cálculo da função de avaliação f(n) = g(n) + h(n) e garantia de otimalidade com heurísticas admissíveis.

- **Stack:** `Python` `heapq` `Algoritmos Heurísticos`
- **Notebook:** [`01_busca_heuristica_a_star.ipynb`](./01_busca_heuristica_a_star.ipynb)

### 🔹 [Planejamento de Rotas na Romênia (Busca Gulosa e A*)](./02_busca_heuristica_rotas.ipynb)
Resolução do clássico problema do mapa da Romênia (Russell & Norvig), comparando busca gulosa de melhor escolha (Greedy Best-First) contra A* com distâncias em linha reta.

- **Stack:** `Python` `Grafos` `Modelagem Espacial`
- **Notebook:** [`02_busca_heuristica_rotas.ipynb`](./02_busca_heuristica_rotas.ipynb)

### 🔹 [Tomada de Decisão Adversarial com Algoritmo Minimax](./04_algoritmo_minimax_decisao.ipynb)
Árvore de decisão para jogos de soma-zero com avaliação recursiva de utilidade máxima e mínima entre agentes adversariais.

- **Stack:** `Minimax` `Teoria dos Jogos` `NumPy`
- **Notebook:** [`04_algoritmo_minimax_decisao.ipynb`](./04_algoritmo_minimax_decisao.ipynb)

### 🔹 [Agente Autônomo para Jogo da Velha](./05_jogo_da_velha_minimax.ipynb)
Implementação completa de tabuleiro e agente inteligente com função de avaliação heurística ponderada por controle de centro e diagonais.

- **Stack:** `Game AI` `Funções Heurísticas` `NumPy`
- **Notebook:** [`05_jogo_da_velha_minimax.ipynb`](./05_jogo_da_velha_minimax.ipynb)

---

## 📑 Catálogo de Projetos (7 notebooks)

| Notebook | Descrição & Objetivo | Tecnologias | Tamanho |
| :--- | :--- | :--- | :---: |
| [`01_busca_heuristica_a_star.ipynb`](./01_busca_heuristica_a_star.ipynb) | Algoritmo de Busca Heurística A* com fila de prioridades | `heapq` | 3.8 KB |
| [`02_busca_heuristica_rotas.ipynb`](./02_busca_heuristica_rotas.ipynb) | Planejamento de rotas e busca heurística informada | `heapq` | 9.9 KB |
| [`03_algoritmos_grafos_busca_ia.ipynb`](./03_algoritmos_grafos_busca_ia.ipynb) | Grafos e algoritmos de busca em profundidade (DFS) e largura (BFS) | `heapq` | 32.4 KB |
| [`04_algoritmo_minimax_decisao.ipynb`](./04_algoritmo_minimax_decisao.ipynb) | Tomada de decisão adversarial em jogos com algoritmo Minimax | `NumPy` | 5.7 KB |
| [`05_jogo_da_velha_minimax_v1.ipynb`](./05_jogo_da_velha_minimax_v1.ipynb) | Agente inteligente para Jogo da Velha com busca heurística (v1) | `NumPy, Random` | 31.7 KB |
| [`05_jogo_da_velha_minimax_v2.ipynb`](./05_jogo_da_velha_minimax_v2.ipynb) | Agente inteligente para Jogo da Velha com busca heurística (v2) | `NumPy, Random` | 34.6 KB |
| [`06_busca_competitiva_ambientes.ipynb`](./06_busca_competitiva_ambientes.ipynb) | Estratégias de busca competitiva em ambientes multiagentes | `NumPy` | 2.0 KB |

---

## 🚀 Como Executar Localmente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/VictorSilvaCamargo/ia-algoritmos-de-busca.git
   cd ia-algoritmos-de-busca
   ```
2. **Crie e ative um ambiente virtual:**
   ```bash
   python -m venv venv
   # Windows:
   .\venv\Scripts\activate
   # Linux/macOS:
   source venv/bin/activate
   ```
3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Inicie o Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

---

## 👨‍💻 Autor

**Victor Silva Camargo**  

Cientista da Computação | Desenvolvedor FullStack | Engenheiro de Machine Learning  

GitHub: [@VictorSilvaCamargo](https://github.com/VictorSilvaCamargo)

