# Supermarket Sales Dashboard

Este projeto é um dashboard interativo criado usando Streamlit e Plotly Express para analisar vendas de um supermercado com foco em faturamento por unidade, tipo de produto mais vendido, contribuição por filial, desempenho das formas de pagamento, e avaliações das filiais.

## Funcionalidades

- **Faturamento por dia**: Visualize o faturamento diário por unidade (cidade).
- **Faturamento por tipo de produto**: Veja quais tipos de produtos geram mais receita.
- **Faturamento por filial**: Analise o desempenho de cada filial.
- **Faturamento por tipo de pagamento**: Entenda as preferências de pagamento dos clientes.
- **Avaliação das filiais**: Consulte as avaliações médias das filiais.

## Instalação

### Pré-requisitos

- Python 3.7 ou superior
- Pip (gerenciador de pacotes Python)

### Passos

1. **Clone o repositório**:

    ```bash
    git clone https://github.com/seu_usuario/seu_repositorio.git
    cd seu_repositorio
    ```

2. **Crie e ative um ambiente virtual**:

    No Windows:

    ```bash
    python -m venv venv
    .\venv\Scripts\activate
    ```

    No MacOS/Linux:

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Instale as dependências**:

    ```bash
    pip install -r requirements.txt
    ```

    **NOTA**: Caso não tenha um arquivo `requirements.txt`, crie um com o seguinte conteúdo:

    ```bash
    streamlit
    pandas
    plotly
    ```

4. **Crie o arquivo `.env`**:

    Dentro do diretório do projeto, crie um arquivo `.env` para armazenar as configurações e variáveis de ambiente. Exemplo de conteúdo do arquivo `.env`:

    ```env
    # Arquivo de configuração .env
    ```

    **NOTA**: Este arquivo é opcional, dependendo do que você precisa configurar para o projeto.

## Execução

Para executar o dashboard, utilize o comando:

```bash
streamlit run app.py
