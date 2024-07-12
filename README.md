# Automação de Cadastro de Produtos

Este projeto foi feito a partir de um treinamento, e o intuito dele é mostrar a aprendizagem da automação do processo de cadastrar uma base de cadastros em um site. 
O link do site em questão é:
https://dlp.hashtagtreinamentos.com/python/intensivao/login
Esse é um site dedicado para testar o funcionamento do código.

O mesmo utiliza a biblioteca `pyautogui` para interagir com a interface gráfica do usuário e a biblioteca `pandas` para manipulação de dados.

## Funcionalidades

- Abre o navegador web.
- Navega até a página de login do sistema.
- Realiza login automático.
- Lê os dados de produtos de um arquivo CSV.
- Preenche e submete formulários de cadastro para cada produto.

## Requisitos

- Python 3.x
- Bibliotecas Python: `pyautogui`, `pandas`

## Como Usar

- Certifique-se de que o navegador está na primeira posição da barra de tarefas.
- Antes de executar o script, é necessário corrigir as coordenadas de cliques na tela, que variam de acordo com a resolução do monitor.
- Execute o script.

O script irá:
- Abrir o navegador.
- Navegar até a página de login e realizar o login.
- Ler o arquivo `produtos.csv`.
- Preencher e submeter o formulário de cadastro para cada produto na lista.
