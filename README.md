# Projeto | Acidentes de Trânsito em Porto Alegre

## Introdução ##
Este repositório contém o projeto de **Ciência de Dados** para o curso Ciência de Dados e Inteligência Artificial, que é parte da minha graduação em [Banco de Dados com ênfase em Data Analytics](https://online.pucrs.br/graduacao/banco-dados-enfase-data-analytics), gerenciado e ministrado pela PUCRS.

## Instruções de uso ##
1. **Clonar o repositório**. Clone o repositório para sua máquina.
```bash
git clone https://github.com/felipesebben/ds-acidentes-poa.git
```

2. **Navegar para o diretório do projeto**
```bash
cd ds-acidentes-poa
```

3. **Criar ambiente virtual**.
Usando `pip`:
```bash
python -m venv /.venv
```

Usando `poetry`, pode-se instalar todo o ambiente virtual sem a necessidade de criar manualmente o ambiente virtual.
```bash
poetry install
```

4. **Ativar o ambiente virtual**
Usando `pip`, use:
```bash
# Windows
env\Scripts\activate

# Unix ou MacOS
source env/bin/activate

poetry shell
```

Com `pip`, instale as dependências usando:
```bash
pip install -r requirements.txt
```

Com isto, ative os notebooks usando o kernel criado para o projeto.

## Fase 1 do Projeto ##
### Enunciado da fase 1 ####

- Procurem um conjunto de dados com, pelo menos, 1.000 linhas e 10 colunas, e que tenha um atributo alvo categórico ou numérico.

- Façam a carga no Orange Data Mining para ajudar na exploração.

- Transcrevam a síntese do conjunto de dados como apresentado em sua origem.

- Em até 3 parágrafos, expliquem o interesse em explorá-lo.

- Sobre o conjunto de dados escolhido:
    - Qual a finalidade do conjunto de dados?
    -   Quantas linhas e quantas colunas o conjunto de dados tem? 
    -   Qual o formato que ele é disponibilizado? (CSV, JSON, XLSX, etc)

- Escolham pelo menos 10 colunas totalmente preenchidas (as mais importantes) e, para cada coluna (inclusive para a coluna alvo):
    - Qual o nome e o que representa?
    - Qual o tipo de dados? Nominal/Ordinal/Numérico/Data e/ou hora?
    - Quais são os valores considerados válidos?
    - Quantos valores distintos aparecem na coluna?
    - Qual o menor e o maior valor, e qual a moda?
    - Os valores da coluna são numéricos? Qual a média e qual o desvio-padrão? Qual a mediana?

    - Qual a oportunidade para um projeto de ciência de dados foi identificada? Justificar a resposta!