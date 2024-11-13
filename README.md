### Exploração de Metiloma de Tumores de Córtex Adrenal

**Nome:** Luís Eduardo Cruvinel Pinto  
**Data:** 14/11/2024

## Descrição

Este projeto utiliza dados do banco de dados público _Gene Expression Omnibus GSE179175_, gerados pelo laboratório de endocrinologia do Hospital de Clínicas da FMRP. O objetivo é aplicar as técnicas de machine learning apresentadas na disciplina para fazer a exploração do metiloma de 57 amostras de Tumor de Córtex Adrenal pediátrico e correlacionar com desfechos clínicos, com finalidade estritamente didática.

## Bibliotecas Utilizadas

- `pandas` 1.3.3
- `numpy` 1.21.2
- `matplotlib` 3.4.3
- `seaborn` 0.11.2
- `scipy` 1.7.1
- `scikit-learn` 0.24.2

## Estrutura do Projeto

- `projeto_intro_ciencia_de_dados.ipynb`: Notebook contendo o código e as análises realizadas.
- `GSE179175_Matrix-processed-Mvalues.csv`: Arquivo contendo os valores M obtidos do preprocessamento dos dados (arquivo público)
- `raw_clinical.csv`: Arquivo contendo os dados clínicos das amostras
- `infinium-methylationepic-v-1-0-b5-manifest-file.csv`: Manifesto do ensaio EPICv1 da Illumina, utilizado para análise dos dados de metilação de DNA das amostras

### Disclaimer: O projeto é apenas didático e não deve ser interpretado como relevante clinicamente
