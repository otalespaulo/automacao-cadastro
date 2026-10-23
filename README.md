# automacao-cadastro
Automação de cadastros em sistema web utilizando Python, PyAutoGUI e Pandas para leitura de arquivos CSV e preenchimento automatizado de formulários.

# Automação de Cadastro de Produtos com Python

Projeto de automação desenvolvido durante meus estudos de Python, com o objetivo de automatizar o cadastro de produtos em um sistema web a partir de dados armazenados em um arquivo CSV.

## Tecnologias utilizadas

- **Python** — lógica e execução da automação.
- **Pandas** — leitura e manipulação dos dados do arquivo CSV.
- **PyAutoGUI** — automação de interações com a interface gráfica.
- **Pathlib** — localização do arquivo CSV a partir do diretório do script.
- **Time** — controle de pausas durante a execução.

## Funcionalidades

- Leitura dos dados de produtos a partir de um arquivo CSV.
- Abertura do navegador e acesso à página de cadastro.
- Preenchimento automatizado dos campos do formulário.
- Tratamento de observações vazias, evitando o preenchimento de valores ausentes.
- Envio automático dos formulários para cadastrar os produtos da tabela.

## Estrutura do projeto

```text
automacao-cadastro-produtos/
├── main.py
├── produtos.csv
├── requirements.txt
├── .gitignore
└── README.md
```

## Pré-requisitos

- Python instalado.
- Navegador Brave instalado.
- Acesso ao sistema web utilizado no projeto.
- Arquivo `produtos.csv` com as colunas esperadas pelo script.

## Instalação

1. Clone este repositório:

   ```bash
   git clone URL_DO_SEU_REPOSITORIO
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd automacao-cadastro-produtos
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

## Formato dos dados

O arquivo `produtos.csv` deve conter as seguintes colunas:

| Coluna | Descrição |
|---|---|
| `codigo` | Código do produto |
| `marca` | Marca do produto |
| `tipo` | Tipo do produto |
| `categoria` | Categoria do produto |
| `preco_unitario` | Preço unitário |
| `custo` | Custo do produto |
| `obs` | Observações opcionais |

Utilize dados de exemplo compatíveis com o sistema.

## Como executar

1. Coloque o arquivo `produtos.csv` na mesma pasta de `main.py`.
2. Confira se o navegador e o sistema estão acessíveis.
3. Execute o script:

   ```bash
   python main.py
   ```

4. Acompanhe a automação enquanto os produtos são preenchidos e enviados ao sistema.

**Importante:** a automação utiliza coordenadas fixas da tela e depende da posição dos elementos, da resolução e do estado da janela. Evite utilizar o computador durante a execução.

## Aprendizados

- Leitura e manipulação de dados com Pandas.
- Iteração sobre linhas de uma tabela.
- Automação de tarefas repetitivas com PyAutoGUI.
- Manipulação de caminhos de arquivos com Pathlib.
- Integração entre dados tabulares e preenchimento de formulários web.

## Observações

Este projeto foi desenvolvido como prática de aprendizagem, acompanhando um tutorial e adaptando o código ao meu ambiente de desenvolvimento.

A automação foi preparada para o sistema utilizado no exercício e pode exigir ajustes para funcionar em outros ambientes.
