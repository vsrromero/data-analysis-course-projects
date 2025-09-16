[English](./README.md) | [Português](./README-pt.md)

# Projetos do Curso de Análise de Dados

Este repositório contém todos os projetos desenvolvidos como parte do meu programa de aprendizdo em Análise de Dados.  
Cada projeto aborda um tema específico como SQL, limpeza de dados, visualização e análise exploratória.  

## Estrutura do Repositório
- [`project-01-student-mental-health/`](./project-01-student-mental-health/) → Fundamentos de SQL e consultas práticas  

## Como Usar
1. Instale o [Python 3.9+](https://www.python.org/downloads/) se ainda não estiver instalado.  
2. Clone o repositório para sua máquina local:
```git clone https://github.com/vsrromero/data-analysis-course-projects.git```
3. Navegue até a pasta do projeto desejado:
```cd data-analysis-course-projects/project-01-student-mental-health```
4. (Opcional, mas recomendado) Crie um ambiente virtual:
```
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```
5. Instale os pacotes Python necessários:

```
pip install duckdb ipykernel numpy pandas
```
6. (Recomendado para usuários do VS Code) Instale a extensão Rainbow CSV para facilitar a visualização, filtragem e manipulação de arquivos CSV, que são frequentemente utilizados nos projetos deste repositório como fontes de dados para análise exploratória, limpeza e visualização:
https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv

7. Abra o notebook Jupyter (.ipynb) no VS Code ou em qualquer ambiente Jupyter.
8. Execute as células do notebook. As consultas SQL utilizam DuckDB para consultar arquivos CSV diretamente.
8. Confira a pasta outputs/ para resultados em CSV.