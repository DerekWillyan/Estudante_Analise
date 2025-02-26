# Análise de Dados de Desempenho em Exames

Este repositório contém um notebook de análise de dados (`analysis.ipynb`) que explora um conjunto de dados relacionado ao desempenho de estudantes em exames. O objetivo é analisar e visualizar os dados para identificar padrões e tendências que possam ajudar a entender os fatores que influenciam o desempenho dos alunos.

## Descrição do Conjunto de Dados

O conjunto de dados utilizado neste notebook é chamado `exams.csv` e contém as seguintes colunas:

- **gender**: Gênero do estudante.
- **race/ethnicity**: Grupo étnico/racial do estudante.
- **parental level of education**: Nível de educação dos pais.
- **lunch**: Tipo de refeição (padrão ou reduzida).
- **test preparation course**: Se o estudante completou um curso de preparação para o teste.
- **math score**: Pontuação em matemática.
- **reading score**: Pontuação em leitura.
- **writing score**: Pontuação em escrita.

## Análise Realizada

O notebook realiza as seguintes etapas de análise:

1. **Importação de Bibliotecas e Carregamento dos Dados**:
   - Utiliza as bibliotecas `pandas` e `seaborn` para manipulação e visualização de dados.
   - Carrega o conjunto de dados `exams.csv`.

2. **Exploração Inicial dos Dados**:
   - Exibe as primeiras linhas do conjunto de dados.
   - Verifica a presença de valores nulos.
   - Gera estatísticas descritivas das colunas numéricas.

3. **Filtragem de Dados**:
   - Filtra os dados para incluir apenas os estudantes que foram reprovados em matemática (pontuação inferior a 60).

4. **Visualização de Dados**:
   - Cria gráficos de barras para visualizar a distribuição dos estudantes reprovados por gênero, raça/etnia, nível de educação dos pais, tipo de refeição e curso de preparação para o teste.
   - Utiliza a biblioteca `matplotlib` para gerar os gráficos.

5. **Análise de Forma dos Dados**:
   - Verifica o número total de estudantes e o número de estudantes reprovados.

6. **Filtragem Adicional**:
   - Filtra os dados para incluir apenas estudantes do sexo feminino que foram reprovados em matemática.

## Como Executar o Notebook

1. **Pré-requisitos**:
   - Python 3.x instalado.
   - Bibliotecas Python: `pandas`, `seaborn`, `matplotlib`.

2. **Instalação das Dependências**:
   ```bash
   pip install pandas seaborn matplotlib
   ```

3. **Execução do Notebook**:
   - Abra o notebook `analysis.ipynb` em um ambiente Jupyter Notebook ou JupyterLab.
   - Execute as células sequencialmente para reproduzir a análise.

## Conclusões

O notebook fornece uma visão geral do desempenho dos estudantes em exames, com foco nos fatores que podem influenciar a reprovação em matemática. As visualizações ajudam a identificar tendências e padrões que podem ser úteis para futuras análises e intervenções educacionais.

## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou novas análises, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
