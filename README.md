# 🤖 Smart Bauru

> Um Sistema de Informação Geográfica (SIG) para Mapeamento e Análise de Ocorrências Urbanas na cidade de Bauru–SP.

Este projeto utiliza técnicas de Ciência de Dados e *Web Scraping* para coletar, processar, analisar e visualizar problemas urbanos, oferecendo uma ferramenta para a formulação de políticas públicas mais eficazes e para o engajamento cívico.

---

## ✨ Funcionalidades Implementadas

- **Mapa interativo detalhado:** Visualização de ocorrências com marcadores individuais, popups informativos e um painel de filtros avançado. ![Mapa Interativo](/images/smart-bauru.png)
- **Mapa de calor:** Geração de um mapa de calor separado que mostra a concentração de **todas** as ocorrências, ideal para uma análise macro dos principais *hotspots* da cidade. ![Mapa de Calor](/images/mapa-calor.png)
- **Análise de recorrência:** Um *script* dedicado identifica e mapeia os locais exatos onde tipos de problemas específicos acontecem repetidamente, apontando para questões crônicas. ![Mapa de Recorrência](/images/mapa-recorrencias.png)
- **Análises específicas:** Exemplos de como analisar os dados para extrair *insights*, como análises sazonais e comparações entre ocorrências de importantes bairros da cidade.

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- **Linguagem:** Python
- **Análise e Manipulação de Dados:** Pandas, NumPy
- **Web Scraping:** BeautifulSoup, Selenium
- **Mapeamento e Geolocalização:** Folium, GeoPandas
- **Gráficos e Visualizações:** Matplotlib
- **Ambiente de Desenvolvimento:** PyCharm, Jupyter Notebook

## 🚀 Como Executar o Projeto

Siga os passos abaixo para configurar e executar o ambiente de análise.

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/f3l1pe-augusto/analise-ocorrencias-urbanas.git](https://github.com/f3l1pe-augusto/analise-ocorrencias-urbanas.git)
    cd analise-ocorrencias-urbanas
    ```

2.  **Crie e ative um ambiente virtual (recomendado):**
    ```bash
    # Para Windows
    python -m venv venv
    .\venv\Scripts\activate

    # Para macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Instale as dependências:**
    Crie um diretório chamado `requirements.txt` na pasta principal do projeto com o seguinte conteúdo:
    ```txt
    pandas~=2.2.3
    matplotlib~=3.10.3
    folium~=0.19.5
    ```
    Em seguida, instale-o com o pip:
    ```bash
    pip install -r requirements.txt
    ```
