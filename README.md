# Pesquisa_Bootstrap_JS

Este projeto foi desenvolvido como parte do trabalho prático de JavaScript sobre requisições HTTP e manipulação de APIs. Utilizamos temas variados para busca e exibição dinâmica de dados.

## 👥 Integrantes do Grupo
ARTHUR RIBEIRO DE AZEVEDO 
CARLOS DANIEL GUALBERTO DOS SANTOS 
GUSTAVO SANTANA REBOLO 
HENRY MENEZES CARDOSO 
LARISSA EDUARDA BRAZ DA SILVA 
OTHÁVIO KAUAN GOMES CORRÊA 
RAFAELA MERLOTTO PARRILLA

## 🎯 Objetivo
Demonstrar o funcionamento do método fetch() .then() e .catch() para realizar requisições assíncronas, tratar as respostas do servidor e manipular o DOM para exibir os dados de forma visual no navegador.

## 🛠️ Tecnologias Utilizadas
**HTML:** Estrutura da página.
**JavaScript (ES6):** Lógica de requisição, Promises e manipulação do DOM.

## 📖 Conteúdo Abordado

### 1. O que é uma API e HTTP?
Explicamos o conceito de interface de programação e como o navegador solicita dados via protocolo HTTP.

### 2. Método fetch(), .then() e .catch()
Implementamos a estrutura de **Promises** para garantir que o código espere a resposta da API sem travar a aplicação.
**.then():** Utilizado para converter a resposta bruta em JSON e processar os dados de sucesso.
**.catch():** Utilizado para capturar e exibir mensagens de erro caso a requisição falhe.

### 3. Manipulação de Dados
Demonstramos como converter a resposta em um objeto manipulável e como usar o método forEach para criar elementos HTML dinamicamente.
**Diferencial:** Utilizamos o método .slice(0, 5) para filtrar e exibir apenas os 5 personagens principais da frota.

### 4. Tratamento de Erros
O código verifica a propriedade response.ok. Caso haja um erro de rede ou URL inválida, o usuário é alertado através de uma mensagem amigável no console ou via alert.

## 🚀 Como rodar o projeto
1. Baixe o arquivo index.html.
2. Abra o arquivo em qualquer navegador moderno.
3. Clique no botão **"Ver Personagens"** para disparar a requisição à API.

---
Trabalho de JavaScript - 2026