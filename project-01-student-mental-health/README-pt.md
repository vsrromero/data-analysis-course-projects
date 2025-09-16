[English](./README.md) | [Português](./README-pt.md)

# Projeto 01 – Análise da Saúde Mental de Estudantes

## Descrição do Projeto
Ir para a universidade em um país diferente afeta sua saúde mental?  
Uma universidade internacional no Japão pesquisou seus estudantes em 2018 e publicou um estudo no ano seguinte, aprovado por vários conselhos éticos e regulatórios.  

O estudo concluiu que estudantes internacionais têm maior risco de dificuldades de saúde mental do que a população em geral, e que a **conexão social** (pertencer a um grupo social) e o **estresse de aculturação** (estresse associado a entrar em uma nova cultura) são fatores preditivos de depressão.  

Neste projeto, exploramos o conjunto de dados `students` usando PostgreSQL para investigar se chegamos a uma conclusão semelhante para estudantes internacionais e avaliar se o **tempo de permanência** é um fator que contribui.  

---

## Instruções do Projeto
- Explorar e analisar os dados de `students` para verificar como o **tempo de permanência (stay)** impacta as médias dos escores de diagnósticos de saúde mental dos estudantes internacionais.  
- Retornar uma tabela com **nove linhas e cinco colunas**.  
- As cinco colunas devem ter os aliases:  
  - `stay`  
  - `count_int` (número de estudantes internacionais por tempo de permanência)  
  - `average_phq` (média do teste PHQ-9 de depressão)  
  - `average_scs` (média do teste SCS de conexão social)  
  - `average_as` (média do teste ASISS de estresse de aculturação)  
- Arredondar as médias para **duas casas decimais**.  
- Ordenar os resultados por `stay` em **ordem decrescente**.  
- ⚠️ Importante: A solução final deve usar o DataFrame chamado **`df`** (renomeá-lo causará erro na validação).  

---

## Dicionário de Dados

| Campo           | Descrição                                           |
| --------------- | --------------------------------------------------- |
| `inter_dom`     | Tipo de estudante (internacional ou doméstico)      |
| `japanese_cate` | Proficiência na língua japonesa                     |
| `english_cate`  | Proficiência na língua inglesa                      |
| `academic`      | Nível acadêmico atual (graduação ou pós-graduação)  |
| `age`           | Idade atual do estudante                            |
| `stay`          | Tempo de permanência atual em anos                  |
| `todep`         | Pontuação total do teste de depressão (PHQ-9)       |
| `tosc`          | Pontuação total do teste de conexão social (SCS)    |
| `toas`          | Pontuação total do teste de estresse de aculturação (ASISS) |

---

## Habilidades Desenvolvidas
- Escrever queries SQL em PostgreSQL  
- Usar funções agregadas (`COUNT`, `AVG`, `ROUND`)  
- Agrupar dados com `GROUP BY`  
- Aplicar ordenação e alias em SQL  
- Interpretar dados no contexto de pesquisas em saúde mental  

## Conclusão
A análise indica que a adaptação social e cultural é crucial para a saúde mental de estudantes internacionais. As médias de depressão (PHQ) e de estresse de aculturação (AS) não diminuem de forma linear com o tempo de estadia, e a conectividade social (SCS) não melhora automaticamente ao longo do tempo. Esses resultados sugerem que o tempo de estadia por si só não é suficiente para prever o bem-estar mental, e que a integração social desempenha um papel fundamental no apoio à saúde mental dos estudantes no exterior.