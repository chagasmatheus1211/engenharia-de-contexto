
# 🌍 Smart Simulators: Análise Ambiental e Lógica de Evacuação

[![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Projeto-Acadêmico-orange?style=for-the-badge)](https://github.com/chagasmatheus1211/portfolio-matheus-chagas-mauriz-coque)

## 📝 Descrição do Projeto

Este repositório reúne algoritmos de simulação desenvolvidos em Python para modelagem de cenários e análise de indicadores ambientais. O projeto trabalha com duas áreas principais: **segurança civil por meio de simulações de evacuação** e **sustentabilidade urbana através da análise de microclima e qualidade do ar**.

Os sistemas utilizam lógica de estados, estruturas de dados e processamento de informações para avaliar condições ambientais e simular o comportamento de indivíduos em situações com restrições.

## ⚙️ Módulos do Sistema

### 🌡️ 1. Monitor de Microclima e Conforto Térmico

Módulo responsável por processar dados de diferentes pontos geográficos, como praças e cruzamentos, para calcular indicadores de conforto ambiental.

- 🌬️ **Classificação da Qualidade do Ar (IQA):** categoriza a qualidade do ar em níveis que vão de “Boa” a “Muito Ruim”, utilizando estruturas `match/case`.
- 🌡️ **Cálculo de Conforto Térmico:** ajusta a pontuação de conforto conforme a variação em relação à temperatura ideal de 25 °C, à umidade e à poluição.
- 🕒 **Análise Temporal:** compara dados coletados em diferentes horários para identificar mudanças nas condições ambientais de um mesmo local.

### 🚪 2. Simulador de Evacuação de Ambientes

Simulador baseado em estados que representa a saída de um indivíduo de um edifício com obstáculos e caminhos restritos.

- 🔑 **Gestão de Inventário:** coleta e utiliza itens, como chaves, para liberar caminhos bloqueados.
- ⚡ **Controle de Energia:** encerra a simulação quando o limite de tentativas é ultrapassado.
- 🧭 **Lógica de Navegação:** gerencia a posição do indivíduo em uma lista dinâmica de locais, permitindo retornar quando há obstáculos.

## 🚀 Tecnologias Utilizadas

- 🐍 **Linguagem:** Python 3.10
- 💻 **Ambientes de execução:** Google Colab e Jupyter Notebook
- 🧠 **Conceitos:** máquina de estados finitos, listas, matrizes multidimensionais e lógica condicional.

## 📊 Regras de Negócio e Aprendizados

O desenvolvimento dos módulos permite praticar conceitos importantes de lógica de programação e engenharia de software:

- 📏 **Validação de Dados:** mantém a pontuação de conforto dentro do intervalo de 0 a 10.
- 🔄 **Persistência de Estado:** utiliza listas de inventário para influenciar decisões e etapas futuras de um laço `while`.
- 🛡️ **Segurança na Navegação:** verifica os limites dos índices para evitar erros de acesso a posições inexistentes em listas.
- 🔀 **Controle de Fluxo:** aplica condições e mudanças de estado para determinar as ações permitidas durante cada simulação.

## 🔧 Como Executar

### 📋 Pré-requisitos

- Python 3.10 ou superior.
- Editor de código ou ambiente compatível com Python.

### ▶️ Passo a Passo

**1. Clone o repositório**

```bash
git clone https://github.com/SEU-USUARIO/smart-simulators.git
```

**2. Acesse a pasta do projeto**

```bash
cd smart-simulators
```

**3. Execute o analisador de clima**

```bash
python untitled3.py
```

**4. Execute o simulador de evacuação**

```bash
python untitled4.py
```

> 💡 Caso esteja utilizando o Google Colab ou Jupyter Notebook, abra os arquivos correspondentes e execute as células de código.

## 📂 Estrutura do Projeto

```text
smart-simulators/
├── README.md
├── untitled3.py
└── untitled4.py
```

- 📘 `README.md`: documentação e instruções de execução.
- 🌡️ `untitled3.py`: módulo de análise ambiental e conforto térmico.
- 🚪 `untitled4.py`: módulo de simulação de evacuação.

## 💻 Acesse o Projeto

🐍 **[Visualizar código-fonte — Analisador de Clima (main1.py)](main1.py)**

🐍 **[Visualizar código-fonte — Simulador de Evacuação (main2.py)](main2.py)**

## 👤 Autor

**Matheus Chagas Mauriz Coque**

🎓 Estudante de Engenharia de Software

- 💼 [LinkedIn](https://www.linkedin.com/in/matheus-chagas-coque-b190ba39b/)
- 🐙 [GitHub](https://github.com/chagasmatheus1211)
- 📧 [E-mail](mailto:chagasmatheus1211@gmail.com)

---

⭐ *Projeto acadêmico com foco em simulação de cenários, análise ambiental, estruturas de dados e lógica de programação.*

⬅️ **[Voltar ao portfólio principal](https://github.com/chagasmatheus1211/portfolio-matheus-chagas-mauriz-coque/tree/main)**
