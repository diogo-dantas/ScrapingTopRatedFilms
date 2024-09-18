# ScrapingTopRatedFilms

Projeto de web scraping utilizando as bibliotecas *Beautiful Soup* e *requests*, para  captar os 50 filmes com melhores classificações médias de acordo o site EverybodyWiki (https://en.everybodywiki.com/100_Most_Highly-Ranked_Films). As informações serão extraídas e exportadas para um arquivo csv e adicionadas a uma tabela em um banco de dados Movies.db que será criado através da biblioteca *sqlite3*.

## Pré-requisitos

Antes de começar, você precisa ter o Python instalado em sua máquina. Este projeto é compatível com o Python 3.6 ou superior.

### Instalando o Python

#### No Windows

1. Baixe o instalador do Python no [site oficial do Python](https://www.python.org/downloads/).
2. Execute o instalador e certifique-se de marcar a opção "Add Python to PATH" antes de clicar em "Install Now".

#### No macOS

1. Você pode instalar o Python usando o Homebrew. Se você ainda não tem o Homebrew instalado, siga as instruções em [brew.sh](https://brew.sh).

2. Execute o seguinte comando no Terminal:

   ```
   brew install python
   ```

#### No Linux

  Use o gerenciador de pacotes de sua distribuição. Por exemplo, no Ubuntu, execute:

    sudo apt update

### Instalação das Dependências

Depois de instalar o Python, você precisa instalar as dependências do projeto. Crie um ambiente virtual e instale as dependências usando pip:

Criar um Ambiente Virtual

    python -m venv venv

Ativar o Ambiente Virtual

No Windows:

    venv\Scripts\activate

No macOS/Linux:

    source venv/bin/activate

Instalar Dependências

    pip install -r requirements.txt

Executando o Projeto

Depois de instalar todas as dependências, você pode executar o projeto com o seguinte comando:

```
python webscraping_movies.py
```

