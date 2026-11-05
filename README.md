# Tratamento de Dados — Portfólio de Ciência de Dados

Projeto prático de formação e portfólio para desenvolver competências em tratamento e análise de dados, bancos de dados, inteligência artificial e automação. O domínio inicial usa uma base **sintética** de processos previdenciários, sem dados pessoais reais.

## Objetivo

Construir, passo a passo, um fluxo reproduzível que receba dados em CSV, valide e limpe a base, responda perguntas analíticas, armazene os dados em banco, gere visualizações e automatize tarefas. Cada etapa deve ser explicada com comandos para executar e exemplos da saída esperada.

## Foco

1. **Python para dados:** fundamentos, ambiente, arquivos CSV/JSON, organização de código.
2. **Manipulação e qualidade:** Pandas e NumPy; tipos, ausências, duplicidades, categorias e datas.
3. **Análise e estatística:** métricas descritivas, agrupamentos, perguntas de negócio e interpretação responsável.
4. **Banco de dados:** SQL, SQLite no começo e PostgreSQL como próximo passo; modelagem, consultas e integração Python.
5. **Visualização:** Matplotlib/Seaborn e, posteriormente, Power BI.
6. **Inteligência artificial:** fundamentos de aprendizado de máquina, validação e métricas; IA como apoio, com revisão humana.
7. **Automação e entrega:** scripts e pipelines reproduzíveis, documentação e versionamento com Git/GitHub.

## Base inicial

A trilha usa `processos_previdenciarios_demo_500.csv`, uma base demonstrativa sintética com 500 registros. Ela serve para exercícios de leitura, limpeza, análise, SQL e automação. Não representa processos reais nem deve ser usada para decisões administrativas, jurídicas ou sobre benefícios.

## Resultado esperado

Ao concluir a trilha, o repositório deverá conter:

- ambiente e dependências documentados;
- dados demonstrativos e dicionário de dados;
- scripts/notebooks executáveis e organizados por etapa;
- comandos de execução com saídas esperadas;
- análise exploratória com gráficos e conclusões verificáveis;
- banco local e consultas SQL documentadas;
- pipeline automatizado, logs e validações;
- experimentos introdutórios de IA com métricas, limitações e revisão humana;
- instruções para reproduzir o projeto em outra máquina;
- README atualizado com evidências e próximos passos.

## Etapas do roadmap

| Etapa | Tema | Entrega |
|---|---|---|
| 1 | Preparar ambiente e conhecer a base | Ambiente Python, leitura do CSV e conferência de linhas/colunas |
| 2 | Limpeza e qualidade | Relatório de ausências, duplicatas, tipos e valores fora do padrão |
| 3 | Análise exploratória | Tabelas, estatísticas, visualizações e conclusões |
| 4 | Banco de dados e SQL | Modelo inicial, carga da base e consultas úteis |
| 5 | IA aplicada com responsabilidade | Experimento simples, avaliação, limitações e revisão humana |
| 6 | Automação do fluxo | Pipeline reproduzível da leitura ao relatório |
| 7 | Portfólio e versionamento | Documentação, histórico Git e apresentação do projeto |

## Estrutura planejada

```text
.
├── data/
│   └── processos_previdenciarios_demo_500.csv
├── notebooks/
├── src/
├── sql/
├── outputs/
├── requirements.txt
└── README.md
```

A estrutura será ampliada conforme cada etapa for implementada; arquivos ainda não criados não são considerados entregas concluídas.

## Ambiente e bibliotecas

Conjunto previsto, instalado progressivamente conforme o roadmap:

- Base: Python 3, pandas, numpy, requests, python-dotenv
- Análise e gráficos: matplotlib, seaborn
- Banco de dados: SQL/SQLite (incluído no Python), SQLAlchemy; PostgreSQL e psycopg em etapa posterior
- IA/ML: scikit-learn
- Notebooks: JupyterLab ou extensão Jupyter do VS Code
- Qualidade e versionamento: pytest e Git

### Instalação inicial (Windows PowerShell)

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install pandas numpy requests matplotlib seaborn sqlalchemy scikit-learn jupyterlab python-dotenv
```

No VS Code, selecione o interpretador da pasta `.venv`. O uso de PostgreSQL será adicionado quando a etapa de banco estiver pronta.

## Como trabalhar

- Siga as etapas em ordem e marque cada entrega como concluída somente após executar e explicar o resultado.
- Em cada módulo, registre: objetivo, comando, saída observada, interpretação e limitações.
- Use apenas dados sintéticos ou devidamente anonimizados.
- Não inclua credenciais, tokens, dados pessoais ou documentos reais no Git.
- Não use classificações de IA como decisão automática; mantenha revisão humana.

## Critério de conclusão

O projeto estará apresentável quando outra pessoa conseguir configurar o ambiente, executar o pipeline do início ao fim, comparar os resultados com os exemplos documentados e entender o que os dados permitem — e não permitem — concluir.

## Próximo passo

Começar pela **Etapa 1**: verificar os arquivos disponíveis, preparar o ambiente Python e ler a base demonstrativa. Ao implementar cada atividade, adicionar aqui o comando exato e a saída esperada.

## Relação com o roadmap profissional

Este repositório é o espaço de execução do eixo **Ciência de Dados e tratamento de dados** do plano de carreira: Python/Pandas, SQL, estatística, visualização, IA aplicada, automação e portfólio. A estratégia profissional e a rotina de acompanhamento ficam na página dedicada do projeto no Notion.
