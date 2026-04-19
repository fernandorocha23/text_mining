# Projeto de Text Mining

Este repositório contém um projeto de Text Mining focado na análise de sentimentos. O projeto foi reestruturado para seguir as melhores práticas de organização de projetos de Data Science, visando maior clareza, modularidade e reprodutibilidade.

## Estrutura do Projeto

```
. 
├── data/
│   ├── raw/             # Dados originais e imutáveis
│   ├── processed/       # Dados limpos e transformados
│   └── external/        # Dados externos (léxicos, etc.)
├── notebooks/           # Notebooks Jupyter para exploração e experimentação
├── src/                 # Código fonte modularizado (funções, classes)
├── models/              # Modelos treinados e serializados
├── reports/
│   └── figures/         # Gráficos e visualizações geradas
├── requirements.txt     # Dependências do projeto
└── README.md            # Este ficheiro
```

## Como Começar

1.  **Clonar o repositório:**
    ```bash
    git clone https://github.com/fernandorocha23/text_mining.git
    cd text_mining
    ```
2.  **Criar e ativar um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/macOS
    # venv\Scripts\activate   # Windows
    ```
3.  **Instalar as dependências:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Explorar os notebooks:**
    Os notebooks na pasta `notebooks/` podem ser executados para entender o fluxo de trabalho do projeto.

## Contribuição

Sinta-se à vontade para abrir *issues* ou *pull requests* para melhorias ou correções.
