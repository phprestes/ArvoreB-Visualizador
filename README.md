# Visualizador de Árvore B

Visualizador de Árvore B em Python, para a disciplina **SCC0215 - Organização de Arquivos** (ICMC-USP). Lê o arquivo binário do índice e desenha a árvore.

<p align="center">
  <img alt="Disciplina" src="https://img.shields.io/badge/SCC0215-Organiza%C3%A7%C3%A3o%20de%20Arquivos-blue?style=for-the-badge">
  <img alt="Instituição" src="https://img.shields.io/badge/ICMC--USP-Universidade%20de%20S%C3%A3o%20Paulo-orange?style=for-the-badge">
</p>

> **Disciplina:** SCC0215 - Organização de Arquivos <br>
> **Professor(a):** Cristina Dutra de Aguiar <br>
> **Instituição:** ICMC-USP - Universidade de São Paulo

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/NetworkX-2C6E9B?style=for-the-badge" alt="NetworkX" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Graphviz-1C1C1C?style=for-the-badge" alt="Graphviz" />
</p>

## Requisitos

- **Python 3** (recomendado em um ambiente virtual)
- **Graphviz** e seus arquivos de desenvolvimento
- Pacotes de `requirements.txt` (`matplotlib`, `networkx`, `pygraphviz`, entre outros)

## Como Executar

Instalar as dependências:

```bash
sudo apt-get install graphviz graphviz-dev
pip install -r requirements.txt
```

Rodar com o arquivo binário da sua árvore B:

```bash
python3 arvere.py nome_do_arquivo_da_sua_arvore_b.bin
```

O repositório inclui `indiceAtaques10.bin` como exemplo.

## Estrutura do Projeto

- `arvere.py`: leitura do arquivo binário e desenho da árvore.
- `requirements.txt`: dependências Python.
- `indiceAtaques10.bin`: exemplo de índice em árvore B.

## Funcionalidades Implementadas

Nós coloridos por tipo:

- **Vermelho:** raiz
- **Azul:** intermediário
- **Verde:** folha

Observação: os nós **não** são plotados na ordem dos ponteiros. Eles aparecem na ordem do arquivo binário, de cima para baixo. Confira manualmente se os ponteiros estão na ordem correta.
