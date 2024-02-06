# Acidentes em rodovias federais/Federal road accidents in Brazil - Periodo 2021 - 2023

No Brasil, acontecem tantos acidentes em rodovias que parece que fomos anestesiados. Constantemente, vemos os jornais noticiarem que determinado feriado foi marcado por tragédias em nossas rodovias. Também não é incomum ouvir relatos de conhecidos que presenciaram ou vivenciaram um ou mais acidentes durante uma viagem ou passeio.

# Estatísticas dos Acidentes

| Ano   | Número de Acidentes | Número de Acidentes com Vítimas Fatais | Porcentagem de Acidentes Fatais | Número de Mortos |
|-------|----------------------|----------------------------------------|---------------------------------|-------------------|
| 2021  | 64.539               | 4.664                                  | 7%                              | 5.396             |
| 2022  | 64.547               | 4.662                                  | 7%                              | 5.439             |
| 2023* | 55.464               | 4.007                                  | 7%                              | 4.633             |

**Obs**: *Até outubro de 2023

Conforme os números divulgados pela Polícia Rodoviária Federal (PRF) referentes aos acidentes em rodovias federais nos anos de 2021 até outubro de 2023, observamos uma tendência preocupante com um total significativo de acidentes e vítimas fatais.

Nota-se um comportamento muito similar nos últimos 3 anos. Parece até que as campanhas de atenção ao volante, fiscalização e manutenção das vias não surtiram efeito ou não foram implementadas corretamente.

## Objetivos

Visando isso, decidi criar um estudo usando conhecimentos e técnicas de ciência e análise de dados para auxiliar na redução de sinistros. Portanto, defini dois objetivos:

    1- Identificar as principais características que contribuem para acidentes com vítimas fatais;
    2- Criar uma variável preditiva com base estatística para estimar a probabilidade desses incidentes.

É importante ressaltar que, embora os números já tenham sido mais elevados, optei por analisar um período de 3 anos para garantir uma janela temporal adequada e trabalhar com uma volumetria de observações significativa.

# O que você encontrará neste estudo

1. **Metodologia CRISP-DM:**
    - Abordagem para o desenvolvimento de projetos de mineração de dados.

2. **Data Cleaning:**
    1. Tratamento de Missing Values.
    2. Identificação de valores nulos mascarados.

3. **Feature Engineering:**
    - Geração e correção de novas features.

4. **Análise Estatística:**
    1. Análise Exploratória.
    2. Análise Espacial.
    3. Teste de Hipóteses (Qui-Quadrado e Kolmogorov-Smirnov).
    4. Correlação.

5. **Pré-Processamento:**
    1. CatBoostEncoder.
    2. StandardScaler.

6. **Oversampling:**
    - Criação de dados sintéticos com algoritmo SMOTE.

7. **Criação de Modelos de Classificação:**
    1. Seleção de Variáveis:
        1. Seleção com Base na Correlação.
        2. SelectKBest.
    2. Modelos:
        1. Logistic Regression.
        2. K-Nearest Neighbors (KNN).
        3. Random Forest.
        4. Gradient Boosting Classifier.







