
# Projeto de Reconhecimento de Letras com MLP

## Integrantes
- Ana Clara das Neves Barreto
- Eloisa Antero Guisse
- Jamyle Gonçalves Rodrigues Silva
- Lucca Pinto
- Marcos Martins de Oliveira Pacheco
- Sarah Klock Mauricio

## Sobre o Projeto
Este repositório contém os notebooks e dados para um projeto de classificação de letras usando redes neurais do tipo Multilayer Perceptron (MLP). O projeto foi desenvolvido como parte do curso de Inteligência Artificial na Universidade de São Paulo (USP), com o objetivo de explorar e visualizar o comportamento de redes neurais em tarefas de classificação simples.

## Estrutura do Repositório
- **ep_ia_mlp.ipynb**: Implementação do MLP.
- **analises.ipynb**: Análise dos resultados do modelo.
- **pesos_salvos.txt**: Pesos salvos do MLP, utilizáveis sem necessidade de re-treino.
- **X.txt**: Dados de entrada para treino e teste.
- **Y_letra.txt**: Classes correspondentes aos dados de entrada.
- **csvs**:
  - **grid_search_results.csv**: Resultados de grid search para hiperparâmetros.
  - **com_dois.csv**: Dados com inicialização Xavier e momentum.
  - **com_momentum.csv**: Dados com momentum, sem Xavier.
  - **com_xavier.csv**: Dados com Xavier, sem momentum.
  - **sem_nada.csv**: Dados sem Xavier e sem momentum.
  - **learning_rates.csv**: Dados variando taxas de aprendizado.
  - **proporcao_conjunto_teste.csv**: Dados variando proporções do conjunto de teste.

## Instalação
Para configurar seu ambiente para executar os notebooks, siga estas instruções:
1. Clone o repositório.
2. Instale as dependências usando `pip install -r requirements.txt`.

## Como Usar
Para utilizar os notebooks, simplesmente execute cada célula em ordem. Os notebooks estão comentados para facilitar o entendimento de cada passo do processo de treinamento e análise.

## Contribuições
Contribuições são bem-vindas! Se deseja contribuir, por favor:
- Faça um fork do repositório.
- Crie um branch para suas modificações.
- Envie um pull request detalhando as mudanças propostas.

