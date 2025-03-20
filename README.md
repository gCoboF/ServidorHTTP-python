# Servidor HTTP com Pokédex

Um servidor HTTP simples implementado em Python que serve uma Pokédex interativa com informações sobre diferentes Pokémon.

## Descrição

Este projeto consiste em um servidor HTTP básico desenvolvido em Python que hospeda uma aplicação web de Pokédex. Os usuários podem navegar por diferentes Pokémon e visualizar suas características, tipos e evoluções.

![image](https://github.com/user-attachments/assets/68437ab1-76cf-4986-a6fc-a7a1c20463ee)

## Funcionalidades

- Servidor HTTP básico implementado em Python
- Suporte para requisições GET e PUT
- Interface web responsiva
- Visualização de informações detalhadas dos Pokémon
- Navegação entre evoluções dos Pokémon
- Suporte para imagens e arquivos HTML

## Estrutura do Projeto

ServidorHTTP-python/
│
├── servidorHTTP.py    # Arquivo principal do servidor

│
└── htdocs/       # Diretório com arquivos da aplicação web

├── index.html    # Página inicial

├── *.html        # Páginas individuais dos Pokémon

└── img/          # Diretório de imagens

## Como Executar

1. Certifique-se de ter o Python instalado em seu sistema
2. Clone ou baixe este repositório
3. Navegue até o diretório do projeto
4. Execute o servidor com o comando:

bash
python servidorHTTP.py

5. Abra seu navegador e acesse:
http://localhost:8080

![image](https://github.com/user-attachments/assets/305edc70-8c8f-49cf-971b-e7cb6134df44)


## Tecnologias Utilizadas
- Python
- Socket Programming
- HTML
- CSS
- JavaScript
  
## Características do Servidor
- Porta padrão: 8080
- Suporta múltiplas conexões
- Tratamento de erros básico
- Suporte para diferentes tipos de arquivos (HTML, imagens)
