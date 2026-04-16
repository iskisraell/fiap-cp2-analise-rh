# Análise de Dados de Recursos Humanos

**FIAP** | **Professor:** Luciana | **Turma:** TIAPZ  
**Disciplina:** Computational Thinking with Python

---

## Equipe

| Nome | RM |
|------|-----|
| Giovanni Henrique Pereira Hessel | 570574 |
| Suellen Pereira da Silva | 573862 |
| Arthur Zeferino | 570858 |
| Israel Carneiro de Toledo | 573854 |
| Luan Gonçalves de Freitas | 571935 |

---

## Sobre o Projeto

Este repositório contém a atividade prática (CP2) da disciplina de Computational Thinking with Python da FIAP. O projeto consiste em uma análise exploratória de dados de Recursos Humanos, utilizando o dataset **HRDataset_v14** com informações de 311 funcionários.

## Estrutura do Notebook

O notebook está organizado em **8 exercícios indexados**, progressivos em complexidade:

| Exercício | Tópico |
|-----------|--------|
| 1 | Reconhecimento estrutural e inspeção da base de dados |
| 2 | Lógica de classificação com if/elif/else e funções |
| 3 | Uso de funções lambda e filtragem com Pandas |
| 4 | Análises agregadas e ranking |
| 5 | Classificação sofisticada com múltiplas variáveis |
| 6 | Análise de amostragem e variabilidade |
| 7 | Identificação de padrões e achados |
| 8 | Conclusão |
| 24 | Análise de correlação entre variáveis |
| 25 | Análise de distribuição e outliers |

## Base de Dados

- **Dataset:** HRDataset_v14.csv
- **Registros:** 311 funcionários
- **Colunas:** 36 atributos

### Principais Colunas

- `Employee_Name` - Nome do funcionário
- `Salary` - Salário
- `Department` - Departamento
- `EmploymentStatus` - Status de employment
- `ManagerID` - ID do gerente
- `PerformanceScore` - Pontuação de desempenho
- `EngagementSurvey` - Pesquisa de engajamento (0-5)
- `EmpSatisfaction` - Satisfação do funcionário (1-5)

## Dependências

```
pip install pandas numpy matplotlib seaborn kagglehub
```

| Pacote | Uso |
|--------|-----|
| `pandas` | Manipulação de dados (DataFrames, filtros, groupby) |
| `numpy` | Operações numéricas (np.where, quantis) |
| `matplotlib` | Gráficos (boxplot) |
| `seaborn` | Heatmap de correlação |
| `kagglehub` | Download automático do dataset |

## Como Executar

1. Clone o repositório
2. Instale as dependências: `pip install pandas numpy matplotlib seaborn kagglehub`
3. Abra o arquivo `CP2-Luciana-Python-Analise-RH.ipynb` no Jupyter ou Google Colab
4. Execute as células sequencialmente

---

**FIAP** - Computational Thinking with Python