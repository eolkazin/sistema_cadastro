# Registro de Consumo

Este projeto é uma aplicação gráfica em Python desenvolvida com a biblioteca `customtkinter`. Ele permite registrar o consumo de produtos, calcular preços com acréscimos e salvar os dados em planilhas ou arquivos de texto.

## Funcionalidades

- **Seleção de produtos**: Escolha entre uma lista de alimentos com preços.
- **Acréscimos**: Adicione itens extras ao pedido com preços específicos.
- **Cálculo de preço total**: Atualize o preço automaticamente com base nos acréscimos selecionados.
- **Registro de dados**: Salve as informações em uma planilha do Excel (se disponível) ou em um arquivo de texto.
- **Interface amigável**: Interface gráfica moderna e responsiva com `customtkinter`.
- **Controle de teste**: Bloqueia o uso do programa após a data limite configurada.

## Requisitos

- Python 3.10 ou superior.
- Bibliotecas necessárias:
  - `customtkinter`
  - `openpyxl`
  - `datetime`

## Instalação

1. Clone o repositório ou baixe os arquivos.
2. Instale as dependências necessárias:

```bash
pip install customtkinter openpyxl
```

## Como Usar

1. Execute o arquivo principal do programa:

```bash
python main.py
```

2. Insira o nome do cliente e selecione o alimento desejado.
3. Adicione os acréscimos, se necessário.
4. Clique no botão **Salvar** para registrar os dados.
5. Os dados serão salvos em uma pasta chamada `CLIENTES` no formato Excel ou texto, dependendo do sistema.

## Estrutura do Projeto

- **CLIENTES/**: Diretório onde os arquivos de registro são armazenados.
- **main.py**: Arquivo principal do programa.
- **README.md**: Este arquivo.

## Personalização

- Para alterar a lista de alimentos e acréscimos, edite as variáveis `alimentos` e `acrescimos` no código.
- A data limite do teste pode ser configurada na variável `data_limite`.

## Licença

© 2024 Sua Empresa - Todos os direitos reservados.
